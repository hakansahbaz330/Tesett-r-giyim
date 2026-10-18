# Ölçü, Kumaş ve Desen Analizi + Teklif Mailleri

Tarih: 18 Ekim 2026

## 0. Veri kalitesi uyarısı (önce bunu oku)

- **Trendyol, n11 ve Cimri sayfaları bu ortamdan açılmadı (HTTP 403).** Bu yüzden gerçek "çok satanlar" sıralaması ve yorum sayıları **elde yok**. Aşağıdaki analiz Mooncorn, QEF, Modanisa, Pazarium, Trend Tesettür ve Armine sayfalarından okunan verilerle sınırlı.
- Mooncorn ve QEF ürünlerinin çoğunda henüz yorum yok; yorum sayısıyla satış tahmini yapılamadı. QEF'te yalnızca bir ürün "ÇOK SATAN" etiketli.
- Modanisa filtre sayıları ürün adedidir (satış değil). "Standart" ve "200" gibi belirsiz değerler yorumlanırken dikkatli olun.
- Satış verisi için sizin yapmanız gereken 20 dakikalık manuel kontrol, bölüm 5'te.

---

## 1. Ölçü analizi

### Gözlenen ebatlar

| Kaynak | Ürün | Ebat (cm) | Kumaş |
|---|---|---|---|
| Mooncorn | Meil / Azure Desen Hebei İpek Şal | **70 × 190** | %70 pamuk, %30 ipek |
| Mooncorn | Penye Şal Kanyon | **75 × 185** | Penye |
| Mooncorn | Degrade Müslin Şal | **90 × 200** | %100 pamuk müslin |
| QEF | Floş Viskon Düz Şal | **70 × 200** | %50 floş, %50 viskon |
| Armine (n11 arama sonuçlarında) | Kumaş şal, lyocell monogram şal | **75 × 195** | Lyocell vb. |
| Arsel Moda (n11 arama sonuçlarında) | Soft pamuklu şal | 70 × 180 | Pamuk |
| Başka bir marka (n11 arama sonucu) | Şifon saten şal | 70 × 170 | Şifon saten |
| Trendyol kategori adı | "75 x 182 şal" | 75 × 182 | Karışık |

### Modanisa ebat filtresi (şal kategorisi, ürün adedi)
90×90 (256) · 70×190 (190) · 90×200 (179) · 100 (18) · 100×120 (13) · 75×200 (14) · 70×180 (11) · 70×200 (11) · "200" (724, belirsiz) · "Standart" (3.484, ebat belirtilmemiş)

