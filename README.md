# 📝 Minimal ToDo

Minimal ToDo, sade ve kullanıcı dostu bir yapılacaklar listesi (ToDo) uygulamasıdır. Görev ekleme, detay görüntüleme, tamamlama, düzenleme ve silme işlemlerini destekler. Expo + React Native ile geliştirilmiştir.

![Minimal ToDo Screenshot](./assets/splash-icon.png)

---

## 🚀 Özellikler

- Görev ekle
- Görev detaylarını gör
- Görevleri tamamlandı/aktif olarak işaretle
- Görev sil
- Uygulama kapanıp açılsa bile veriler kaybolmaz (AsyncStorage desteği)

---

## 📱 Ekranlar

- **Ana Sayfa:** Tüm görevleri listeler
- **Görev Ekle:** Yeni görev tanımlama ekranı
- **Görev Detayı:** Görev detaylarını görme, silme ve tamamlama

---

## 🛠️ Kurulum

### 1. Depoyu Klonla

```bash
git clone https://github.com/ozzencben/minimal-todo.git
cd minimal-todo
```

### 2. Gerekli Paketleri Kur

```bash
npm install
```

### 3. Uygulamayı Başlat

```bash
npx expo start
```

Expo Go uygulaması ile telefonundan veya emulator üzerinden çalıştırabilirsin.

---

## 💾 Kalıcılık (Persist)

Görevler `AsyncStorage` kullanılarak yerel bellekte tutulur. Böylece uygulamayı kapatsan bile görevler kaybolmaz.

---

## 📁 Proje Yapısı

```
minimal-todo/
├── assets/           # Görseller
├── context/          # Global task context
├── screens/          # Tüm ekran bileşenleri
├── App.js            # Uygulama girişi
├── README.md         # Bu dosya
└── ...
```

---

## 📌 Kullanılan Teknolojiler

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [React Navigation](https://reactnavigation.org/)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/)
- [React Context API](https://reactjs.org/docs/context.html)

---

## 👨‍💻 Geliştirici

**Özenç Dönmezer**  
📧 [ozzencben@gmail.com](mailto:ozzencben@gmail.com)  
🔗 [LinkedIn Profilim](https://www.linkedin.com/in/%C3%B6zen%C3%A7-d%C3%B6nmezer-769125357/)  
💻 [GitHub](https://github.com/ozzencben)

---

## 📃 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına göz atın.