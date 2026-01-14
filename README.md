# 🚗 Araç Değer Kaybı Analiz Sistemi

Bu proje, trafik kazası sonrası araçlarda oluşan değer kaybını hukuki katsayılar kullanarak hesaplayan ve potansiyel müşteri verilerini **Google E-Tablolar**'a anlık olarak ileten modern bir web uygulamasıdır.



## 🌟 Özellikler

- **Akıllı Hesaplama:** Hasar tutarı ve kilometre verilerine dayalı hukuki analiz.
- **Anlık Veri Kaydı:** Form verileri Google Apps Script aracılığıyla doğrudan Google Sheets'e iletilir.
- **Modern Arayüz:** Plus Jakarta Sans yazı tipi ve akıcı CSS animasyonları ile kullanıcı dostu tasarım.
- **Mobil Uyumluluk:** Tüm telefon ve tabletlerle %100 uyumlu responsive yapı.

## 🛠️ Teknoloji Yığınları

- **Frontend:** HTML5, CSS3 (Modern Flexbox), JavaScript (ES6+)
- **Backend:** Google Apps Script (Serverless)
- **Veri Depolama:** Google Sheets API
- **Barındırma:** GitHub Pages

## 📋 Kurulum ve Dağıtım

Sistemi kendi alan adınızda çalıştırmak için:

1. Bu depoyu (repository) fork'layın veya kopyalayın.
2. `index.html` içindeki `scriptURL` değişkenini kendi Google Apps Script URL'nizle değiştirin.
3. GitHub Ayarlarından **Pages** sekmesine giderek `main` dalını yayına alın.
4. Alan adı (Custom Domain) ayarlarınızı yaparak HTTPS sertifikasını aktif edin.

## 📊 Veri Akışı Nasıl Çalışır?

1. Kullanıcı site üzerindeki formu doldurur.
2. JavaScript, verileri JSON formatına dönüştürür.
3. `fetch` API ile Google Apps Script'e `POST` isteği gönderilir.
4. Script, gelen veriyi yakalar ve Google E-Tablo'ya yeni bir satır olarak ekler.

---
*Bu proje hseyn0003-cmyk tarafından geliştirilmiştir.*
