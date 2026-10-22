# Сайт «Чистовье Кыргызстан»

## Что заменить перед запуском
1. **Instagram**: найдите в `index.html` все `INSTAGRAM_NICK` (5 мест) и замените на ник вашей страницы.
2. **Фото товаров** лежат в папке `img/` (официальные фото Чистовье, формат .webp, ~10 КБ каждое). Чтобы заменить фото, положите новый файл с тем же именем.
3. **Цены и описания**: в `index.html` в блоке `<div class="products">` у каждой карточки
   поменяйте текст в `<h3>` (название), `<p>` (описание) и `<div class="price">` (например «от 450 сом»).
   Новый товар = скопировать один блок `<article class="product">…</article>`.
4. **Свой домен** (если купите, например chistovie.kg): замените `https://chistovie-kg.onrender.com`
   в `index.html`, `robots.txt`, `sitemap.xml`.

## Размещение: GitHub + Render
1. Создайте репозиторий на github.com (например `chistovie-kg`) и загрузите все файлы этой папки
   (Add file → Upload files).
2. На render.com: New → Blueprint (или Static Site) → выберите репозиторий.
   Render сам прочитает `render.yaml`. Publish directory: `.`, Build command — пусто.
3. Сайт будет по адресу https://chistovie-kg.onrender.com (или похожему, если имя занято —
   тогда поменяйте адрес в файлах из п.4).
4. Свой домен: Render → Settings → Custom Domains.

## Чтобы попасть в поиск
1. Google Search Console (search.google.com/search-console) — добавить сайт, подтвердить,
   отправить `sitemap.xml`, запросить индексирование главной.
2. Яндекс Вебмастер (webmaster.yandex.ru) — то же самое.
3. Ссылка на сайт: 2ГИС, Google Карты (Бизнес-профиль), Яндекс Бизнес, Lalafo, шапка Instagram,
   WhatsApp Business, официальный сайт Чистовье (страница дистрибьюторов).
