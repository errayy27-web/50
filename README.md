# SS OIL Görsel Merkezi

Bu depo, eski içeriği kaldırılarak ürün görsel yönetim web uygulamasına dönüştürüldü.

## Kullanım
GitHub Pages üzerinden `index.html` açılır. Supabase Project URL, **publishable/anon** key ve Supabase Auth hesabı ile giriş yapılır. Şifre tarayıcıda saklanmaz. Kullanıcı 948 ürünün resimlerini taratabilir, eksikleri filtreleyebilir, manuel fotoğraf yükleyebilir ve görselleri yenileyebilir.

## Supabase
- Proje: `rxpsezjtjqfksdxcxmuw`
- Ürünler: `public.ssoil_snapshots` (`kind=products`)
- Görseller: `public.ssoil_product_images`
- Storage: `product-images`
- Edge Functions: `match-product-images`, `upload-product-image`

Görsel araması Open Food Facts ile barkod eşleştirir; başka kaynaklar için manuel web araması vardır. Fonksiyonlar sadece `eray@ssoil.ba` Supabase Auth hesabını yetkilendirir.

**Not:** GitHub Pages dağıtımı ayrıca etkinleştirilmelidir. Uygulama kurulmuş olması 948 görselin yüklenmiş olduğu anlamına gelmez.
