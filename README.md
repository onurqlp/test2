# AYDA A1 Akademi — Final GitHub Pages

AYDA Dil Akademisi kendi hızında A1 Almanca öğrenme alanı. **24 Menschen A1 ünitesi**, her ünitede **3 mevcut ders videosu/materyali**, tüm orijinal konu anlatımları, Türkçe ipuçları, Almanca örnekler, Arbeitsbuch notları, **24 özgün alıştırma/ünite (576 soru)** ve ilerleme kaydı korunur.

## Öğrenci deneyimi

1. Öğrenci ana sayfadan **Üniteler**e geçer, ilgili ünitesini açar.
2. **Ünite ders videosu**, **Kısa konu tekrarı** ve **Konuşma kalıpları** üst sekmeleri ile içerik sayfa içinde oynatılır/gösterilir. **⛶ Büyüt** ekranı örter, **✕ Kapat** dersi geri getirir; Escape tuşu çalışır.
3. Öğrenci ayrıntılı Türkçe konu anlatımlarını, örnek cümleleri ve kitap notlarını okur.
4. **24 Alıştırmaya Başla** butonuyla çoktan seçmeli, eşleştirme, kelime sıralama ve diğer görevleri çözer. Yanlışlarda açıklamalar gösterilir.
5. Ders kayıtları, ek kaynaklar, mini sınav pratiği yalnızca **Ek kaynaklar** bölümünde ikincil olarak bulunur.

## GitHub Pages kurulumu

1. Bu arşivi çıkar. İçindeki `index.html`, `assets/`, `og.png` ve `README.md` dosyalarını **GitHub deponun ana dizinine** yükle.
2. GitHub deposunun `Settings > Pages` bölümünde `main` branch ve `/(root)` seç.
3. Özel alan adı kullanıyorsan GitHub Pages Custom domain yapılandırmasını koru.
4. Yayına alındıktan sonra tarayıcı önbelleğini yenile; bağlantıları bir telefon üzerinden de kontrol et.

## Önemli teknik notlar

- Mevcut **sınıf şifresi kontrolü** aynen korunur: `https://onurqlp.github.io/ayda-pass/access-control.js` (başka hesaba taşınmadı).
- Öğrenci ilerleme anahtarı korunur: `ayda-a1-progress-v3`, sadece aynı tarayıcıda yerel olarak saklanır.
- Kendi hızında çalışma (asenkron/offline ders) platformudur. **Bu, internetsiz video izleme anlamına gelmez.** Google Drive/YouTube videoları ve harici şifre kontrolü için internet gerekir.
- Drive dosyaları `.../file/d/DOSYA_ID/preview` üzerinden iframe'de açılır. Erişim izni veya barındırıcı kısıtı nedeniyle oynatılamayan içerik için **Açılmazsa kaynağı aç** yedek bağlantısı sağlanır.
- Gerçek AYDA logo dosyası kullanıcı tarafından sağlanan AYDA master tema metninden alınmıştır.
- Alıştırma soruları ve cevapları mevcut JS veri kümesinden değiştirilmeden tutulmuştur.
- `assets/base.css` orijinal; `assets/study.css` eğitim amaçlı yeni mobil tema; `assets/app-ayda-a1.js` eğitim arayüzü.
