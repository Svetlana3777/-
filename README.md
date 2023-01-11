# Итоговая работа по модулю "Основы языка программирования"
Задание

Вопросы по заданию

Возможна такая ситуация, что мы хотим показать друзьям фотографии из социальных сетей, но соц. сети могут быть недоступны по каким-либо причинам. Давайте защитимся от такого.

Нужно написать программу для резервного копирования фотографий с профиля(аватарок) пользователя vk в облачное хранилище Яндекс.Диск.

Для названий фотографий использовать количество лайков, если количество лайков одинаково, то добавить дату загрузки.
Информацию по сохраненным фотографиям сохранить в json-файл.

Задание:

Нужно написать программу, которая будет:

Получать фотографии с профиля. Для этого нужно использовать метод photos.get.
Сохранять фотографии максимального размера(ширина/высота в пикселях) на Я.Диске.
Для имени фотографий использовать количество лайков.
Сохранять информацию по фотографиям в json-файл с результатами.
*Обратите внимание: *токен для ВК можно получить выполнив инструкцию.

Входные данные:
Пользователь вводит:

id пользователя vk;

токен с Полигона Яндекс.Диска. 
Важно: Токен публиковать в github не нужно!

Выходные данные:
json-файл с информацией по файлу:

    [{
    "file_name": "34.jpg",
    "size": "z"
    }]
    
Измененный Я.диск, куда добавились фотографии.​​

Обязательные требования к программе:

1 Использовать REST API Я.Диска и ключ, полученный с полигона.
2 Для загруженных фотографий нужно создать свою папку.
3 Сохранять указанное количество фотографий(по умолчанию 5) наибольшего размера (ширина/высота в пикселях) на Я.Диске
4 Сделать прогресс-бар или логирование для отслеживания процесса программы.
5 Код программы должен удовлетворять PEP8.
6 У программы должен быть свой отдельный репозиторий.
7 Все зависимости должны быть указаны в файле requiremеnts.txt.​

Необязательные требования к программе:

Сохранять фотографии и из других альбомов.

Сохранять фотографии на Google.Drive.
