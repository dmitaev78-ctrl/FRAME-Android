# FRAME Android

Android-приложение для FRAME Prompt Studio.

## Сборка APK без Android Studio через GitHub

1. Создайте новый репозиторий на GitHub.
2. Загрузите **содержимое папки FRAME_Android** в корень репозитория (важно: `app`, `.github`, `settings.gradle.kts` должны лежать в корне).
3. Откройте вкладку **Actions**.
4. Выберите **Build FRAME APK** → **Run workflow** → **Run workflow**.
5. После успешной сборки откройте выполненный запуск.
6. Внизу страницы в разделе **Artifacts** скачайте **FRAME-Android-APK**.
7. Распакуйте архив — внутри будет `FRAME.apk`.

Приложение в этой версии использует сайт:
https://dmitaev78-ctrl.github.io/FRAME9/

Поэтому для работы приложения нужен интернет.
