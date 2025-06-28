🔓 Anonymous Login FTP Checker
🎯 Amaç:
Bu araç, verdiğiniz .txt dosyasındaki IP adresleri üzerinde FTP servisine anonim giriş (anonymous login) açık mı değil mi kontrol eder.

📦 Özellikler
✅ Basit terminal arayüzü
✅ IP listesi üzerinden otomatik kontrol
✅ Başarılı giriş yapılan IP’leri basarili.txt dosyasına kaydeder
✅ Renkli çıktı (Colorama ile göz alıcı terminal)
✅ Hataları yakalar ve loglar
✅ Python 3 uyumlu, ftplib kullanır

🛠 Gereksinimler
bash
Kopyala
Düzenle
pip install colorama
📁 IP Dosyası Formatı
Sadece IP içeren bir .txt dosyası:

```192.168.1.10 ``` 
```93.184.216.34 ``` 
```213.128.72.183``` 


🚀 Kullanım

```https://github.com/Jyxlor-web/ftpchecker.git```

```cd ftpchecker```

```python3 tool1.py```

```python3 ftp_anon_checker.py```
Sonra:
📎 Sana Sadece IP içeren .txt dosya yolunu girin: diye soracak.
Örnek:


```/home/kullanici/Desktop/iplistesi.txt```
📂 Çıktı
Terminalde başarılı/başarısız giriş durumu yazılır.

basarili.txt içine başarılı giriş yapılan IP’ler kaydedilir.

🧠 Teknik


Giriş denemesi:


ftp.login('anonymous', '')
Bu, birçok eski FTP sunucusunda kullanıcı adı/şifre gerektirmeyen klasik anonim login yöntemidir.

⚠️ Uyarı
Bu araç sadece:

Eğitim amaçlıdır

Yetkili ağlar üzerinde kullanılmalıdır

İzinsiz erişim yasalara aykırıdır

Sorumluluk kullanıcıya aittir.

My Channel t.me/nextahackteam t.me/Jyxlorzirve
