# Bir Varmış — Türk Masalları Derlemesi

**Hazırlayan:** Dastan Abdullayev  
**Öğrenci numarası:** 86230082  
**Ders:** Programlamaya Giriş, 2026–2027 Güz  
**Öğretim üyesi:** Meral Şentürk

## Proje

[GitHub deposu](https://github.com/dastanabdullayew0-spec/bir-varmis-masallar)

Sekiz Türk masalının kısa yeniden anlatımlarını bir araya getiren okuma sayfası. Masalların açılıp kapanması, başlığa göre arama, sonuç sayısı ve 16–24 piksel aralığında yazı boyutu ayarı bulunur. Arka plan çok açık yeşildir.

## Nasıl açılır?

`masal-derlemesi.html` dosyasını indirip tarayıcıda aç. Kurulum veya internet bağlantısı gerekmez. Kaynak kitabın bağlantısını açmak internet gerektirir. GitHub dosya görünümü siteyi çalıştırmaz; HTML dosyasını indirip açmak yeterlidir.

## Dosyalar

- `masal-derlemesi.html`: İçsel CSS ve JavaScript kullanan tek site dosyası.
- `86230082_DastanAbdullayev_vize.pdf`: Raporun okunabilir PDF sürümü.
- `main.tex`: Düzenlenebilir LaTeX kaynağı.

## Teknolojiler

HTML, içsel CSS ve içsel JavaScript. Harici tema, kütüphane, font veya veri dosyası kullanılmaz. `details` ile aç/kapat HTML'nin yerleşik özelliğidir. Arama ve okuma boyutu JavaScript ile yönetilir. 600 piksel ve altı ekranlar için ayrı yerleşim kuralları bulunur.

## Kaynak ve alınan destek

Kúnos, Ignácz (der.); Bain, R. Nisbet (çev.). *Turkish Fairy Tales and Folk Tales*. London: A. H. Bullen, 1901. [Project Gutenberg eBook 64807](https://www.gutenberg.org/ebooks/64807). Kitabın Türk masalları bölümündeki sekiz anlatı kullanıldı. Metinler tam çeviri değil, kısa yeniden anlatımlardır.

Kodun hazırlanması, arama ve okuma ayarı, kısa masal uyarlamaları ve raporun düzenlenmesinde ChatGPT desteği kullanıldı. Çok açık yeşil arka plan öğrenci isteğiyle seçildi. Hazır web sitesi teması veya yapay zekâyla üretilmiş görsel kullanılmadı.

## Testler

Arama, Türkçe büyük/küçük harf dönüşümü, sıfır sonuç, aramayı temizleme ve boyut sınırları kod düzeyinde kontrol edildi. Gerçek bilgisayar, telefon ve çevrimdışı açılış testleri yapılmadı.

## Sunum videosu

Durum: Henüz yapılmadı.  
Video bağlantısı: —

## Rapor kaynağı

LaTeX kaynağının derleme kontrolü geçti. Overleaf'te **XeLaTeX** seçilmelidir. Kaynak, verilen PDF şablonundaki bölüm sırası temel alınarak yeniden oluşturuldu; hocanın özgün `.tex` dosyası değildir. Bu klasördeki PDF aynı içeriğin ayrıca üretilmiş okunabilir önizlemesidir; LaTeX derleyicisinden dışa aktarılmış dosya değildir. Son LaTeX çıktısı dışa aktarılırken sayfalar kontrol edilmelidir.

## Teslim

MEBİS teslimi henüz yapılmadı. Depoda HTML, rapor PDF'i, LaTeX kaynakları ve README bulunmalıdır. MEBİS'e yalnız rapor PDF'i yüklenir. Kesin teslim tarihi güncel ders duyurusundan doğrulanmalıdır.
