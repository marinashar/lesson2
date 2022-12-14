## Что такое Github?


Github - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория 

Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием.

## Git add

Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add <имя файла>*.

## Создание коммитов

Для того, чтобы создать коммит (сохранение), необходимо выполнить команду *git commit -m "Сообщение"*.

## Создание ветки

Для того, чтобы создать ветку, нужно использовать *git branch <имя ветки>* или *git checkout -b <имя ветки>*.

## Переключение с ветки на ветку

Чтобы переключиться с одной ветки на другую, необходимо вызвать команду *git checkout <имя ветки>*.

## Совмещение двух вариантов текста

Чтобы слить любую ветку с текущей, вызываем *git merge <имя ветки для слияния с текущей>*.

## Удаление веток

Чтобы удалить не нужную ветку, необходимо вызвать команду *git branch -d <имя ветки, которую хотим удалить>*.

## Добавление изображения

В Git не принято добавлять файлы изображений, их хранят на cторонних носителях. Чтобы исключить ненужные файлы из
загрузки, есть команда *git ignore*.

## Конфликт изменений

При работе в двух ветках одновременно может возникнуть ситуация, когда в одной и другой ветке мы по-разному изменили блок текста. Если затем мы попробуем слить эти ветки, Git сообщит о конфликте и предложит выбрать, какие же изменения записать. 
Поэтому у проекта в репозитории должен быть один ответственный пользователь, наделённый правом проводить слияния и разрешать конфликты.

## Визуализация всех веток

Чтобы отобразить коммиты в виде дерева, нужно вызвать команту *git log --graph*