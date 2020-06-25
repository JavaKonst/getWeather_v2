# GetWeatherApp v2
<p>Погода в городе (weatherAPI, SQLite, JDBC, JSON и пр.)<p>

<p><h6><i>Консольная программа, выдает по введенному городу текущую температуру окр.воздуха.
Используются погодные сервисы YandexWeather (пробный период, может быть не доступен), AccuWeather, OpenWeather.
Также программа записывает в базу данных SQlite запрос-ответ ввиде "Город-температура".</i></h6></p>

<ol><ins>Эксплуатация программы:</ins>
<li>Запустить класс Main.</li>
<li>В консоли ввести город (кириллицей, регистр не важен).</li>
<li>Цифрой выбрать погодный сервис. Сервис от Яндекс предоставляет временный доступ, поэтому может быть не доступен.</li>
<li>После подтверждения программа выдаст город и температуру в нем, а также произведет запись в базу данных (имеющуюся или создаст новую).</li></ol>
