# Инструкция по работе с Git

## Что такое Git

Система управления сохранениями, которая помогает хранить, переключать, редактировать сохранения.

## Подготовка репозитория

Для создания репозитория используется команда *git init*. Команда выполняется один раз в начале работы с документом.

## Создание коммитов

Для создания коммитов сначала файл сохраняется, после чего ипользуются команды: *git add <название файла>*, после чего команда *git commit -m "комментарий изменений"*. Комментарий изменений писать ОБЯЗАТЕЛЬНО.

## Журнал изменений

Чтобы открыть журнал изменений для просмотра текущих коммитов, необходимо ввести команду *git log*. В журнале сохранения представлены в обратном порядке, от самого последнего до самого первого.

## Перемещение между сохранениями

Для перемещения между сохранениями, представленными в журнале, необходимо ввести команду *git checkout <название коммита>*. Название комита это длинный код желтого цвета с комментарием ниже. Для копирования нужно выделить название и нажать правую кнопку мыши и второй раз в команде *git checkout*.

## Слияние веток и решение конфликтов

Для слияния веток, необходимо переместится на ветку, в которую будут добавляться изменения ("чистовик"), далее в терминале ввести команду *git merge <название ветки>*. В поле *название ветки*, добавить ту ветку, в которой вы не находитесь, но хотите соеденить её ("черновик").

Для решения возникших конфликтов (например: появились два текста одновременно), необходимо, если нет решения при помощи автоматической стратегии, выбрать один из представленных варианотов решения, которые находятся в добаленном тексте.

## Ветки в Git

Для создания веток, необходимо ввести команду *git branch*. Чтобы создать новую ветку, необходимо ввести команду *git branch <название ветки>*. Чтобы переключаться между существующими ветками, необходимо ввести команду *git checkout <название ветки>*.

## Удаление веток