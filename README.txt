DECOPOL PREMIUM — sayt (UZ / RU), v8

TILLAR (v8 dan boshlab URL orqali):
  O'zbekcha:  https://premium.decopoluzbekistan.uz/franshiza.html
  Ruscha:     https://premium.decopoluzbekistan.uz/ru/franshiza.html
  UZ / RU tugmasi o'sha sahifaning boshqa tildagi manziliga o'tadi (?id=... ham saqlanadi).
  ru/ papkasida faqat kichik HTML fayllar bor — rasm, CSS va JS ildizdagi umumiy fayllardan olinadi.
  Eski ?lang=ru havolalari avtomatik /ru/ ga o'tadi.

HOSTINGGA JOYLASH (premium.decopoluzbekistan.uz papkasi):
  1) Eski style-v7.css va app-v7.js ni o'chiring.
  2) Zip'ni yuklab, Extract qiling (ru/ papkasi o'zi yaratiladi).
  3) .well-known, .htaccess, .user.ini, php.ini, index(old).html ga tegmang.

RASMLAR: quyidagi nomlar bilan shu papkalarga qo'ying — sayt o'zi topadi.
(Rasm bo'lmasa, o'rnida rangli fon ko'rinadi.)

  img/hero-home.jpg            bosh sahifa tepa rasmi
  img/about-hero.jpg           "Biz haqimizda" tepa rasmi
  img/franshiza-hero.jpg       "Franshiza" tepa rasmi
  img/franshiza/farg-ona.jpg   Farg'ona kartochkasi
  img/franshiza/namangan.jpg   Namangan kartochkasi
  img/adv1.png ... adv6.png, adv6.png   "Afzalliklar" kartochkalari rasmlari

  img/cases/sariqbola.jpg            (TAYYOR)
  img/cases/besh-bola-buildings.jpg  (TAYYOR)
  img/cases/giotto.jpg               (TAYYOR)
  img/cases/innovative-centre.jpg
  img/cases/yong-hin-ceramics.jpg
  img/cases/yuksalish-group.jpg
  img/cases/uzbekistan-airways.jpg
  img/cases/manhattan.jpg
  img/cases/fergana-city-uylari.jpg
  img/cases/zinalar.jpg
  img/cases/nbu-bank-toshkent.jpg

  img/showroom/salotto-tv.jpg, angolo-caffe.jpg, ingresso.jpg, entrada.jpg,
  escalera.jpg, maestra.jpg, lucevista.jpg, zonaviva.jpg, clinica.jpg, sapore.jpg,
  la-tavola.jpg, futuro-scuola.jpg, royale.jpg, elevare.jpg, celeste.jpg,
  ritorante.jpg, la-reception.jpg, rialzo.jpg, panorama.jpg

  img/collections/stone.jpg, wood.jpg, concrete.jpg, fabric.jpg, velvet.jpg   Kolleksiyalar sahifasi

  img/brands/*.jpg            Brend logotiplari (15 ta, TAYYOR). Asl PNG/SVG bo'lsa, shu nomlar bilan almashtiring

  video/showroom.mp4           Showroom sahifasidagi video

SAHIFALAR (hammasi shu saytning ichida ochiladi, decopol.net'ga o'tmaydi):
  index, about, franshiza, cases, showroom, panel (Kolleksiyalar), designers (Dizaynerlarga),
  contact (Bog'lanish)
  case.html?id=...      har bir loyiha  (11 ta)
  zone.html?id=...      har bir showroom zonasi  (19 ta)
  franchise.html?id=... Farg'ona va Namangan

Til: tepada UZ / RU tugmasi. Ruscha sahifalar /ru/ ichida.

----- RASMLAR HOLATI (4-oktyabr) -----
Tayyor:  16 ta showroom zonasi, 8 ta loyiha, 15 ta brend logotipi, bosh sahifa loyihalari.
Yetishmaydi (rangli fonda turadi):
  img/showroom/(tayyor)
  img/cases/yong-hin-ceramics.jpg, fergana-city-uylari.jpg, nbu-bank-toshkent.jpg
  img/collections/*.jpg, img/franshiza/*.jpg

----- VIDEOLAR (zona va loyiha batafsil sahifalari) -----
app-v8.js ichida ZVIDEO va CVIDEO degan ikkita ro'yxat bor (hozircha bo'sh).
Video manzilini yozsangiz, o'sha zona/loyiha sahifasida "Video" bo'limi o'zi paydo bo'ladi. Misol:
  var ZVIDEO = { 'lucevista': 'https://.../video.mp4' };
Zona nomlari: salotto-tv, angolo-caffe, ingresso, entrada, escalera, maestra, lucevista, zonaviva,
clinica, sapore, la-tavola, futuro-scuola, royale, elevare, celeste, ritorante, la-reception, rialzo, panorama

v6: Kolleksiyalar, Dizaynerlarga, kolleksiya (collection.html), mahsulot (product.html) va zona sahifalari asl saytdagidek.
Yangi fayllar: collection.html, product.html.
v8: ruscha sahifalar /ru/ manzilida (ru/ papkasi), UZ/RU tugmasi URL'ni almashtiradi.
