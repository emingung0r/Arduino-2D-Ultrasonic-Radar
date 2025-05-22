
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

*(İsteğe bağlı olarak görsel buraya eklenebilir)*

---

## 👨‍💻 Geliştirici

**Abdurrahman Güngör**

Yorumlu kodlar ve görsel açıklamalar dahil edilmiştir.

---

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.
