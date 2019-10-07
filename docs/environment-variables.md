# Environment Variables (.env)
Yükleme ve yayın sayfalarında .env'den bahsedip durduk. Bu dosyalar, servisin ve front-end paketlerindeki detayların grubunuza özel olmasını sağlayacak değerleri tutuyor.

## Back-end .env
```env
PORT=                           // Servisin çalışacağı port.
HOST_URL=                       // Servisin çalışacağı url. (https://example.com)
NODE_ENV=                       // Servisin çalışacağı enviroment.
SITE_NAME=                      // Sitenin ismi. (Örn: PuzzleSubs)
SECRET_OR_KEY=                  // Passportjs'in kullanacağı secret key.
DISCORD_ANIME_WH=               // Discord Anime kanalı Webhook
DISCORD_EPISODE_WH=             // Discord Bölüm kanalı Webhook
DISCORD_MANGA_WH=               // Discord Manga kanalı Webhook
DB_HOST=                        // MariaDB Host
DB_USER=                        // MariaDB Kullanıcı ismi
DB_NAME=                        // MariaDB Database ismi
DB_PASSWORD=                    // MariaDB Kullanıcı şifre
DB_CONNECTION_LIMIT=100         // MariaDB bağlantı limit sayısı
CF_ZONEID=                      // CloudFlare cache temizleme API yolu, ZONEID
CF_EMAIL=                       // CloudFlare cache temizleme API yolu, EMAIL    
CF_APIKEY=                      // CloudFlare cache temizleme API yolu, APIKEY
SMTP_USERNAME=                  // SMTP Mail için kullanıcı adı
SMTP_PASSWORD=                  // SMTP Mail için şifre
SMTP_HOST=                      // SMTP Mail için host
```

## Front-end Client .env
```env
REACT_APP_SITENAME=""           // Sitenin ismi. (Example)
REACT_APP_SITEURL=""            // Sitenin isim alanı. (https://example.com)

REACT_APP_DISQUS_SHORTNAME=""   // Disqus kısa ismini sağlarsanız anime, manga ve bölüm sayfalarında yorum kısmı gösterir.
REACT_APP_DEV_API_URL=""        // Dev ortamında istekleri yapmak için kullanacağı alan adı. (http://localhost:5000 gibi)
REACT_APP_GA_USER_ID=""         // Google Analytics kullanıcı id'niz.
REACT_APP_FACEBOOK_LINK=""      // Link sağlarsanız footer'da tıklanabilir bir Facebook logosu gösterir.
REACT_APP_DISCORD_LINK=""       // Link sağlarsanız footer'da tıklanabilir bir Discord logosu gösterir.

REACT_APP_SSS_PAGE_TEXT=""      // Text sağlarsanız SSS sayfası oluşturur, menüde gösterir.
```

## Front-end Admin .env
```env
REACT_APP_SITEURL=""            // Sitenin isim alanı. (https://example.com)
REACT_APP_DEV_API_URL=""        // Dev ortamında istekleri yapmak için kullanacağı alan adı. (http://localhost:5000 gibi)
``` 