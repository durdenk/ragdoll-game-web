# Ragdoll Gladiator — Web Sayfası

Oyunun İngilizce tanıtım, gizlilik ve kullanım koşulları sayfaları. Framework,
paket kurulumu, derleme veya çalışma anında API çağrısı gerektirmez.

- Public web repo: [durdenk/ragdoll-game-web](https://github.com/durdenk/ragdoll-game-web)
- Hedef site: https://durdenk.github.io/ragdoll-game-web/
- Gizlilik: https://durdenk.github.io/ragdoll-game-web/privacy-policy.html
- Kullanım koşulları: https://durdenk.github.io/ragdoll-game-web/terms-of-use.html
- Veri silme: https://durdenk.github.io/ragdoll-game-web/privacy-policy.html#data-deletion
- Android paket kimliği: `com.cukkacreatives.ragdoll.gladiator`
- İletişim: cukkacreatives@gmail.com

## Yerel önizleme

Proje kökünden:

```sh
python -m http.server 8765 --bind 127.0.0.1 --directory docs/web
```

http://127.0.0.1:8765/ adresini aç. Görsel kontrolü 1280×720 ve 1600×720
yatay boyutlarda yap. Önizleme bitince sunucuyu Ctrl+C ile kapat.

## GitHub Pages yayını

Bu klasördeki aşağıdaki dosyaları **public web reposunun köküne** kopyala;
özel oyun reposunu veya proje dosyalarını yayınlama:

- `index.html`
- `privacy-policy.html`
- `terms-of-use.html`
- `styles.css`
- `crest.svg`
- `crossed-swords.png`
- `app-ads.txt`
- `.nojekyll`

GitHub Pages kaynağı `main` dalı ve `/ (root)` olmalı. Göreli bağlantılar
`/ragdoll-game-web/` alt yolunda da çalışır. `crossed-swords.png`, oyunun
`assets/ui/icons/fight.png` görselinin kopyasıdır. Eski şablonun logosu kullanılmaz.

Yayın sonrasında yukarıdaki hedef adresleri doğrula. Google Play Console'a
oyunun gizlilik ve kullanım koşulları adreslerini gir. Bu klasörün düzenlenmesi
tek başına public repoyu veya canlı siteyi güncellemez.

## Reklam ve veri açıklamaları

`app-ads.txt` içindeki yayıncı kimliği `docs/feature/admob.md` ile eşleşir.
AdMob, geliştirici web sitesinin ana makine kökünde `/app-ads.txt` arar;
GitHub Pages proje alt yolundaki dosya tek başına yeterli değildir.
`durdenk.github.io` geliştirici sitesi olarak kullanılacaksa aynı satırın
https://durdenk.github.io/app-ads.txt adresinde sunulması gerekir. Alternatif
olarak kökünde bu dosya bulunan bir özel alan adı kullanılabilir.

Gizlilik sayfası Android sürümlerinin kullanabileceği AdMob, GameAnalytics,
Google Play Billing ve değerlendirme akışlarını açıklar. Eklentilerin projede
bulunması, her sürümde bütün veri akışlarının etkin olduğu anlamına gelmez.
Yayınlanacak Android sürümünün gerçek SDK ayarları, izin/onay akışı ve Google
Play Data safety beyanı aynı veri uygulamalarını yansıtmalı. Eski oyunun bonus
gold satın alım vaadi bu oyuna taşınmadı.

Resmi başvuru kaynakları:

- [Google Mobile Ads veri açıklaması](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [AdMob app-ads.txt kurulumu](https://support.google.com/admob/answer/9363762)
- [GameAnalytics gizlilik bildirimi](https://www.gameanalytics.com/trust/privacy-notice)
- [GameAnalytics saklama ve silme politikası](https://www.gameanalytics.com/trust/data-retention-and-deletion-policy)
- [Google Play In-App Reviews](https://developer.android.com/guide/playcore/in-app-review#data-safety)
- [GitHub Pages ve veri toplama](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection)
