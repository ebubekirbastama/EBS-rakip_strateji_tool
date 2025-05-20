🔎 RAKİP İÇERİK STRATEJİSİ ANALİZ ARACI (GUI) 
======================================================

📌 Bu proje, belirli bir anahtar kelime için Google aramalarında çıkan 
ilk 3 domain üzerinde "site:domain.com anahtar kelime" mantığıyla 
tersine mühendislik yaparak içerik stratejisi analiz etmenizi sağlar.

![EBS](https://raw.githubusercontent.com/ebubekirbastama/EBS-rakip_strateji_tool/refs/heads/main/ebs1.png)

🎯 NE İŞE YARAR?
----------------------
- Belirli bir kelime için rakip siteleri tespit eder.
- Her domain içinde o anahtar kelimeyle ilgili sayfaları listeler.
- Çıkan sonuçları Excel'e tek tıkla aktarır.
- Modern, emojili bir arayüze sahiptir.
- Otomatik olarak eksik Python kütüphanelerini kurar.
- Threading desteği sayesinde arayüz kasmaz.

📦 GEREKENLER
----------------------
- Python 3.7+
- internet bağlantısı

Kullanılan kütüphaneler:
- tkinter
- googlesearch-python
- openpyxl

❗ Program ilk açıldığında eksik modüller varsa otomatik olarak yükler.

💻 KULLANIM
----------------------
1. Python kurulu değilse: https://www.python.org/downloads/
2. Bu scripti çalıştır:
   python analiz_gui.py
3. Anahtar kelimeyi gir ve "🚀 Analizi Başlat" butonuna tıkla
4. Sonuçları görmek ve Excel'e aktarmak için "💾 Excel'e Aktar" butonunu kullan

🛠️ EXE DOSYASINA ÇEVİRME (Opsiyonel)
----------------------
PyInstaller ile EXE’ye dönüştürmek için:
   pip install pyinstaller
   pyinstaller analiz_gui.py --onefile --noconsole

📁 LİSANS
----------------------
MIT Lisansı – dilediğiniz gibi kullanabilir, geliştirebilir ve paylaşabilirsiniz.

✉️ İLETİŞİM
----------------------
Geliştirici: [ebubekirbastama]  
Proje Sayfası: https://github.com/ebubekirbastama/EBS-rakip_strateji_tool


