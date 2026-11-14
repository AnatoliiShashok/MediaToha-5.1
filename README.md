# MediaToha 5.1

Автор: Anatolii Serediuk. Вебплеєр: музика з YouTube, радіо України / Іспанії / Європи, UA + ES.

## Оновлення сайту
1. У репозиторії **видали** `robots.txt` (на проєктному сайті Google його не читає).
2. **Add file -> Upload files**: завантаж `index.html`, `sw.js`, `sitemap.xml`, `manifest.webmanifest`, `og-image.png`, `icon-192.png`, `icon-512.png`, `README.md` (заміни старі) -> Commit.
3. Через 1-2 хв онови сайт на телефоні двічі (service worker оновлюється з другого разу).

## Щоб сайт знаходився в Google за "Mediatoha5.1"
1. Зайди в https://search.google.com/search-console -> **Add property -> URL prefix** -> встав `https://anatoliishashok.github.io/MediaToha-5.1/`.
2. Підтвердження: обери **HTML file**, завантаж отриманий файл `googleXXXX.html` у корінь репозиторію, натисни Verify.
3. **Sitemaps** -> додай `sitemap.xml` -> Submit.
4. **URL inspection** -> встав адресу сайту -> **Request indexing**.
5. Репозиторій: у **About** (шестірня) впиши Website = адреса сайту, Description = "MediaToha 5.1 (Mediatoha5.1) - music and radio web player", Topics: `mediatoha`, `music-player`, `radio`, `pwa`.
6. Перевірка: пошук `site:anatoliishashok.github.io` у Google. Індексація займає від кількох днів до кількох тижнів.
7. Додатково: https://www.bing.com/webmasters (можна імпортувати з Google Search Console).

Посилання на сайт з профілю GitHub, чатів і сторінок друзів прискорюють індексацію.
