# lab07
1) Делаю инструкцию по первому коммиту;
2) Пишу обычный код на с++ в ./hello/hello.cpp;
3) Туда же пишу докерфайл;
4) Пишу код для CI.yml файла в ./github/workflows/CI.yml;

Команды:
```
FROM - задает базовый класс
LABEL - задает описание различных метаданных
WORKDIR - задает рабочую директорию
COPY - копирует файли и папки в контейнер
RUN - выполняет команду однажды при сборке
CMD - выполнение команды при каждом запуске, в нашем случае это
-t - задать устройство, на котором запускается контейнер
-i - запуск в интерактивном режиме
build - сборка
run - запуск контейнера
-p - задать порт
diff - показать разницу
images - вывод всех образов
image - вывод конкретного образа
rm - удалить контейнер
rmi - удалить образ
logs - вывод логов контейнера
inspect - вывод подробной информации по контейнеру
