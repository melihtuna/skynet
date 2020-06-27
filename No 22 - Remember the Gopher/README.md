# Go Dilinin Temellerini Hatırlamak

Bu çalışmadaki amacım epey süre ara verdiğim go dilinin temellerini hatırlamak.

## Ön Hazırlıklar

Örneklere başlarken Heimdall _(Ubuntu 20.04)_ üstünde go dili için gerekli ortamın hazır olmadığını fark ettim. Dolayısıyla bir kurulum yapmam gerekti. İlk olarak [şu](https://golang.org/dl/) adresten uygun sürümü indiri usr/local altına açtım.

```bash
#Downloads klasörüne inen dosyayı talimatlara uyarak /usr/local altına açtım
sudo tar -C /usr/local -xzf go1.14.4.linux-amd64.tar.gz 
```

Sonrasında /etc klasörü altındaki profile dosyasının sonuna aşağıdaki yol tanımını ekledim. 

```text
export PATH=$PATH:/usr/local/go/bin
```

Sisteme tekrak giriş yaptıktan sonra yüklenmiş go sürümüne baktım.

![Screenshot_01.png](./assets/Screenshot_01.png)

Her şey yolundaydı ve kodlamaya geçebilirdim.

## Çalışma Zamanı

Örnekler birden fazla dosyadan oluşuyor. Sırasıyla örneklerin build ve çalışma zamanı görüntüleri aşağıdaki gibidir.

```bash
#Build işlemi
go build IHateHelloWorld.go
# ve dosya adını kullanarak programı çalıştırma
./IHateHelloWorld
```

![Screenshot_02.png](./assets/Screenshot_02.png)

```bash
go build AFewMethods.go
./AFewMethods
```

![Screenshot_03.png](./assets/Screenshot_03.png)

>To Be Continued

## Bölümün Bomba Soruları

>To Be Continued

## Ödevler

- Kullanıcının terminalden gireceği komutlara göre şu senaryoyu işleyecek kodu yazın._Kullanıcı "types" yazdığında go'da kullanılan temel tipler ekrana yazdırılsın. "rand" yazdığında ekrana rastgele bir sayı yazsın."today" yazdığından günün tarihini ve hangi günde olduğumuzu yazsın. "alan dikdortgen 4 5" yazdığında dikdortgenin alanını hesaplayıp yazsın ve hatta 5X4 lük + işaretlerinden oluşan dikdörtgeni terminale çizsin. "quit" dediğinde programdan çıksın_

>To Be Continued