### Çıkarım
- Senin bildiğin **70×180 ve 75×200 gerçek ama en yaygın değerler değil.** Açıkça ebat belirten ürünlerde **70×190 ve 90×200** (geniş müslin/pamuk) daha çok görünüyor; 70×200 ve 75×195 de var. Genel aralık: **eni 70–75, boyu 180–200 cm**.
- **Kare eşarp:** 90×90 baskın (256 ürün); 100×100 ipek eşarplarda; 100×120 ve 90×200 geniş stoller ayrı bir grup.
- **Karar önerisi:** Ana ebat **70×190**, premium/ipeksi modelde **75×200**, büyük/müslin modelde **90×200**. 70×180 ucuz ve eski sayılır; kısa kalır.
- **Teknik not [benim çıkarımım, teyit gerekli]:** Baskı kumaşları genelde 140–150 cm enindedir (7K'da 140/145/150). 70 cm enli iki şal yan yana 140–145 cm kumaşa sığar; 75 cm enli iki şal ancak 150 cm kumaşa sığar. Bu, 75 cm'lik ebatın fire ve maliyetini etkileyebilir. Baskıcıya bunu sorun.

---

## 2. Kumaş analizi

### Mooncorn şal kategorisi (2.423 ürün, kumaş filtresi adetleri)
Pamuk 1.234 · Polyester 1.138 · Viskon 662 · Yün 490 · Kaşmir 466 · İpek 262 · Modal 154 · Bambu 115

Alt kategoriler: Jakar 777 · Çift taraflı 400 · Neo Crash 205 · Hebei İpek 178.

### Diğer gözlemler
- **"Hebei ipek" = ipek değil, %70 pamuk %30 ipek karışım** (Mooncorn ürün sayfası). "İpek" filtresi 262 ürünün çoğu böyle karışım olabilir.
- **QEF düz şallar** (349,90–899,90 TL): Daily Krep, Daily Cotton (23 renk), Faye Müslin (18 renk), Bambu Penye (11 renk), Floş Viskon (899,90 TL, tek "ÇOK SATAN" etiketli).
- **Pazarium** (düşük segment): modal/liva kraş şal 182,70–207,90 TL.
- **Armine:** saf ipek twill 4.599,90 TL (sonbahar-kış 2026 listesi), jakarlı ipek.

### Orta-üst için kumaş önerisi
| Sıra | Kumaş | Neden |
|---|---|---|
| 1 | **Modal / modal-viskon** (baskı için ince, akışkan) | Kategoride az sayıda (154) → daha az kalabalık; baskı kalitesi iyi; Bursa Dijital modal baskı yapıyor (30/1, 60/1, 80/1) |
| 2 | **Pamuk müslin / pamuk-ipek karışım** | En yaygın kumaş (pamuk 1.234) ama kalite farkı yaratılabilir; doğal his |
| 3 | **Bambu / bambu-penye** | Rahat, düşük kayma; sadece 115 ürün |
| 4 | **Saf ipek twill eşarp (tek model)** | Marka algısı için "vitrin" ürünü; fiyat 1.200–1.900 TL aralığı hedeflenebilir (Armine 4.599 TL, 2.000+ TL) |

**Kaçının:** "Polyester" (1.138 ürün) ve belirsiz bileşimli ürünler – premium algıyla çelişir.

---

## 3. Desen analizi

### Dağılım (Mooncorn)
**Desenli 1.875 (%77) · Düz 548 (%23).** Desenli ürünler baskın, ama düz ürünler daha az rekabetli ve yüksek hacim alabilir.

### Desen dilleri (gözlenen ad ve etiketlerden)
- **Çiçek / botanik** (Çiçek Desenli Liva Kraş, Piramit Çiçek, Emerald, Lauris)
- **Etnik / motifli / arabesk** (Otantik motifli, Şerit detaylı etnik, Meil, Azure)
- **Geometrik / monogram** (Armine Naia monogram)
- **Puantiye** ve **degrade** (Puantiyeli Degrade Şal, Degrade Müslin)
- **Janjan** (parlak reflekte) ve **jakar** dokular
- **Leopar / hayvan derisi** (Piramit Leopar)
- Mooncorn'un isimlendirmesi: "[Desen adı] Desen [Kumaş] Şal – [Renk]" → bir desen 4–5 renkte. Aynı desen çok renk, standart.

### Renk eğilimi (Mooncorn renk filtresi, ürün adedi)
Kahverengi 316 · Yeşil 289 · Gri 226 · Mavi 219 · Haki 218 · Turuncu/Kiremit 195 · Pembe 194 · Lacivert 187 · Mor 185 · Siyah 165 · Vizon/Taş 161 · Bej 145 · Bordo 138 · Krem 92 · Kırmızı 23 · Beyaz 5.
QEF'in öne çıkardığı renk adları: Soft Kahve, Terracotta, Kum Beji, Çağla Yeşili, Vişne, Mürdüm Eriği, Lime.
**Çıkarım:** Toprak tonları (kahve, kiremit, haki, vizon, bej) ve soft yeşiller baskın. Kırmızı ve beyaz neredeyse yok → boşluk ya da talep düşüklüğü; test edilmeli.

### 6 modellik ilk koleksiyon önerisi (100 adet için)
| # | Model | Kumaş | Ebat | Desen | Renk (baskıda renk varyantı) | Adet |
|---|---|---|---|---|---|---|
| 1 | Botanik çiçek | Modal | 70×190 | Çiçek, sakin ton | 2 renk | 15 |
| 2 | Arabesk / etnik motif | Modal | 70×190 | Etnik motif, toprak tonları | 2 renk | 15 |
| 3 | Geometrik / monogram (marka) | Modal | 75×200 | Marka monogramı | 2 renk | 15 |
| 4 | Degrade / yumuşak geçiş | Pamuk müslin | 90×200 | Degrade | 2 renk | 15 |
| 5 | Düz premium (toptan, kendi etiketin) | Modal / bambu | 70×190 | Düz | 3 renk | 20 |
| 6 | Düz geniş müslin (toptan, kendi etiketin) | Pamuk müslin | 90×200 | Düz | 3 renk | 20 |

Bu tablo bir hipotez; fiyat teklifleri ve ebat/kumaş kısıtları gelince güncellenir.

---

## 4. Teklif mailleri

> Gönderirken [köşeli parantezleri] doldurun. Baskıcıya mailin yanı sıra WhatsApp'tan da kısa özet yazın (cevap oranı genelde daha yüksek).

### 4.1 Baskı atölyesine (Bursa Dijital Tekstil; aynı metin 7K Dijital'e uyarlanabilir)

**Konu:** Dijital baskılı şal/eşarp – fason fiyat teklifi (100 adet, 4 desen)

Merhaba,

[Marka adı / çalışma adı] adıyla yeni bir eşarp-şal markası kuruyorum. İlk koleksiyonumuz için kendi tasarladığımız desenlerin dijital baskısı ve kenar işçiliği konusunda fiyat teklifinizi rica ederim. Aşağıda ihtiyacımızı yazdım; eksik olan veya sizde farklı çalışan bir nokta varsa belirtirseniz toparlarım.

**1) Sipariş yapısı**
- Toplam 100 adet; **4 farklı desen × 15 adet** (toplam 60 adet baskı) ve ayrıca, mümkünse düz renk / kendi etiketimle **40 adet** düz boyalı ürün (düz için ayrı fiyat veriyorsanız yazın)
- Seçenek olarak 60 / 100 / 200 adet için ayrı birim fiyat görmek istiyorum.

