#Ошибки TINKOFF INVEST API

Некоторые ошибки 
 
|Код ошибки|Тип ошибки|Текст ошибки|Причины возникновения и </br> рекомендации по устранению|
|---|---|---|---|
12001|UNIMPLEMENTED|Method is unimplemented|Метод не реализован.|
12002|UNAVAILABLE|Deprecated method is unavailable|Метод устарел и недоступен.|
30001|INVALID_ARGUMENT|missing parameter: 'from'|Входной параметр *from* является обязательным.</br>Укажите корректный параметр *from*.|
30002|INVALID_ARGUMENT|the required period should not exceed 7 days|Запрошенный период не может превышать 7 дней.</br>Укажите корректный период.|
30003|INVALID_ARGUMENT|'from' can't be less than the current date|Входной параметр *from* не может быть меньше текущей даты.</br>Укажите корректный параметр *from*.|
30004|INVALID_ARGUMENT|missing parameter: 'to'|Входной параметр *to* является обязательным.</br>Укажите корректный параметр *to*.|
30005|INVALID_ARGUMENT|'id_type' is invalid|Входной параметр *id_type* имеет некорректное значение.</br>Список доступных значений: [*id_type*](https://tinkoff.github.io/investAPI/instruments#instrumentidtype).|
30006|INVALID_ARGUMENT|missing parameter: 'id_type'|Входной параметр *id_type* является обязательным.</br>Укажите корректный параметр *id_type*.|
30007|INVALID_ARGUMENT|missing parameter: 'id'|Входной параметр *id* является обязательным.</br>Укажите корректный параметр *id*.|
30008|INVALID_ARGUMENT|missing parameter: 'figi'|Входной параметр *figi* является обязательным.</br>Укажите корректный параметр *figi*.|
30009|INVALID_ARGUMENT|'from' is invalid|Входной параметр *from* имеет некорректное значение.</br>Укажите корректный параметр *from*.|
30010|INVALID_ARGUMENT|'to' is invalid|Входной параметр *to* имеет некорректное значение.</br>Укажите корректный параметр *to*.|
30011|INVALID_ARGUMENT|interval is invalid|Входной параметр *interval* имеет некорректное значение.</br>Список доступных значений: [*interval*](https://tinkoff.github.io/investAPI/marketdata#subscriptioninterval).|
30012|INVALID_ARGUMENT|'to' can't be less than 'from'|Входной параметр *to* не может быть меньше параметра *from*.</br>Укажите корректные параметры *from* и *to*.|
30013|INVALID_ARGUMENT|'class_code' require for 'id_type' = 'ticker'|Входной параметр *class_code* не может быть пустым при поиске по тикеру.</br>Укажите корректный параметр *class_code*.</br>Подробнее: [Идентификация инструментов](https://tinkoff.github.io/investAPI/faq_identification/).|
30014|INVALID_ARGUMENT|the maximum request period for the given candle interval has been exceeded|Превышен максимальный период запроса для данного интервала свечи.</br>Укажите корректный интервал.</br>Подробнее: [Интервалы свечей и доступные периоды](https://tinkoff.github.io/investAPI/load_history/).|
30015|INVALID_ARGUMENT|parameter 'quantity' is missing or equal to 0|Входной параметр *quantity* является обязательным.</br>Укажите корректный параметр *quantity*.|
30016|INVALID_ARGUMENT|'quantity' is invalid|Входной параметр *quantity* имеет некорректное значение.</br>Укажите корректный параметр *quantity*.|
30017|INVALID_ARGUMENT|missing parameter: 'price'|Входной параметр *price* является обязательным.</br>Укажите корректный параметр *price*. </br> Значение параметра *price* должно быть положительным.</br>units и nanos не могут иметь разные знак и модуль nanos должен быть < 999 999 999|
30018|INVALID_ARGUMENT|price is invalid|Входной параметр *price* имеет некорректное значение.</br>Укажите корректный параметр *price*. |
30019|INVALID_ARGUMENT|missing parameter: 'direction'|Входной параметр *direction* является обязательным.</br>Укажите корректный параметр *direction*.|
30020|INVALID_ARGUMENT|'direction' is invalid|Входной параметр *direction* имеет некорректное значение.|
30021|INVALID_ARGUMENT|missing parameter: 'account_id'|Входной параметр *account_id* является обязательным.</br>Укажите корректный параметр *account_id*.|
30022|INVALID_ARGUMENT|missing parameter: 'state'|Входной параметр *state* является обязательным.</br>Укажите корректный параметр *state*.</br>Список доступных значений: [*direction*](https://tinkoff.github.io/investAPI/operations/#operationstate).|
30023|INVALID_ARGUMENT|invalid parameter: 'state'|Входной параметр *state* имеет некорректное значение.</br>Укажите корректный параметр *state*.</br>Список доступных значений: [*direction*](https://tinkoff.github.io/investAPI/operations/#operationstate).|
30025|INVALID_ARGUMENT|missing parameter: 'order_type'|Входной параметр *order_type* является обязательным.</br>Укажите корректный параметр *order_type*. Список доступных значений: [*order_type*](https://tinkoff.github.io/investAPI/orders/#ordertype).|
30026|INVALID_ARGUMENT|invalid parameter: 'order_type'|Входной параметр *order_type* имеет некорректное значение.</br>Укажите корректный параметр *order_type*.|
30027|INVALID_ARGUMENT|missing parameter: 'order_id'|Входной параметр *order_id* является обязательным.</br>Укажите корректный параметр *order_id*.|
30028|INVALID_ARGUMENT|'order id' is invalid UUID format.|Входной параметр *order_id* имеет некорректное значение.</br>Укажите корректный параметр *order_id* формата UUID.Максимальная длина 36 символов.|
30029|INVALID_ARGUMENT|missing parameter: 'idempotency_key'|Входной параметр *idempotency_key* является обязательным.</br>Укажите корректный параметр *idempotency_key*.|
30030|INVALID_ARGUMENT|'idempotency_key' is invalid|Входной параметр *idempotency_key* имеет некорректное значение.</br>Укажите корректный параметр *idempotency_key*. Максимальная длина 36 символов.|
30031|INVALID_ARGUMENT|missing parameter: 'depth'|Входной параметр *depth* является обязательным.</br>Укажите корректный параметр *depth*.|
30032|INVALID_ARGUMENT|depth is invalid|Входной параметр *depth* имеет некорректное значение.</br>Укажите корректный параметр *depth*.|
30033|INVALID_ARGUMENT|missing parameter: 'trade_clearing_account' or 'class_code'|Параметр *trade_clearing_account* или *class_code* не может быть пустым.|
30034|INVALID_ARGUMENT|not enough balance|Недостаточно средств для совершения сделки (ошибка песочницы).</br>Пополните баланс нужной валюты c помощью метода [*SandboxPayIn*](https://tinkoff.github.io/investAPI/sandbox#sandboxpayin).|
30036|INVALID_ARGUMENT|missing parameter: 'stop_price'|Входной параметр *stop_price* является обязательным.</br>Укажите корректный параметр *stop_price*.|
30037|INVALID_ARGUMENT|missing parameter: 'stop_order_type'|Входной параметр *stop_order_type* является обязательным.</br>Укажите корректный параметр *stop_order_type*.|
30038|INVALID_ARGUMENT|'stop_order_type' is invalid|Входной параметр *stop_order_type* имеет некорректное значение.</br>Список доступных значений: [*stop_order_type*](https://tinkoff.github.io/investAPI/stoporders/#stopordertype).|
30040|INVALID_ARGUMENT|'expire_date' is invalid|Входной параметр *expire_date* имеет некорректное значение.</br>Укажите корректный параметр *expire_date*.|
30041|INVALID_ARGUMENT|the method is available only for futures|Метод предназначен только для работы с фьючерсами.</br>Передайте во входные параметры метода идентификатор фьючерса.|
30042|INVALID_ARGUMENT|not enough assets for a margin trade|Недостаточно активов для маржинальной сделки.</br>Проверьте маржинальные показатели счёта. Вы можете сделать это с помощью метода [*GetMarginAttributes*](https://tinkoff.github.io/investAPI/users#getmarginattributes). |
30043|INVALID_ARGUMENT|missing parameter: 'expiration_type'|Входной параметр *expiration_type* является обязательным.</br>Укажите корректный параметр *expiration_type*.|
30044|INVALID_ARGUMENT|'expiration_type' is invalid|Входной параметр *expiration_type* имеет некорректное значение.</br>Список доступных значений: [*expiration_type*](https://tinkoff.github.io/investAPI/stoporders/#stoporderexpirationtype).|
30045|INVALID_ARGUMENT|missing parameter: 'ticker'|Входной параметр *ticker* является обязательным.</br>Укажите корректный параметр *ticker*.|
30047|INVALID_ARGUMENT|price currency does not match the settlement currency|Валюта цены не совпадает с валютой расчётов по инструменту.</br>Укажите корректную валюту цены. Узнать валюту расчета конкретного инструмента вы можете с помощью метода [*GetInstrumentBy*](https://tinkoff.github.io/investAPI/instruments#getinstrumentby).|
30048|INVALID_ARGUMENT|instrument type is not bond|Метод предназначен только для запроса информации по облигации.</br>Передайте во входные параметры метода идентификатор облигации.|
30049|INVALID_ARGUMENT|post order error: %s|Ошибка метода выставления торгового поручения.</br>Подробнее в тексте ошибки.|
30050|INVALID_ARGUMENT|'instrument_status' is invalid|Входной параметр *instrument_status* имеет некорректное значение.</br>Список доступных значений: [*instrument_status*](https://tinkoff.github.io/investAPI/instruments#instrumentstatus).|
30051|INVALID_ARGUMENT|account margin status is disabled|Для данного договора недоступна маржинальная торговля.</br>Для выставления поручений на срочном рынке, необходимо включить маржинальную торговлю в приложении и терминале.|
30052|INVALID_ARGUMENT|instrument forbidden for trading by API|Для данного инструмента недоступна торговля через API.</br>Вы можете проверить значение параметра api_trade_available_flag данного инструмента c помощью метода [*GetTradingStatus*](https://tinkoff.github.io/investAPI/marketdata#gettradingstatus).|
30053|INVALID_ARGUMENT|post stop_order error: %s|Ошибка метода выставления стоп-заявки.</br>Подробнее в тексте ошибки.|
30054|INVALID_ARGUMENT|instrument type is not a share or etf|Тип инструмента не инвестиционный фонд или акция.|
30055|INVALID_ARGUMENT|order_id cannot be longer than 36 characters|order_id не может быть длиннее 36 символов.|
30056|INVALID_ARGUMENT|stop order settlement currency is not supported|Валюта выставления стоп-заявки не поддерживается.|
30057|INVALID_ARGUMENT|the order is a duplicate, but the order report was not found|Заявка является дублем, но отчет по заявке не найден.</br> Проверьте параметр order_id (идентификатор запроса выставления поручения для целей идемпотентности.) - он должен быть уникальным.|
30058|INVALID_ARGUMENT|task not completed yet, please try again later|Выполнение задачи еще не завершено, попробуйте позже.|
30059|INVALID_ARGUMENT|cancel order error: %s|Ошибка метода отмены заявки.</br>Подробнее в тексте ошибки.|
30060|INVALID_ARGUMENT|cancel stop-order error: %s|Ошибка метода отмены стоп-заявки.</br>Подробнее в тексте ошибки.|
30061|INVALID_ARGUMENT|'from' value out of range|Входной параметр *from* имеет некорректное значение.</br>Укажите значение в пределах от 1970-01-01T00:00:00Z до 2099-12-31T23:59:59.999999999Z включительно.|
30062|INVALID_ARGUMENT|'to' value out of range|Входной параметр *to* имеет некорректное значение.</br>Укажите значение в пределах от 1970-01-01T00:00:00Z до 2099-12-31T23:59:59.999999999Z включительно.|
30063|INVALID_ARGUMENT|'expire_date' value out of range|Входной параметр *expire_date* имеет некорректное значение.</br>Дата должна быть не ранее текущей и не позднее 2099-12-31T23:59:59.999999999Z.|
30064|INVALID_ARGUMENT|the required period should not exceed 31 days|Запрошенный период не может превышать 31 дня.</br>Укажите корректный период.|
30065|INVALID_ARGUMENT|missing parameter: 'task_id'|Входной параметр *task_id* является обязательным.</br>Укажите корректный параметр *task_id*.|
30066|INVALID_ARGUMENT|missing parameter: 'payload'|Входной параметр *payload* является обязательным.</br>Укажите корректный параметр *payload*.|
30067|INVALID_ARGUMENT|'action_type' is invalid|Некорректное значение *action_type*.</br>Выберите допустимое значение.|
30068|INVALID_ARGUMENT|Only limit order is allowed|В настоящий момент возможно выставление только лимитного торгового поручения. Подробнее про [выставление торговых поручений](https://tinkoff.github.io/investAPI/orders_details).|
30069|INVALID_ARGUMENT|Invalid parameter: 'limit'|Входной параметр *limit* имеет некорректное значение.</br>Значение должно быть меньше или равно 1000.|
30070|INVALID_ARGUMENT|'from' can't be more than the current date|Входной параметр *from* имеет некорректное значение.</br>Укажите значение не превышающее текущую дату и время.|
30077|INVALID_ARGUMENT|not available for OTC instruments|Метод недоступен для внебиржевых инструментов.</br>У таких инструментов параметр api_trade_available_flag метода [*GetTradingStatus*](https://tinkoff.github.io/investAPI/marketdata#gettradingstatus) будет иметь значение false.|
30078|INVALID_ARGUMENT|Incorrect minimum price increment|Некорректный шаг изменения цены.</br>Остаток от деления price на min_price_increment должен быть равен 0.|
30079|INVALID_ARGUMENT|instrument is not available for trading|Инструмент недоступен для торгов. Подробнее о [торговых статусах](https://tinkoff.github.io/investAPI/faq_trading_status).|
30080|INVALID_ARGUMENT|quantity must be positive|Количество лотов должно быть положительным числом.|
30081|INVALID_ARGUMENT|account status is closed|Аккаунт закрыт.|
30082|INVALID_ARGUMENT|account status is blocked|Аккаунт заблокирован.|
30083|INVALID_ARGUMENT|order_type is invalid|Некорректный тип заявки.|
30084|INVALID_ARGUMENT|maximum request period has been exceeded|Превышен лимит запрашиваемого периода. |
30085|INVALID_ARGUMENT|price in points is available only for futures and bonds|Тип цены в пунктах доступен только для фьючерсов и облигаций.|
30086|INVALID_ARGUMENT|year is invalid|Некорректный год.|
30087|INVALID_ARGUMENT|missing parameter: query|Входной параметр *query* является обязательным.</br>Укажите не пустой параметр *query*.|
30088|INVALID_ARGUMENT|'from' and 'to' must have the same year|Запрашиваемые даты должны быть в рамках одного года.|
30089|INVALID_ARGUMENT|'to' must not be later than %s|Поле to не должно быть позднее даты, указанной в тексте ошибки.</br>Дата указана в формате ISO 8601.|
30090|INVALID_ARGUMENT|missing parameter: 'siebel_id'|Входной параметр *siebel_id* является обязательным.</br>Укажите корректный параметр *siebel_id*.|
30091|INVALID_ARGUMENT|quantity of instruments can't be more than 100|Количество инструментов не может превышать 100.|
30092|INVALID_ARGUMENT|trading unavailable on weekends|Торги недоступны по нерабочим дням. Больше о [торговых сессиях](https://tinkoff.github.io/investAPI/markets).|
30093|INVALID_ARGUMENT|missing parameter: 'figi' or 'instrument_id'|Один из параметров *figi* или *instrument_id* является обязательным.|
30094|INVALID_ARGUMENT|options trading is not available at the moment|Выставление заявок по опционам недоступно.|
30095|INVALID_ARGUMENT|the request was not executed by the exchange|Заявка не исполнена биржей.</br>Лимитная заявка может не исполняться по причине недостижения установленной цены на бирже.</br>Рыночная же может не исполняться по причине отсутствия сделок с данными инструментов (низкая ликвидность).|
30096|INVALID_ARGUMENT|the order was rejected, try again later|Заявка отклонена, попробуйте повторить позже.|
30097|INVALID_ARGUMENT|inappropriate trading session|Сейчас эта сессия не идёт. Больше о [торговых сессиях](https://tinkoff.github.io/investAPI/markets).|
30098|INVALID_ARGUMENT|currently, there is no trading on this financial instrument|Торги по этому финансовому инструменту сейчас не проводятся.</br>Вы можете проверить актуальный торговый статус инструмента с помощью метода [*GetTradingStatus*](https://tinkoff.github.io/investAPI/marketdata#gettradingstatus).|
30099|INVALID_ARGUMENT|the price is outside the limits for this instrument|Цена вне лимитов по инструменту или цена сделки вне лимита. Подробнее про [выставление торговых поручений](https://tinkoff.github.io/investAPI/orders_details).|
30100|INVALID_ARGUMENT|the price must be positive|Цена должна быть положительной.|
30101|INVALID_ARGUMENT|to trade this financial instrument, pass the test|Для торговли этим инструментом пройдите тестирование. О том, как сдать тестирование и кому оно нужно читайте [тут](https://www.tinkoff.ru/blog/articles/test-invest/).|
30102|INVALID_ARGUMENT|Required parameters missing|Не правильно указаны обязательные параметры.|
30103|INVALID_ARGUMENT|Only best price is allowed|Для инструмента доступно выставление заявки только типа лучшая цена.|
30104|INVALID_ARGUMENT|price_type is invalid| Некорректное значение *price_type*. Значением *price_type* может быть только **PRICE_TYPE_POINT** ИЛИ **PRICE_TYPE_CURRENCY**.|
40002|PERMISSION_DENIED|insufficient privileges|Недостаточно прав для совершения операции.</br>Токен доступа имеет уровень прав read-only, либо у токена нет доступа к указанному счету.</br>Подробнее: [Виды токенов](https://tinkoff.github.io/investAPI/index#_2)|
40003|UNAUTHENTICATED|authentication token is missing or invalid|Токен доступа не найден или не активен.</br>Вы можете выпустить новый токен по ссылке [Настройки](https://www.tinkoff.ru/invest/settings/)|
40004|PERMISSION_DENIED|Working with orders is not available with this account|Выставление заявок недоступно с текущего аккаунта.</br>Брокерский счет не найден, не принадлежит пользователю или закрыт, либо на пользователе ограничения (от Tinkoff Invest API или от биржи). В этом случае нужно обратиться в техподдержку.|
50001|NOT_FOUND|exchange not found|Биржа не найдена по переданному *exchange_id*.</br>Укажите корректный *exchange_id*.|
50002|NOT_FOUND|instrument not found|Инструмент не найден.</br>Укажите корректный идентификатор инструмента.|
50004|NOT_FOUND|account not found|Счёт не найден по переданному *account_id*.</br>Укажите корректный *account_id*.|
50005|NOT_FOUND|order not found|Торговое поручение не найдено по переданному *order_id*.</br>Укажите корректный *order_id*.|
50006|NOT_FOUND|stop-order not found|Стоп-заявка не найдена по переданному *stop_order_id*.</br>Укажите корректный *stop_order_id*.|
50007|NOT_FOUND|task not found|Задача не найдена.|
50008|NOT_FOUND|no orderbook provider|Отсутствует источник данных по стаканам.|
50009|NOT_FOUND|asset not found|Актив не найден.</br>Укажите корректный идентификатор актива.|
50010|NOT_FOUND|brand not found|Бренд не найден.</br>Укажите корректный идентификатор бренда.|
70001|INTERNAL|internal error|Внутренняя ошибка сервиса.</br>Если ошибка повторяется, обратитесь в службу технической поддержки.|
70002|INTERNAL|internal network error|Неизвестная сетевая ошибка, попробуйте выполнить запрос позднее.</br>Если ошибка повторяется, обратитесь в службу технической поддержки.|
70003|INTERNAL|internal error, please try again later|Внутренняя ошибка сервиса, попробуйте выполнить запрос позднее.</br>Если ошибка повторяется, обратитесь в службу технической поддержки.|
80001|RESOURCE_EXHAUSTED|limit of open streams exceeded|Превышен лимит одновременных открытых stream-соединений. Подробнее: [Лимитная политика](https://tinkoff.github.io/investAPI/limits/)|
80002|RESOURCE_EXHAUSTED|request limit exceeded|Превышен лимит запросов в минуту. Подробнее: [Лимитная политика](https://tinkoff.github.io/investAPI/limits/)|
80003|RESOURCE_EXHAUSTED|The limit on SMS sending has been exceeded, try again in a minute|Превышен лимит на отправку СМС, попробуйте через минуту. Если вы не хотите получать СМС при выставлении заявки, отключите отправку СМС в ЛК.|
90001|FAILED_PRECONDITION|need confirmation: %s|Требуется подтверждение операции.</br>Подробнее в тексте ошибки.|
90002|FAILED_PRECONDITION|only for qualified investors|Торговля этим инструментом доступна только квалифицированным инвесторам.|
90003|FAILED_PRECONDITION|The price is too high|Цена заявки слишком высокая. Разбейте заявку на заявки меньшего размера. Подробнее: [Ограничения на стоимость заявки](https://tinkoff.github.io/investAPI/faq_orders/).|
