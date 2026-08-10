# The Way to Chekushka — Alpha

Мрачный двухмерный экшен с видом сверху о пути Мэлл через мутные подвалы,
гермодвери и стаи фогов к заветной чекушке.

Это публичный репозиторий готовых alpha-сборок. Исходный код игры и история
разработки находятся в основном репозитории проекта.

## Скачать Alpha 0.1.0

| Платформа | Требования | Загрузка |
|---|---|---|
| Windows | Windows 10/11, x86-64 | [Скачать ZIP](https://github.com/samarsky-gamedev/The-way-to-Chekushka-Alpha/releases/download/v0.1.0-alpha.1/The-way-to-Chekushka-v0.1.0-alpha.1-Windows-x86_64.zip) |
| macOS | macOS 11+ на Intel или macOS 13+ на Apple Silicon | [Скачать ZIP](https://github.com/samarsky-gamedev/The-way-to-Chekushka-Alpha/releases/download/v0.1.0-alpha.1/The-way-to-Chekushka-v0.1.0-alpha.1-macOS-universal.zip) |

[Открыть страницу релиза](https://github.com/samarsky-gamedev/The-way-to-Chekushka-Alpha/releases/tag/v0.1.0-alpha.1) ·
[SHA-256](https://github.com/samarsky-gamedev/The-way-to-Chekushka-Alpha/releases/download/v0.1.0-alpha.1/SHA256SUMS.txt)

## Что доступно

- сюжетный этаж из шести связанных комнат с гермодверями, лутом и боссом;
- бесконечный режим с процедурными этажами, сундуками и повышением сложности;
- сетевой кооператив для 1–3 игроков через выделенный сервер;
- серверная симуляция игроков, фогов, боя и органов комнаты босса;
- синхронное поглощение органов боссом при здоровье ниже 30%;
- добивание босса после исчерпания конечного запаса органов;
- совместные переходы между этажами, наблюдение после смерти и воскрешение;
- физический мусор, кровь, пространственный звук и полный набор анимаций.

Для запуска и входа требуется интернет-соединение. Это alpha-версия: баланс,
интерфейс и сетевое поведение ещё могут меняться.

## Установка

### Windows

1. Скачайте Windows ZIP и полностью распакуйте его.
2. Запустите `The way to Chekushka.exe` рядом с одноимённым `.pck`.
3. При предупреждении SmartScreen проверьте имя файла и контрольную сумму,
   затем разрешите запуск, если доверяете этому релизу.

### macOS

1. Скачайте и распакуйте macOS ZIP.
2. Переместите `The way to Chekushka.app` в `Applications` при желании.
3. Сборка подписана встроенной ad-hoc подписью Godot, но не нотарифицирована
   Apple. При блокировке откройте **System Settings → Privacy & Security** и
   используйте **Open Anyway** для этого приложения.

## Чистота сборки

Архивы не содержат локальный профиль разработчика, сохранённую OAuth-сессию,
installation ID, настройки или пользовательские сохранения. При первом запуске
игра начинает с экрана входа и создаёт собственные данные только в системной
папке пользователя на конкретном компьютере.

Перед публикацией выполнены чистый импорт Godot 4.7.1, полный прогон 289 тестов,
Windows smoke-тест с отдельной пустой папкой пользовательских данных и проверка
структуры обоих архивов.

## Контрольные суммы

```text
9EB7BF3B7670B53A6671B7C265FC4E32BD884E435375CA79294737459E48163F  The-way-to-Chekushka-v0.1.0-alpha.1-Windows-x86_64.zip
E5A867D6243CADF6D66868E3B68DE87512A5168288E9B6EC146EABAFFAC30B27  The-way-to-Chekushka-v0.1.0-alpha.1-macOS-universal.zip
```

Сборки созданы из
[`The-way-to-Chekushka@42bb4fd`](https://github.com/samarsky-gamedev/The-way-to-Chekushka/commit/42bb4fd74c2756b130334486ab54ac513091f5d9).

Ошибки и обратную связь можно оставлять в
[Issues](https://github.com/samarsky-gamedev/The-way-to-Chekushka-Alpha/issues).
