# Kernel Panic Günlükleri – Bir Yazılımcının Bürokrasiyle İmtihanı

> **“B2B öldü, yaşasın B2C!”**

---

## İçindekiler

1. Bürokrasi Görünce Kaybolan Yazılımcı  
2. Kurşun adres sormaz ama bellek sorar  
3. Copilot ile geri vites  
4. OOM & Leğenle Bellek Yönetimi  
5. `sleep(-1000)` ve diğer low-level hayat dersleri  
6. Masal: Evvel zaman içinde uzaktan çalışan küçük bir Fatih varmış  

---

## 1. Bürokrasi Görünce Kaybolan Yazılımcı

Toplantıda biri “KDV nasıl olacak?” dediğinde:

```

panic: unable to mount muhasebe filesystem
reboot required

```

Fatih: graceful shutdown, Can Yılmaz izle ve kahve al 😎

---

## 2. Kurşun adres sormaz ama bellek sorar

```

Kurşun: FIRE AND FORGET
Pointer: FIRE AND SEGFAULT

```

Her pointer developer’ın içinden geçen bir felsefi gerçek.

---

## 3. Copilot ile geri vites

- Ticket at → Copilot çözer  
- Review takılırsa → Fatih fixler  
- Müdür “Fatura?” deyince → `kernel panic`

```

while(bureaucracy)
sleep(-1000);

````

---

## 4. OOM & Leğenle Bellek Yönetimi

Bellek sızınca:

```bash
bucket = new Leğen();
place(bucket, under(memory));
````

* RAM %95
* Leğen %100 dolu
* Sonuç: stres minimal, mizah maksimum 😂

---

## 5. sleep(-1000) ve diğer low-level hayat dersleri

```
sleep(-1000) 
// Anlamı: “Beni 1000 saniye geriye uyut”
```

* Negatif uyku = pozitif stres
* En güvenli alternatif: `ignore_bureaucracy(); relax(); watch_can_yilmaz();`

---

## 6. Masal

Evvel zaman içinde, kalbur saman içinde,
uzak bir şehirde, uzaktan çalışan küçük bir Fatih varmış. 😄

> * Kod yazıyor
> * Bürokrasi canavarıyla savaşıyor
> * Copilot’a ticket paslıyor
> * En sonunda B2B’yi bırakıp B2C’ye geçiyor

Ve gökten üç elma düşmüş:

1. Kod yazanlara
2. Mizah yapanlara
3. `rm -rf /` yazıp göndermeyenlere 😂

---

## Slogan

```
Kod var, bürokrasi yok.
```

---

> **Not:** Bu proje tamamen mizah amaçlıdır. Gerçek hayat bürokrasi veya finansal tavsiye içermez.

