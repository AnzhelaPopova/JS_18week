1. Сколько живет localStorage?
   хранит данные бессрочно до тех пор пока их не удалят вручную;
2. Как посмотреть localStorage в браузере?
   Содержимое всех хранилищ можно смотреть и редактировать в панели F12, вкладка Application
3. Можно ли хранить данные пользователя в sessionStorage?
   Можно, но данные хранятся только до момента закрытия браузера
4. Как очистить локальное хранилище в браузере?
   Метод clear() очищает хранилище полностью.
   Удаляет запись из хранилища removeItem('ключ').
5. Для чего нужны куки JS?
   При разработке сайтов часть информации (например, токен авторизации или данные пользователя) нужно хранить и читать как в браузере, так и на сервере
6. В чём польза cookie?
   помогают браузеру распознать сайт при повторном посещении и выполнить определенные действия, например, в виде автоматической авторизации
7. Как работать с cookie?
   Запись в cookie работает с помощью присвоения значения новой куки в поле document.cookie
   Для получения значений, записанных в куки, можно просто вывести содержимое document.cookie
   Для кук не предусмотрено специального метода удаления, поэтому для этого используется трюк с установкой кук с параметром expires
8. Как добавить и получить значение из веб-хранилища?
   Для записи используйте метод setItem('ключ', 'значение')
   За чтение отвечает getItem('ключ')
9. Придумайте ещё минимум 3 ситуации, помимо предложенных в уроке, для чего может быть нужно сохранять данные пользователя и какие?
   _Пример из урока: запомнить, что пользователь уже залогинился, что у него лежит в корзине или в каком разделе сайта он сейчас находится_
   сбор статистики. Файлы куки – это источник аналитической информации, необходимой рекламодателям. Реклама, которая показывается на сайтах, опирается именно на индивидуальные файлы cookie, т. е. для каждого пользователя она разная;
   мониторинг сеансов доступа. Чтобы вебмастеру было легче оценивать параметры посещений, в куки сохраняется информация о типе устройства, его местонахождении и времени посещения сайта.
   Сохранение настроек и данных — куки фиксируют, какие действия вы совершали на сайте и какие персональные настройки выстраивали. Например, на сайте по поиску авиабилетов сохраняется информация о языке, валюте, планируемых локациях, дате, а также выбранный билет в корзине. При перезагрузке сайта или выходе из него все фильтры и неоплаченные товары сохраняются.
10. Какие преимущества использования JSON?
    Поддерживается всеми основными платформами JavaScript
    удобен для хранения данных в процессе их обмена между веб-браузером и сайтом или между разными сайтами
11. Какие значения могут быть использованы в JSON?

- **массивы;**
- **объекты;**
- **строки;**
- **числа** (могут быть как целым, так и с плавающей запятой);
- **булевый тип** (значение true или false);
- **значение null** (обозначает отсутствие данных).

12. Как брать данные из JSON?
    JSON.parse() — превращает JSON-данные в объекты или переменные.
