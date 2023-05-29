# Доступные протоколы взаимодействия

TINKOFF INVEST API поддерживает возможность использования различных протоколов.
О том, как начать работать с gRPC, вы можете прочитать на [странице](/investAPI/grpc/).

| Протокол | Подробнее| Endpoint |
|----------|----------|----------|
| gRPC   | API реализован на быстром, удобном и функциональном протоколе [gRPC](https://grpc.io/docs/). | https://invest-public-api.tinkoff.ru:443 - продовый сервис, https://sandbox-invest-public-api.tinkoff.ru:443 - сервис песочницы |
| gRPC-web   | Для поддержки web-клиентов, например браузерных JS скриптов, внедрена поддержка [gRPC-web](https://grpc.io/docs/platforms/web/basics/).   | https://invest-public-api.tinkoff.ru:443 - продовый сервис, https://sandbox-invest-public-api.tinkoff.ru:443 - сервис песочницы |
| REST API   | Для клиентов, привыкших работать с REST API, реализован прокси [Swagger](https://tinkoff.github.io/investAPI/swagger-ui/). Инструкцию по использованию Swagger вы можете прочитать [здесь](/investAPI/swagger/).| https://invest-public-api.tinkoff.ru/rest/- продовый сервис, https://sandbox-invest-public-api.tinkoff.ru/rest/ -- сервис песочницы |
| WebSoket   |Внедрена поддержка Websoket протокола.  | wss://invest-public-api.tinkoff.ru/ws/ |
