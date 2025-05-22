
# Arduino Tabanlı 2D Ultrasonik Radar Görüntüleme Sistemi

Bu proje, **Arduino** ve **Processing** kullanılarak geliştirilen bir 2D radar simülasyonudur. Radar, ultrasonik sensör ile mesafe verisi toplar ve bu veriyi seri haberleşme ile bilgisayara gönderir. Bilgisayarda çalışan Processing arayüzü, bu veriyi görsel bir radar ekranında dinamik olarak gösterir.

---

## 📦 Proje Yapısı

```
arduino_radar_project/
│
├── ARDUNİOsketch_aug15a/
│   └── sketch_aug15a.ino              # Arduino kodu (servo + ultrasonik sensör)
│
├── PROSSİNGsketch__al__ansketch_250521a/
│   ├── sketch__al__ansketch_250521a.pde  # Processing arayüz kodu
│   └── data/                              # (varsa) font veya ses dosyaları
```

---

## 🧰 Gereksinimler

- Arduino UNO veya benzeri bir mikrodenetleyici
- HC-SR04 Ultrasonik Mesafe Sensörü
- SG90 veya benzeri Servo Motor
- Arduino IDE
- Processing IDE
- Bağlantı için USB kablo

---

## 🚀 Kurulum ve Kullanım

1. Arduino IDE'yi açın ve `sketch_aug15a.ino` dosyasını yükleyin.
2. Sensörü ve servoyu doğru pinlere bağlayın.
3. Processing'de `sketch__al__ansketch_250521a.pde` dosyasını açın.
4. **`myPort = new Serial(this, "COM7", 9600);`** satırındaki `COM7` değerini kendi bilgisayarınızdaki porta göre değiştirin.
5. Çalıştırın ve radar ekranını izleyin.

---

## 🖼️ Ekran Görüntüsü

<h3 align="center">📸 Radar Arayüz Görselleri</h3>

<p align="center">
  <img src="https://r.resimlink.com/DWlvfC-QLmZ.jpeg" alt="Radar1 - Tehlike" width="480" style="margin-right: 10px;"/>
  <img src="https://r.resimlink.com/7F2pkiPm6V.jpeg" alt="Radar2 - Güvenli" width="480"/>
</p>
<p align="center">
  <b>Radar1 - Geniş Alan Taraması</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>Radar2 - Güvenli Mesafe</b>
</p>

<br/>

<p align="center">
  <img src="https://r.resimlink.com/b-QHuWvsP.jpeg" alt="Radar3 - Orta Risk" width="480" style="margin-right: 10px;"/>
  <img src="https://r.resimlink.com/G6U7CV.jpeg" alt="Radar4 - Geniş Tarama" width="480"/>
</p>
<p align="center">
  <b>Radar3 - Orta Risk Alanı</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>Radar4 - Tehlike Durumu</b>
</p>

---

## 👨‍💻 Geliştirici

**Abdurrahman Güngör**

Yorumlu kodlar ve görsel açıklamalar dahil edilmiştir.

---

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.
