# S31 tarih ekranı düzeltmesi (kaynak kod)

- Tarih seçilince seçilen günün `/kasa?date=YYYY-MM-DD` ve `/daily-sales` verileri yeniden okunur.
- Önceki günün Kasa değerleri beklerken ekranda gösterilmez.
- Geciken önceki tarih yanıtları yeni seçilen tarihin Kasa tutarlarını ezemez.
- Gün değişiminde Kasa geçici olarak temizlenir.
- Ana SQL Server sadece SELECT; Kasa/dopuna için PC yetkilidir.

**Önemli sınır:** Bu ZIP yalnızca telefon kaynak kodu tarih yenilemesini düzeltir. PC sunucusunun `/kasa?date=` sorgusunun tarihsel hesaplaması ve `/daily-sales` arşivinin tüm geçmiş günleri içerdiği henüz doğrulanmamıştır. Bu ZIP geçmiş SQL verilerini tek seferlik aktarmıyor; bunun için kullanıcı henüz SQL tablo/tarih sütunu bilgilerini vermedi. Supabase `kasa` snapshot'ı tek güne ait olabileceğinden tarihsel sorgu için güvenilir değildir. Flutter SDK ile derleme yapılmamıştır.
