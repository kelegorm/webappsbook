# GET  запросы
### GET запросы
Это самые популярные запросы. С пом. них мы запрашиваем файлы с сервера.
#### URL-Параметры
GET-запрос выглядит так:
http://mysite.com
http://mysite.com/about
http://mysite.com/images/2014/img1.jpg
В помощью
Но если мы будем искать что-нибудь в гугле, то мы окажемся на такой странице:
[https://www.google.ru/search?q=something&oq=something&aqs=chrome..69i57.6044j0j7&sourceid=chrome&espv=210&es\_sm=91&ie=UTF-8]
Адрес запроса состоит из двух частей, разделенных знаком `?`. Первая часть - это адрес запроса, а вторая - это url-переменные. Они перечисленны парами ключ=значение и разделены знаком `&`. По такому адресу обычно скрывается не файл, а серверный скрипт. URL-переменные нужны для передачи данных в скрипт, чтобы он выдал нужный результат.

В этих запросах вся передаваемая информация находится в строке URL.
