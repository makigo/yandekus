# yandekus
#### Yandekus - программа получения курса валют и погодных данных c Яндекс.

### Установка

Скопируйте программу в "/usr/bin" или "/usr/local/bin"  
Для проверки запустите "yandekus --help"  
Готово!

### Помощь

    Использование: yandekus [КЛЮЧ]... [ГОРОД]...

    Команды на выбор:
      -s,  --stock                 Отобразить курсы валют.
      -p,  --pogoda [name|codec]   Отобразить полные метео данные используя код или имя города на англ.
      -w,  --weather [name|code]   Отобразить полные метео данные используя код или имя города на англ.
      -c,  --city [name city]      Отобразить код города (Используйте: имя города на англ.).
      -c,  --code [code city]      Отобразить имя города (Используйте: код).
      -i,  --info [name|code]      Отобразить полную информацию о название или коде города.
                                   (Используйте: код или имя города на англ.)
      -h,  --help                  Показать эту справку и выйти.
      -v,  --version               Показать информацию о версии и выйти.

    Примеры:
         yandekus -c 213      Вывод информации какому городу пренадлежит данный код.
         yandekus -p moscow   Вывод метео данных по городу Москва, также возможно ввести код (например: 213).

    Примечание:
         Коды используются в соответствии с базой данных - Яндекс.Погода (https://yandex.ru/pogoda).
         
### Контакты

Email work.makhonin@gmail.com