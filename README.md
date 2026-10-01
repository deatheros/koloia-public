# Koloia

Дивіться. Читайте. Грайте. Знаходьте нове у своєму колі.

Тут лежить готовий застосунок Koloia для Android. Коду тут немає.

## Як встановити

1. Відкрийте сторінку [Releases](https://github.com/deatheros/koloia-public/releases) і завантажте файл `.apk` з розділу **android-production**.
2. Відкрийте завантажений файл. Коли Android запитає, дозвольте встановлення.
3. Далі Koloia сама пропонуватиме оновлення, коли вийде нова версія.

Розділ **android-test** — тестова версія. Вона працює лише в тестовій мережі.

## Як перевірити файл

Справжня Koloia підписана одним із цих ключів (SHA-256 сертифіката):

- основна версія (**android-production**): `48:4D:66:27:5C:29:2C:B6:54:60:BC:B7:D3:CC:37:E0:D6:A1:30:CD:10:47:B7:28:91:4C:9A:9B:68:92:6A:B3`
- тестова версія (**android-test**): `34:42:CF:F1:0D:64:D0:0E:A7:4F:8B:D4:43:3C:F4:75:00:70:7B:1E:B5:6F:4C:8D:4A:21:CA:CE:C2:86:CC:F7`

Ті самі відбитки опубліковані на сайті: <https://koloia.app/.well-known/assetlinks.json>. Відбиток завантаженого файлу показує команда `apksigner verify --print-certs файл.apk`.

Усі права захищені. Умови — у файлі [LICENSE](LICENSE).

---

# Koloia

Watch. Read. Play. Discover more with your people.

This repository holds the ready-to-install Koloia app for Android. There is no source code here.

## How to install

1. Open [Releases](https://github.com/deatheros/koloia-public/releases) and download the `.apk` file from **android-production**.
2. Open the downloaded file. When Android asks, allow the installation.
3. From then on Koloia offers each new version itself.

**android-test** is the test version. It works only inside the test network.

## How to verify the file

A genuine Koloia is signed with one of these keys (certificate SHA-256):

- main version (**android-production**): `48:4D:66:27:5C:29:2C:B6:54:60:BC:B7:D3:CC:37:E0:D6:A1:30:CD:10:47:B7:28:91:4C:9A:9B:68:92:6A:B3`
- test version (**android-test**): `34:42:CF:F1:0D:64:D0:0E:A7:4F:8B:D4:43:3C:F4:75:00:70:7B:1E:B5:6F:4C:8D:4A:21:CA:CE:C2:86:CC:F7`

The same fingerprints are published on the site: <https://koloia.app/.well-known/assetlinks.json>. `apksigner verify --print-certs file.apk` shows the fingerprint of a downloaded file.

All rights reserved. See [LICENSE](LICENSE).
