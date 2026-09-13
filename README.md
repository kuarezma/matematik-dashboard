# T.C. Millî Eğitim Bakanlığı • Ortaokul Matematik Zümresi Master Doküman Portalı (5, 6, 7, 8. Sınıf)

Türkiye Yüzyılı Maarif Modeli ve MEB müfredatına tam uyumlu; 5, 6, 7 ve 8. Sınıf (LGS) seviyelerinde çift öğretmen adına bağımsız kurumsal kimliklerle hazırlanmış resmî matematik çalışma kağıtları, paralel A/B sınavları, çıkış biletleri, rubrikler, akıllı tahta oyunları ve yapay zekâ kamera tabanlı mobil optik okuma sistemini içeren canlı bulut doküman merkezidir.

---

## 🌐 Canlı Yayındaki Bağlantılar

- 🚀 **Master Zümre Portalı (GitHub Pages):** [https://kuarezma.github.io/matematik-dashboard/](https://kuarezma.github.io/matematik-dashboard/)
- 📱 **Mobil Kamera Tabanlı Optik Okuyucu:** [https://kuarezma.github.io/optik-okuyucu/?anahtar=zumre2026](https://kuarezma.github.io/optik-okuyucu/?anahtar=zumre2026) *(Yedek PIN: `2026`)*

---

## 🏫 Zümre Öğretmenleri & Kurumsal Kimlik Ayrımı

Tüm evraklar çift öğretmen adına bağımsız olarak üretilmiştir:

1. **Demet GÜRHAN YAŞAYAN**
   - **Okul:** Yavuz Selim Ortaokulu
   - **Okul Müdürü:** Ali Rıza HACIOĞLU
   - **Rol:** Matematik Öğretmeni

2. **Uğur YAŞAYAN**
   - **Okul:** Alparslan Ortaokulu
   - **Okul Müdürü:** Mustafa ÖZKAN
   - **Rol:** Matematik Zümre Başkanı

---

## 🎯 Özellikler

1. **Çift Öğretmen & Çift Format Desteği:**
   - Standart ve Paralel (Grup A / B) 12 soruluk MEB formatında çalışma kağıtları (Öğrenci & Adım adım çözümlü Öğretmen nüshaları).
   - Hem **PDF** (yüksek çözünürlüklü baskıya hazır 2 sayfa A4) hem de **Word (.docx)** düzenlenebilir formatları.
2. **4'lü Kesilebilir Mikro Çıkış Biletleri:**
   - Ders sonu 5 dakikalık hızlı süreç değerlendirmesi için A4 tek sayfada 4 adet mikro bilet (Öğrenci ve Çözümlü Öğretmen).
3. **Akıllı Optik Analiz & Teşhis Tablosu (.xlsx):**
   - 28-30 kişilik formüllü, grafikli sınıf not çizelgesi ve MEB Maarif Modeli soru-kazanım güçlük analizi.
4. **Resmî Analitik Rubrik & Süreç Gözlem Çizelgesi:**
   - 2 sayfalık analitik puanlama anahtarı ve öğrenci süreç takip matrisi.
5. **Akıllı Tahta HTML5 Matematik Oyunları:**
   - 5, 6, 7 ve 8. sınıflar için dokunmatik akıllı tahta uyumlu offline çalışabilen etkileşimli eğitim oyunları.
6. **Mobil Optik Okuyucu (PWA):**
   - Telefon ve tablet kamerasından saniyeler içinde optik form okuma, anlık puanlama ve doğrudan Excel aktarımı.

---

## 🛠️ Yerel Güncelleme ve Dağıtım

Yeni haftalık dokümanlar üretildiğinde tek komutla statik portalı güncellemek ve GitHub Pages'e göndermek için:

```bash
python3 build_portal.py
cd matematik-dashboard
git add .
git commit -m "feat: haftalik evraklar ve analiz verileri guncellendi"
git push origin main
```
