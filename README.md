# Dynamic Island Demo для Android

Это Android-оболочка для `index.html` из `dynamic_island_project.zip`. Она запускает интерактивную HTML-симуляцию внутри WebView.

Это не системная Dynamic Island и не плавающая панель поверх других приложений. Android guide из исходного архива содержит только пример сервиса и неполон для самостоятельной сборки, поэтому он не включён в APK.

## Сборка через GitHub Actions

Загрузите содержимое этой папки в корень нового GitHub-репозитория. Файл `.github/workflows/build.yml` запускает сборку при push и вручную. После успешного запуска скачайте артефакт `DynamicIsland-APK`; внутри будет `app-debug.apk`.

APK debug-signed предназначен для установки и проверки на устройстве.
