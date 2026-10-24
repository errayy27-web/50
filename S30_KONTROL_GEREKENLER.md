# S30 kaynak kod taslağı — henüz derlenmedi/test edilmedi

Bu ZIP **kuruluma hazır veya doğrulanmış sürüm değildir**. Flutter SDK bulunmadığından analiz/derleme ve gerçek cihaz testi yapılmadı.

Kaynakta hazırlananlar:
- Dört tema seçimi (siyah-altın, lacivert-altın, beyaz-kırmızı üst başlıklı, beyaz-siyah).
- Ana sayfada 10 adet 2 sütunlu kısayol, bilgi kartının kaldırılması.
- Tedarikçi düzenleme/silme menüsü.
- Siparişe Ekle miktar ve tedarikçi seçimi penceresi.
- Ürün detayında Eksik/Fazla yan yana, fotoğraf işlemleri tek menüde, kritik stok altta.
- Kasa tarihinin bugün izlenirken gece değişmesi.
- Ayarlar senkronizasyon açıklamalarının kaldırılması.

**Tamamlanmamış / doğrulanmamış işler**:
- Telefon -> Supabase tedarikçi/eksik-fazla gönderim hatasının kök nedenini bulma ve canlı test.
- Kasa nakit market/yakıt ayrımının gerçek ödeme verileriyle hesaplanması.
- Geçmiş gün Yakıt/Market verilerinin PC tarafında kalıcı arşivlenmesi.
- Kasa bölümündeki satırların kesin istenen yerleşimi.
- Tedarikçi ekleme sonrası aynı sipariş penceresine otomatik geri dönüş.
- Flutter analyzer, derleme, otomatik ve cihaz testleri.

Ana SQL Server'a hiçbir yazma işlemi eklenmemiştir.
