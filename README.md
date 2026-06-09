# AOB Apps Destek Sitesi

App Store Support URL, Privacy Policy URL, TestFlight destek sayfası ve
kullanıcı veri silme talepleri için hazırlanmış statik destek sitesidir.
Framework veya derleme adımı gerektirmez.

## Dosyalar

- `index.html`: AOB Apps destek merkezi ve Minik Adımlar destek bölümü
- `privacy.html`: App Store uyumlu gizlilik politikası
- `contact.html`: İletişim ve veri silme talepleri sayfası
- `privacy/index.html`: GitHub Pages üzerinde `/privacy` yönlendirmesi
- `contact/index.html`: GitHub Pages üzerinde `/contact` yönlendirmesi
- `styles.css`: Ortak responsive tasarım sistemi

## Lokal Olarak Açma

```bash
cd support-site
python3 -m http.server 8080
```

Tarayıcı bağlantıları:

- Destek: `http://localhost:8080/`
- Gizlilik: `http://localhost:8080/privacy.html`
- İletişim: `http://localhost:8080/contact.html`

## GitHub Pages Yayını

Kullanıcı sitesi olarak `https://aobapps.github.io/` adresini kullanmak için
GitHub'da `aobapps.github.io` isimli herkese açık bir repo oluşturun.

1. `support-site` klasörünün içeriğini reponun kök dizinine yükleyin.
2. Repo içinde **Settings → Pages** bölümünü açın.
3. Kaynak olarak **Deploy from a branch** seçin.
4. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydedin.
5. Yayın tamamlandıktan sonra tüm bağlantıları gizli sekmede kontrol edin.

## App Store Connect URL'leri

GitHub Pages kullanıcı sitesi yayınlandığında:

- **Support URL:** `https://aobapps.github.io/`
- **Privacy Policy URL:** `https://aobapps.github.io/privacy`
- **Contact URL:** `https://aobapps.github.io/contact`

Farklı bir GitHub kullanıcı adı veya proje reposu kullanılırsa URL'leri kendi
yayın adresinize göre güncelleyin.

## İletişim ve Veri Silme

Tüm destek, iletişim ve veri silme talepleri için:

```text
osmanalibasak@gmail.com
```

App Store Connect'e URL eklemeden önce bağlantıların herkese açık olarak
açılabildiğini ve e-posta bağlantılarının doğru çalıştığını kontrol edin.
