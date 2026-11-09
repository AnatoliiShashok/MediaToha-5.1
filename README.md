# MediaToha 5.1

Автор: Anatolii Serediuk. Одна сторінка (PWA): YouTube-музика, радіо України / Іспанії / Європи, UA + ES.

## Публікація на GitHub Pages
1. github.com → **New repository** (наприклад `mediatoha`) → Create.
2. **Add file → Upload files** → перетягни всі файли з цієї папки (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`) → **Commit changes**.
3. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)` → Save.
4. Через 1–2 хвилини сайт буде на `https://ТВІЙ_ЛОГІН.github.io/mediatoha/`.
5. На телефоні відкрий адресу в Chrome → меню ⋮ → **Додати на головний екран / Установити додаток**.

## Примітки
- Сайт працює по https, тому запасний плеєр YouTube (помилка 153) тут працює.
- Радіо: на https показуються лише станції з https-потоком.
- Ключ YouTube Data API (необов'язково) вводиться в «Меню» і зберігається лише в браузері, у код не потрапляє.
- У коді є публічні client_id Jamendo і SoundCloud (демо). Для стабільності отримай власний ключ Jamendo: developer.jamendo.com.
