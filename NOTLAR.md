# Faraday Etüt Merkezi – Landing Page Notları

> Tasarım v2: editorial/studio yeniden tasarım (kart-grid yerine hairline liste düzeni, Fraunces serif başlıklar, muted altın).
> Scroll animasyonları: altın ilerleme çizgisi, başlık clip-reveal, görsellerde maske+zoom-out, kademeli stagger, hero parallax. `prefers-reduced-motion` desteği var.

## Kaynaklardan doğrulanan bilgiler
| Bilgi | Kaynak |
|---|---|
| Telefon / WhatsApp: **0541 140 65 45** (wa.me/905411406545) | Instagram gönderi intens (@p/DRZ-0oCivJz, @reel/DPybWi7Cjqy) + vansiyaseti.com haberi |
| Adres: Cumhuriyet Caddesi, Değer İş Merkezi Kat 6 (Anadolu Sahaf Kırtasiye ön sokağı), İpekyolu/Van | Haber + IG |
| 75 nitelikli Türkiye geneli AYT-TYT seri deneme; Aralık'tan itibaren haftada 2 TYT-AYT denemesi; deneme sonrası hata/sonuç analiz kâğıdı | IG post @p/DeHMmAtqlTK, @p/De2RnuuvZWt |
| Cumartesi–Pazar deneme; sınırsız Wi-Fi; klima; kişiye özel dolaplar; prizli masalar; kantin | Salih Beyoğlu (işletme yöneticisi) Facebook video metni |
| 789 takipçi, 26 gönderi | Instagram profili (01.11.2026) |
| Slogan: "Hayalleriniz korumamız altında" | vansiyaseti.com haberi (12.06.2025 / 10.06.2025) |
| **Kazanan puanları: 16 Tıp, 26 Diş Hekimliği, 57 Eczacılık, 17 Hukuk, 24 Özel Öğretim** ("İlk yılımızda Van'ın en iyisi olarak YKS 2026'yı geride bıraktık" · Devlet üniversiteleri puanı esas alınmış) | IG reel kapağı (c17 → `afis-kazananlar.jpg`) |
| İkinci hesap: @faradaydenememerkezi | SKZ afiş alt bandı |
| Takvim afişi adres detayı: "Cumhuriyet Caddesi Şerefiye Mah. Köseoğlu 1. Sokak Değer İş Merkezi 6. kat" | 2026 YKS takvim afişi (c9) |
| Öne çıkanlar: ✅KAZANANLAR✅, ✏️SERİ DENEME✅, ✏️KPSS DENEME✅, ✏️YKS DENEME✅ | Hikâye öne çıkanları |

## Kullanılan görseller (images/)
- `logo.jpg` – Instagram profil fotoğrafı (150px, lacivert amblem) — header, hero, footer, favicon
- `salon2.webp` – Gerçek salon (boş) — hero arka plan + galeri
- `salon3.webp` – Marka duvarı — galeri
- `salon1.webp` – Haber künyeli açılış karesi — yedek (kullanılmıyor; istersen galeriye ekle)
- `afis-haftada2.jpg` – "Haftada 2 TYT-AYT" afişi (içinde DOLU salon fotoğrafı var) — Deneme bölümü
- `afis-75.jpg` – "75 nitelikli seri deneme" afişi — Deneme bölümü
- `afis-takvim.jpg` – 2026 YKS deneme takvimi (yazar yayınlar) — Deneme bölümü
- `afis-kampanya.jpg` – "Büyük Kampanya" afişi — Kampanya şeridi
- `afis-kayit.jpg` – "Kayıtlar açıldı / 345 All Star" afişi — Kampanya şeridi
- `afis-yks.jpg` – "YKS'de başarıyı yakala" afişi — Kampanya şeridi
- `bina.jpg` – Bina dış görünümü (Instagram hikâye polaroid kırpımı) — Konum bölümü
- `afis-kazananlar.jpg` – ✅KAZANANLAR✅ puan afişi (16 Tıp / 26 Diş / 57 Eczacılık / 17 Hukuk / 24 Öz. Öğretim) — Kazananlar bölümü
- `ekip.jpg` – Merkez içinden reels karesi (mola/kitap köşesi, ekip; siyah bantlar kırpıldı) — Galeri

Kaynaklar: Instagram CDN @faradayetutmerkezi (01.11.2026 çekimi) + vansiyaseti.com açılış haberi (10.06.2025).
CDN imzası zaman aşımına uğradığından hikâye öne çıkanları (Kazananlar, Seri Deneme... yıldızlı kapaklar) indirilemedi — indirdiğin zaman galeriye ekleyebilirsin.

## ⚠️ Kod içinde `<!-- NOT -->` / `<!--PLACEHOLDER-->` işaretli unsurlar
1. **Çalışma saatleri (S.S.S. 1)** – örnek metin; gerçek saatileri yazınca değiştir.
2. **Öğrenci yorumları (yorumlar bölümü)** – şablon; Google Maps yorumlarıyla değiştir (isimler baş harfle kısalt).
3. **Galeri "Kilitli Dolaplı Masa" kutusu** – tek kalan placeholder; gerçek fotoğraf ekleyince `<img>` etiketiyle değiştir (images/dolap.jpg).
4. **og:image** – yayına alınca tam URL kullan (https://domain/images/salon2.webp).
5. **Kazananlar / sayaç bölümü artık GERÇEK veriyle dolu** (afis-kazananlar.jpg'den; toplam 140). Öğrenci isimli hikâyeler eklemek istersen Instagram'daki listenin devamını temin et.

## Nasıl açılır / yayınlanır?
- Yerel önizleme: `index.html`'e çift tıkla.
- Yayın için: Netlify / GitHub Pages / Vercel'e klasörü sürükle-bırak yeterlidir (tek dosya + images/).
