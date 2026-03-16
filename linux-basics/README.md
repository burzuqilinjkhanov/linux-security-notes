# Linux Basics

Basic Linux commands used in terminal.

This section contains my personal notes while learning Linux.

---

## User Information

### whoami

Mevcut oturumda hangi kullanıcı ile giriş yaptığımı gösterir.

---

## Directory Navigation

### pwd

Bulunduğum klasörün tam yolunu gösterir.

### ls

Bulunduğum klasördeki dosya ve klasörleri listeler.

### ls -l

Dosyaları daha detaylı şekilde gösterir.

### ls -la

Gizli dosyalar dahil tüm dosyaları gösterir.

---

## Directory Movement

### cd

Bir klasöre girmek için kullanılır.

### cd ..

Bir üst klasöre çıkmak için kullanılır.

### cd /

Root dosya sistemine gider.

---

## File Operations

### touch
touch file.txt
Yeni bir dosya oluşturur.

### cp
cp file.txt copy.txt
Dosya kopyalamak için kullanılır.

### mv
mv file.txt newfile.txt
Dosya taşımak veya ismini değiştirmek için kullanılır.

### rm
rm file.txt
Dosya silmek için kullanılır.

rm -rf klasörismi
⚠️ Dikkat:  Klasör silmek (Zorla silmek)
            Bu komut dosyaları **geri dönüşü olmadan siler**.
