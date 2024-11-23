разрешение на публикацию исходного кода данного проекта не было получено

# Мобильное приложение "LexStatus" - заказать юридическую помощь

# Содержание:
1. обзор проекта
2. описание кода/архитектуры, навигация по коду

## 1 обзор проекта

Приложение позволяет найти юриста поблизости, заказать обратный звонок, быть в курсе новостей

Видеообзор:
https://rutube.ru/video/9c53227a4f075e79d635f806066a5d33/

Функционал:

Приложение работает в двух режимах:
1. Онлайн режим: приложение получает и сохраняет на устройстве обновления с сервера: настройки, статьи, новости, отображает карту с офисами компании, позволяет отправить заявку на получение консультации
2. Оффлайн режим: приложение отображает сохраненные на устройстве обновления с сервера: настройки, статьи, новости.

Задачи:
- Разработать мобильное приложение под ключ: клиент (включая дизайн), бэкенд
- Подключить приложение к существующему WordPress сайту
- Разработать веб-админку для настройки приложения
- Разработать 3 варианта дизайна
- Разместить приложение в Google Play Market, AppStore

Скриншоты:
![1](https://github.com/s2023alek/mobile-app-LexStatus/blob/2bb257811302125a9b5020e927ddca2c82222597/README/1024x500.png)
![1](https://github.com/s2023alek/mobile-app-LexStatus/blob/2bb257811302125a9b5020e927ddca2c82222597/README/1.png)
![1](https://github.com/s2023alek/mobile-app-LexStatus/blob/2bb257811302125a9b5020e927ddca2c82222597/README/2.png)
![1](https://github.com/s2023alek/mobile-app-LexStatus/blob/2bb257811302125a9b5020e927ddca2c82222597/README/3.png)
![1](https://github.com/s2023alek/mobile-app-LexStatus/blob/2bb257811302125a9b5020e927ddca2c82222597/README/4.png)


Просмотреть приложение в Google Play:  
https://play.google.com/store/apps/details?id=ru.lexstatus.mobileapp
Просмотреть приложение в iTunes Preview:  
https://itunes.apple.com/us/app/uridiceskaa-kompania-lexstatus/id1035379863?l=ru&ls=1&mt=8


## 2 описание кода/архитектуры, навигация по коду

Языки программирования: php, JavaScript  
Фреймворки: PhoneGap, AngularJs, Ionic Framework  

Подробности о процессе разработки:  
- Использование фреймворка PhoneGap, позволило развернуть приложение одновременно на нескольких мобильных ОС (Android, iOS), почти без затрат времени связанных с устранением специфических проблем для каждой ОС  
- На сайт был установлен плагин WordPress, позволяющий получать содержимое статей в формате json  
- Приложение было протестировано в эмуляторах и физических устройствах

