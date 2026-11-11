# RocketCheat Loader (StandRocket V1.07)

Приложение просит root у KernelSU (настоящий `su`), показывает «загрузку» и запускает игру из `app/src/main/assets/index.html` в WebView. Интернет не нужен.

## Как получить APK
**Вариант 1 — GitHub (без Android Studio):**
1. Создай репозиторий на github.com и загрузи в него всё содержимое этой папки (включая скрытую `.github`).
2. Вкладка Actions → Build APK → Run workflow (или просто после push).
3. Когда сборка зелёная — открой её, внизу Artifacts → `RocketCheat-apk` → скачай, распакуй, поставь `app-debug.apk`.

**Вариант 2 — Android Studio:** File → Open → эта папка → Build → Build APK(s).

## Использование
Открой приложение → «ПОЛУЧИТЬ ROOT» → в KernelSU разреши. Без root игра не запускается.
Чтобы обновить игру, замени `app/src/main/assets/index.html` и пересобери.
