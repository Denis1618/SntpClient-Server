# SntpClient-Server
Простые сервер и клиент, реализованные по протоколу SNTP.<br />
## Параметры запуска (ключи) приложения
* --help    				- Справка по использованию программы.

* --seconds-offset [-o]		- Необязательным именнованым аргументом принимается "-o" - 
							количество секунд, которое прибавится к итоговому времени. По умолчанию равно 0.							
* --receive-timeout [-t]    - Необязательным именнованым аргументом принимается "-t" - количиство миллисекунд, 
							которое сервер будет ожидать очередное подключение. По умолчанию равно 1000 * 60 * 5 (5 минут).

## Использование
(os Windows10)<br />
Сервер (клиент аналогично) можно запустить как с помощью двойного клика мышкой по значку файла Server.exe, так и с помощью консоли:
`C:\SNTP\Server\bin\Release>Server.exe -o 10 -t 10000`<br />
Далее сервер перейдет в режим ожидания клиента.
## Автор
Чернущенко Денис, Март 2018