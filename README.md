# Night Siege (Forge 1.20.1)

Требования: JDK 17 и интернет при первой сборке.

## Сборка
- Linux/macOS: `./gradlew build`
- Windows: `gradlew.bat build`

При первом запуске gradlew сам скачает gradle-wrapper.jar, затем Gradle 8.1.1 и Forge (это долго).
Готовый мод: `build/libs/nightsiege-1.0.0.jar` -> в папку `mods` (Forge 47.x, MC 1.20.1).

## Тест
`./gradlew runClient`, в мире: `/time set 97000` (5-й день), затем `/time set 109000` (ночь, старт волны).
