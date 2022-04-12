

Возможная дипломная работа

Формулировка задания: Создать онлайн интерфейс для исходящих сообщений с использованием JSON-API {URI} для взаимодействия TX и внешней CBS (автоматизированной банковской системой). Целью интерфейса – создание и блокирование карт во внешней CBS. Во время обработки транзакции в TX, интерфейс в режиме запрос-ответ выполняется синхронный запрос по http-протоколу к удаленному CBS, проходя следующие пункты:

• Аутентификацию

• Передачу данных о карте

В случае, если внешняя система отклонит запрос, создание и блокирование карты в TX так же будет отклонено.

Формат транзакции со стороны TX – XML схема.

Формат сообщения CBS - JSON
