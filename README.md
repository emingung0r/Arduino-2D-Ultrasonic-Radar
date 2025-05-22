<p align="center">
  <img src="https://r.resimlink.com/mjosL.png" alt="Arduino Logo" width="300"/>
</p>

<h1 align="center">
  Arduino Tabanlı 2D Ultrasonik Radar<br>
  Görüntüleme Sistemi
</h1>

<p align="center">
  <a href="https://instagram.com/emin.gung0r">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="https://linkedin.com/in/emin.gung0r">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://x.com/emin.gung0r">
    <img src="https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white" alt="X">
  </a>
</p>

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

1. **Arduino IDE'yi açın** ve `sketch_aug15a.ino` dosyasını yükleyin.

2. **Donanımı bağlayın:**  
   Ultrasonik sensörü ve servo motoru uygun pinlere bağlayın.

3. **Processing IDE'yi açın** ve `sketch__al__ansketch_250521a.pde` dosyasını açın.

4. Aşağıdaki satırı bulun ve `COM7` ifadesini kendi portunuza göre değiştirin:

   ```java
   myPort = new Serial(this, "COM7", 9600);

  5.Processing uygulamasını çalıştırın ve radar arayüzü açıldığında anlık olarak nesne taramasını izleyin.

---

## 🖼️ Ekran Görüntüsü

<h3 align="center">📸 Radar Arayüz Görselleri</h3>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://r.resimlink.com/X4-U1eYlR7K6.jpeg" alt="Radar1" width="100%"><br>
      <b>Radar 1 - Geniş Alan Taraması</b>
    </td>
    <td align="center" width="50%">
      <img src="https://r.resimlink.com/7F2pkiPm6V.jpeg" alt="Radar2" width="100%"><br>
      <b>Radar 2 - Güvenli Mesafe</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://r.resimlink.com/b-QHuWvsP.jpeg" alt="Radar3" width="100%"><br>
      <b>Radar 3 - Orta Risk Alanı</b>
    </td>
    <td align="center" width="50%">
      <img src="https://r.resimlink.com/G6U7CV.jpeg" alt="Radar4" width="100%"><br>
      <b>Radar 4 - Tehlike Durumu</b>
    </td>
  </tr>
</table>


---

## 👨‍💻 Geliştirici

**Abdurrahman Güngör**

Yorumlu kodlar ve görsel açıklamalar dahil edilmiştir.

---

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.
