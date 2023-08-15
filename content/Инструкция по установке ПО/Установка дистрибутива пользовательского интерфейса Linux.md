
Установка дистрибутива пользовательского интерфейса для актуальных версий Linux (Ubuntu, Debian, Fedora, Arch)

Скачать последний дистрибутив по ссылке:

![Значок](https://gamma-wellbore.com/wp-content/plugins/download-manager/assets/file-type-icons/zip.svg)

### [Client_linux](https://gamma-wellbore.com/download/client_linux/)

 1 файл(ы)  45 МБ

[Скачать](https://gamma-wellbore.com/gamma_help/installation/#)

Разархивировать архив стандартными средствами и перейти в терминале по в распакованную папку:

![](https://gamma-wellbore.com/wp-content/uploads/2023/02/image_2023-03-27_08-49-45.png)

Перед запуском ПО Гамма необходимо указать IP адрес серверной части приложения следующей командой:

export CELERY_REDIS_HOST=X.X.X.X       где X.X.X.X – IP машины запущенной в докере серверной частью

И прописать в явном виде где нужно искать недостающие библиотеки (в текущей папке с ПО):

export LD_LIBRARY_PATH=путь к текущей папке

команда pwd выводит полный путь к текущей папке, его можно скопировать.

Далее ПО запускается стандартной для Linux командой: ./GammaGui (перед / обязательно нужно поставить  точку).

Все команды и порядок их запуска:

![](https://gamma-wellbore.com/wp-content/uploads/2023/02/image_2023-03-27_08-58-22-e1679889959677.png)

Запущенный продукт выглядит полностью аналогично интерфейсу в Windows:

![](https://gamma-wellbore.com/wp-content/uploads/2023/02/image_2023-03-27_08-59-27-1024x579.png)

Поздравляем, можно работать в ПО Гамма в Линуксе.