**2) Ürün ebatları** (her biri için ayrı fiyat lütfen)
- A) **70 × 190 cm** şal (ana ürün)
- B) **75 × 200 cm** şal
- C) **90 × 200 cm** şal (müslin/pamuk için)
- D) İsteğe bağlı: **100 × 100 cm** kare eşarp (modal)

Sorularım: Dikdörtgen şal ebatlarını (A, B, C) baskı ve kesim-dikim olarak yapıyor musunuz, yoksa yalnızca kare eşarp mı basıyorsunuz? Kumaş eniniz nedir (140/145/150 cm)? 70 cm enli iki şalı yan yana basabiliyor musunuz, 75 cm için fire ne olur?

**3) Kumaş**
- Birinci tercih: **modal** (ince, akışkan; sitenizde 30/1, 60/1, 80/1 modal yazıyor – şal için hangisini önerirsiniz?)
- İkinci tercih: **pamuk müslin** (90×200 için), üçüncü: **pamuk-ipek karışım** veya **viskon**
- Lütfen her kumaş için bileşim (%), gramaj (gr/m²), kumaş eni ve kumaş fiyat farkını yazın.
- Kumaş bileşimi etiketimde yazılacağı için, bileşim yazılı teyit istiyorum.

**4) Kenar işçiliği** (fiyat farkıyla)
- Şal için: lazer kesim + overlok / rulo / saçak / el rulosu seçenekleriniz ve her birinin birim fiyat farkı.
- Kare eşarp için: İtalyan makine rulosu ve el rulosu fiyat farkı.

**5) Baskı ve renk**
- Arka yüze renk geçişi (siteniz %60–80 diyor) – "extra mode" ek maliyeti ve görünüm farkı
- Renk eşleştirme: ekranda gördüğüm renk ile baskı rengi için hangi süreci öneriyorsunuz (renk kartı, ön numune)?
- Dosya formatı ve çözünürlük şartı (RGB, 200 dpi+ gerçek ebatta?) ve tasarımı sizin şablonunuza nasıl yerleştirmeliyim (desen tekrarı, kenar payı)?

