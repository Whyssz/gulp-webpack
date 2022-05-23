# Описание

Это готовая сборка gulp + webpack.
Взята с канала "Верстальщик по жизни" и немного подправлена.

# Краткое Описание

___Возможности:___
1. Работа сборки в разных режимах (dev поддерживает)
2. Сжатие картинок и автоматическая подстановки webp, если браузер поддерживает (главое правильно оформляйте теги img) *build
3. Создание min файлов *build
4. Лёгкое внедрение модулей в webpack по необходимости
5. Конвертор шрифтов (ttf swap) и их запись для удобной работы *dev
6. Разбитые css файлы, статические настройки для проекта
7. Все функции сборки, сжатия, конвертации происходят автоматически

___Исключение плагинов___
Значительные изменения в сборку не вносил, за исключением пары плагинов и небольшого изменения сборки под себя.
Исключены плагины по работе с путями (img), для исключения ошибок в различных IDE и плагин по автоматической загрузке на FTP, мало использую, да и загрузить собраный архив занимает пару секунд.

Более подробно саму сборку можно посмотреть на самом канале с которого и бралась основа [Ссылка на источник]https://www.youtube.com/watch?v=jU88mLuLWlk
___
# Установка 

* Установить `node.js` 
* Желательно использовать `git/bash`
* Скачать сборку, прописать команду `npm i`

___

# Как это работает
 
* npm run dev команда запускающая сборку в режиме разработчик
* npm run build собирает сборку, можно проверить есть ли ошибки уже в готовом проекте перед сдачей
* npm run zip собирает готовые файлы в архив

В файле gulpfile.js можно оснакомится более подробно, понять всю суть можно без каких-либо проблем.
