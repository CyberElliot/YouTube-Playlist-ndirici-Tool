# 📥 YouTube Playlist Downloader

YouTube üzerindeki **playlist’leri tek parça MP4 (video + ses)** formatında indirmek için geliştirilmiş, Python tabanlı bir **CLI (Command Line Interface)** uygulamasıdır.

Proje, `yt-dlp` ve `ffmpeg` kullanarak videoları yüksek uyumlulukta indirir ve **AAC ses codec’i** ile birleştirerek Windows Media Player dahil olmak üzere yaygın oynatıcılarda sorunsuz çalışacak dosyalar üretir.

---

## 🚀 Özellikler

- 📂 YouTube playlist indirme desteği  
- 🎥 Video + ses birleşik MP4 çıktı  
- 🔊 AAC ses codec (codec hatalarını önler)  
- 🔢 Playlist sırasına göre otomatik dosya adlandırma  
- ⚙️ Otomatik ffmpeg entegrasyonu  
- 🖥️ Windows EXE olarak dağıtım (Python kurulumu gerekmez)  
- ⌨️ Basit ve hızlı CLI arayüzü  

---

## 🖥️ Platform Desteği

### ✅ Windows
- **Stabil ve aktif olarak çalışmaktadır**
- EXE dosyası üzerinden direkt çalıştırılabilir
- Ek Python veya bağımlılık kurulumu gerekmez

### ⚠️ Android
- **Geliştirme aşamasında**
- Mobil arayüz ve sistem entegrasyonu üzerinde çalışmalar sürmektedir
- İlerleyen sürümlerde eklenecektir

---

## 🛠️ Kullanılan Teknolojiler

- **Python 3**
- **yt-dlp**
- **ffmpeg**
- **PyInstaller**
- **Inno Setup (Windows Installer)**

---

## 📦 Kullanım (Windows)

1. EXE dosyasını çalıştırın  
2. Playlist linkini girin  
3. İndirme yapılacak klasörü belirtin  
4. İndirme işlemi otomatik olarak başlar  

```txt
Playlist linki: https://www.youtube.com/playlist?list=XXXX
Kayıt yolu: C:\Users\Username\Desktop