**6) Numune**
- Ücretli numune: kaç adet (1–4), birim ücret, süre (6–10 iş günü?) ve numune ücretinin sipariş verirsem düşülüp düşülmediği.
- Tek bir desenin 2 kumaşta (modal / müslin) numunesini yan yana alabilir miyim?

**7) Etiket ve paket**
- Kendi bileşim / bakım etiketimi dikebilir misiniz (etiketi ben getiririm veya siz temin edersiniz?) ve dikim ücreti
- Ütülü, katlı, poşetli teslim mümkün mü; adet başı ücreti

**8) Süre ve ödeme**
- Numune ve ana üretim süresi (kumaş stokta ise / değilse)
- Ödeme şekli (sitenizde tam ön ödeme yazıyor): kısmi ön ödeme (%50 / %50) mümkün mü?
- Tekrar sipariş ve parti-arası renk tutarlılığı garantiniz var mı? Ayıplı ürün durumunda yenileme politikanız?

**9) Fatura ve vergi**
- Fatura türü ve KDV oranı (fiyatlar KDV hariç mi?). Faturayı henüz firma adına değil, [bireysel/şahıs] adına isteyebilirim; bunun için ne gerekiyor? (Bu konuyu ayrıca mali müşavirimle netleştiriyorum.)
- Desenlerimin gizliliği: tasarım dosyalarımın başkasına basılmayacağı konusunda yazılı güvence verir misiniz?

**10) Teslim**
- Nakliye (alıcı ödemeli / gönderici ödemeli), adres [İl/İlçe], kargo seçenekleri.

Mümkünse **yazılı bir teklif (PDF/mail)** ve adet kademeli birim fiyat tablosu istiyorum. Fabrikanızı ziyaret etmek isterim; uygun gün/saatleri paylaşırsanız randevu alırım.

Teşekkürler, iyi çalışmalar.  
[Ad Soyad] · [Telefon/WhatsApp] · [E-posta] · [Şehir]

---

### 4.2 Toptancıya / özel etiketli üreticiye (Şal Fabrikası, Moda Kaşmir B2B, Carell, Alıcıoğlu, Mooncorn Toptan)

**Konu:** Özel etiketli (private label) şal/eşarp toptan fiyat teklifi – 100 adet

Merhaba,

[Marka adı] adında yeni bir eşarp-şal markası kuruyorum. İlk siparişim için **özel etiketli (kendi etiket ve ambalajımla)** ürün alıyorum ve fiyat teklifinizi rica ediyorum. Bayi/üyelik başvurusunu da yapabilirim; hangi yoldan ilerleyelim?

**1) Sipariş**
- İlk sipariş: toplam **100 adet**, **5–6 model**, her modelden **15–20 adet**; model başına en fazla **2–3 renk**. Karışık model/renk mümkün mü?
- 50 / 100 / 250 / 500 adet için birim fiyat (KDV hariç) tablosu.
- Minimum sipariş adedi veya tutarı nedir?

**2) Ürün**
- Kumaşlar: **modal / modal-viskon**, **bambu**, **pamuk müslin**, **floş viskon**, **pamuk-ipek karışım** ve (tek model) **saf ipek twill eşarp**
- Ebatlar: **70×190**, **75×200**, **90×200** şal ve **100×100** eşarp. Hangilerini stokta tutuyorsunuz? Ebatlar tolerans dahil kaç cm?
- Her ürün için bileşim (%), gramaj, ebat, kenar işlemi (overlok / rulo / saçak) ve yıkama talimatı.
- Düz renkler için renk kartelanız / renk sayısı; **toprak tonları** (kahve, kiremit, haki, vizon, bej, soft yeşil) var mı?

**3) Özel etiket**
- Logo / bileşim etiketi dikimi: minimum adet, birim ücret, süre
- Kendi ambalajım / poşetim ile paketleme mümkün mü?
- İsterseniz **size özel (ürün bazında münhasır) desen/renk** çalışması yapabilir miyiz? Münhasırlık için minimum adet ve ücret nedir?

