## эти строки нужно вводить только перед первой работой, в дальнейшем их вводить не нужно
1. git config --global user.name "name"   - ваше имя
2. git config --global user.email 'email' - ваш имэйл
3. git comfig --global color.ui auto      - включение подсветики
4. git config --global core.editor 'program name' - если нужно работать в сторонней программе
4. git config --list  - проверка настроек


## команды терминала
    ls - list - показать список файлов
    ls -a - показ всех файлов, даже скрытых
    cd - change directory - (cd download) переход в другую дерикторию
    cd .. - перейти в папку на уровень выше
    cd ../.. - перейти в папку на два уровня выше
    mkdir - make directory - (mkdir testDir) - создать новую дерикторию
    touch - (touch test.txt) - создание файл
    cp - copy - (cp test.txt text_copy.txt) - копирование файла
    mv - move - (mv text.txt text_original.txt) - переиминование файла
    echo - (echo "Hello") - вывод строки в терминал
    echo "Hello" > test_original.txt - записание строки в файл
    cat test_original.txt - открыть файл в терминале
    rm - remove - (rm test_original.txt) - удаление файла
    rm -R testDir - рекурсивное удаление


## Создание репозитория через терминал
    mkdir repo - создание репозитория в текущей дериктории
    cd repo - переход в дерикторию repo
    git init - создание пустого репозитория
    git status - текущее сосотояние репозитория

