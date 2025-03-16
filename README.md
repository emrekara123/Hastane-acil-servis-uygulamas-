Hastane Acil Servis Uygulaması

Proje Açıklaması

Bu proje, hastane acil servisinde hasta kayıtlarını yönetmek ve hastaları aciliyet sırasına göre işleme almak için geliştirilmiş bir konsol tabanlı uygulamadır. Hastalar aciliyet seviyelerine göre sıralanarak öncelikli kuyruk yapısında işlenir.

Özellikler

Hasta ekleme (Ad, Yaş, Aciliyet durumu)

Hastaları öncelik sırasına göre listeleme

Öncelikli hastayı işleme alma

Hasta bilgilerini HL7 formatında görüntüleme

Reçete yazma ve reçete numarası üretme

Kurulum

1. Depoyu Klonlayın

git clone https://github.com/emrekara123/Hastane-acil-servis-uygulamas-.git

2. Derleme ve Çalıştırma

gcc hastane.c -o hastane
./hastane

Kullanım

Uygulama açıldığında aşağıdaki menü ile karşılaşacaksınız:

Hasta Ekle

Hasta Listele

Hasta İşleme Al

Reçete Yaz

Çıkış

Komut satırından ilgili numarayı seçerek işlemleri gerçekleştirebilirsiniz.

Akış Şeması ve Çalışma Mantığı

Proje ile ilgili detaylı analiz ve akış şemaları için proje analiz dokümanına göz atabilirsiniz.
