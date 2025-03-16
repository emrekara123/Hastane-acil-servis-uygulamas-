# **Hastane Acil Servis Uygulaması**

## **Proje Açıklaması**
Bu proje, hastane acil servisinde hasta kayıtlarını yönetmek ve hastaları aciliyet sırasına göre işleme almak için geliştirilmiş bir konsol tabanlı uygulamadır. Hastalar aciliyet seviyelerine göre sıralanarak öncelikli kuyruk yapısında işlenir.

## **Özellikler**
- Hasta ekleme (Ad, Yaş, Aciliyet durumu)
- Hastaları öncelik sırasına göre listeleme
- Öncelikli hastayı işleme alma
- Hasta bilgilerini HL7 formatında görüntüleme
- Reçete yazma ve reçete numarası üretme

## **Kurulum**
### **1. Depoyu Klonlayın**
```sh
git clone https://github.com/emrekara123/Hastane-acil-servis-uygulamas-.git
```
### **2. Derleme ve Çalıştırma**
```sh
gcc hastane.c -o hastane
./hastane
```

## **Kullanım**
Uygulama açıldığında aşağıdaki menü ile karşılaşacaksınız:
1. Hasta Ekle
2. Hasta Listele
3. Hasta İşleme Al
4. Reçete Yaz
5. Çıkış

Komut satırından ilgili numarayı seçerek işlemleri gerçekleştirebilirsiniz.

## **Akış Şeması ve Çalışma Mantığı**
Proje ile ilgili detaylı analiz ve akış şemaları için **[Proje Analiz Dokümanı](docs/proje_analiz.md)** dosyasına göz atabilirsiniz.

## **Ekstra Bilgi**
Bu proje, öncelikli kuyruk (priority queue) yapısını kullanarak hastaları aciliyet seviyelerine göre sıralar. Böylece yüksek aciliyetli hastalar öncelikli olarak işleme alınır. 

Kullanıcı dostu bir arayüze sahip olup, hastane yönetim sistemlerine entegrasyonu kolaylaştırmak için HL7 formatında veri çıktısı sağlamaktadır. Reçete yazma fonksiyonu, her hasta için benzersiz bir reçete numarası üretir ve bu sayede kayıt takibini kolaylaştırır.

Projeyi geliştirirken C programlama dilinin dinamik bellek yönetimi ve bağlı listeler (linked list) gibi temel veri yapılarından faydalanılmıştır. Bu sayede hasta ekleme ve işleme alma işlemleri verimli bir şekilde gerçekleştirilir.

## **Lisans**
Bu proje açık kaynak olup MIT lisansı ile lisanslanmıştır.