**4) Numune**
- Seçeceğim 4–6 ürün için numune ücreti, süre; sipariş verirsem numune bedeli düşülüyor mu?

**5) Süre, ödeme, kargo**
- Stoktan teslim süresi, özel üretim/özel etiket süresi
- Ödeme şekilleri (kart/havale), kargo koşulları ve ücret
- Tekrar sipariş ve renk/parti tutarlılığı
- Ayıplı ürün ve iade/değişim politikanız

**6) Fatura**
- Faturalı satış; KDV oranı; **bireysel (T.C. kimlik no) adına** fatura kesebiliyor musunuz? (Bunu ayrıca mali müşavirle netleştiriyorum.)

**7) Referans**
- Aynı şekilde çalıştığınız 1–2 marka referansı paylaşabilir misiniz?

Fiyat listesi ve koşulları yazılı olarak iletirseniz çok sevinirim.

Teşekkürler,  
[Ad Soyad] · [Telefon/WhatsApp] · [E-posta] · [Şehir]

---

### 4.3 Kısa WhatsApp mesajı (maile ek olarak)

> Merhaba, yeni bir eşarp/şal markası kuruyorum. Kendi desenlerimle 100 adetlik ilk üretim için fiyat almak istiyorum (4 desen × 15 adet, modal ve pamuk müslin, 70×190 / 75×200 / 90×200 şal ebatı). Detaylı talebi size mail olarak gönderdim. Fiyat, numune ve süre bilgisi verebilir misiniz? Teşekkürler.

---

## 5. Gerçek "çok satan" verisini 20 dakikada toplama listesi

Trendyol/Hepsiburada/n11 sayfalarını siz açıp aşağıyı doldurun (telefonda "Çok Satanlar" sıralaması):

1. Kategori: **Eşarp & Şal → Şal**, sıralama: **Çok satanlar**.
2. İlk 30 üründe şunları tabloya girin: marka, fiyat, **ebat**, **kumaş**, **desen tipi**, **renk**, **yorum sayısı**, **puan**, satıcı sayısı.
3. "Kumaş: modal/bambu/müslin" ve "fiyat 450–1.000 TL" filtresiyle tekrarlayın.
4. 1–2 yıldız yorumları okuyun: sık şikâyet (kayma, çekme, renk solması, kalite) → ürün vaadiniz.
5. Aynı çalışmayı **Modanisa** ve **Hepsiburada** için tekrarlayın; ortak çıkan özellikler talebin gerçek göstergesi.

Tablo sütunları: Marka | Ürün | Fiyat | Ebat | Kumaş | Desen | Renk | Yorum | Puan | Not

İsterseniz bu 30 satırı bana yapıştırın, sayısal analizini ben yaparım.

---

## Kaynaklar
- [Mooncorn şal](https://mooncorn.com.tr/collections/sal) · [Hebei ipek şal ürün sayfası](https://mooncorn.com.tr/meil-desen-hebei-ipek-sal-siyah) · [Penye şal](https://mooncorn.com.tr/penye-sal-kanyon) · [Degrade müslin](https://mooncorn.com.tr/degrade-muslin-sal-bej)
- [QEF şal](https://www.qefofficial.com/collections/sal) · [Floş viskon şal](https://www.qefofficial.com/products/flos-viskon-duz-sal-lime)
- [Modanisa şal](https://www.modanisa.com/en/shawl.htm) · [Pazarium şal](https://www.pazarium.com.tr/sal) · [Trend Tesettür](https://www.trendtesettur.com/tr/sal-esarp/)
- [Armine sonbahar-kış eşarp](https://www.armine.com/sonbahar-kis-esarp-koleksiyonu)
- [Bursa Dijital Tekstil – modal eşarp baskı](https://www.bursadijitaltekstil.com/modal-esarp-dijital-baski/) · [eşarp baskısı](https://www.bursadijitaltekstil.com/esarp-baskisi/) · [7K Dijital eşarp baskı](https://www.7kdijitalipekbaski.com/dijital-esarp-baski/)
