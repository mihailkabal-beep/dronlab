# Завдання для Codex: опублікувати ДронЛаб на GitHub і Vercel

Це статичний сайт з двох HTML-файлів. Нічого не збирати, не встановлювати і не змінювати.

1. Створи публічний репозиторій GitHub `dronlab` і запуш у гілку `main` усі файли цієї папки, зберігши структуру:
   - `index.html`
   - `slides/index.html`
   - `README.md`, `TEACHER_NOTES.md`, `CODEX_DEPLOY.md`, `vercel.json`
2. Увімкни GitHub Pages: Settings → Pages → Source: Deploy from a branch → Branch `main`, папка `/ (root)`.
   Адреса: `https://<user>.github.io/dronlab/` (презентація — `/dronlab/slides/`).
3. Vercel: імпортуй цей репозиторій як новий проєкт.
   - Framework Preset: **Other**
   - Build Command: порожньо; Output Directory: `.` (корінь)
   - Install Command: порожньо
   Після деплою перевір, що відкриваються `/` і `/slides/`.
4. Перевірка після публікації:
   - на `/` вкладка «Місії коду» показує карту, кнопка «▶ Запустити місію» запускає політ;
   - на `/slides/` стрілки гортають слайди, лічильник показує «1 / 26»;
   - посилання «Презентація» в застосунку і «ДронЛаб →» на слайдах ведуть одне до одного.
5. Наприкінці дай обидві адреси (GitHub Pages і Vercel).
