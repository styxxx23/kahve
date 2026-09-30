# ☕ Kahve Buluşması — sana özel cevaplar

Bu sürüm Firebase/Supabase kullanmaz.

## Sadece 1 şey yapman gerekiyor

`script.js` dosyasını aç ve en üstteki:

```js
const OWNER_EMAIL = "SENIN_EPOSTA_ADRESIN@example.com";
```

kısmını kendi e-posta adresinle değiştir.

Örneğin:

```js
const OWNER_EMAIL = "ornek@gmail.com";
```

Sonra 3 dosyayı GitHub'a yükle:

- index.html
- style.css
- script.js

GitHub → **Settings → Pages → Deploy from a branch → main → / (root)**.

### Nasıl çalışıyor?

Arkadaşın:
1. Siteye girer.
2. Evet'e basar.
3. İsmini ve saatini girer.
4. "Cevabımı gönder"e basar.
5. Telefonunun e-posta uygulaması açılır ve cevap sana gönderilecek şekilde hazırlanır.

**Önemli:** Bu yöntemde cevapları otomatik olarak sessizce göndermek mümkün değildir. Tarayıcı güvenliği nedeniyle kullanıcı e-posta uygulamasını açıp gönderme işlemini onaylar.

Arkadaşların birbirlerinin cevaplarını görmez.
