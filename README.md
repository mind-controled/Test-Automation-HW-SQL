## Особенности запуска:

1. Запустить контейнер с mysql командой ``docker-compose up``
2. Запустить приложение командой:

``java -jar artifacts/app-deadline.jar -P:jdbc.url=jdbc:mysql://localhost:3306/app -P:jdbc.user=app -P:jdbc.password=pass``

3. Запустить автотесты
4. Перед повторным запуском автотестов следует остановить контейнер командой ``docker-compose down`` и повторить шаги 1-2
