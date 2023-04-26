# terminal_homework_1
Homework terminal thema 1

1. Посмотреть где я.
       
       pwd 
2. Создать папку.
       
       mkdir homework
3. Зайти в папку.
       
       cd homework
4. Создать 3 папки.
       
       mkdir test_1 test_2 test_3
5. Зайти в любую папку.

       cd test_2 
6. Создать 5 файлов (3 txt, 2 json).

       touch 1.txt 2.txt 3.txt 1.json 2.json
7. Создать 3 папки.
   
       mkdir folder_1 folder_2 folder_3
8. Вывести список содержимого папки.

       ls
9. Открыть любой txt файл.

       nano 1.txt   
10. Написать туда что-нибудь, любой текст.
11. Cохранить и выйти.
12. Выйти из папки на уровень выше.

        cd ..
13. Переместить любые 2 файла, которые вы создали, в любую другую папку.

        mv 1.txt 1.json ../test_1
14. Cкопировать любые 2 файла, которые вы создали, в любую другую папку.

        cp 2.txt 2.json ../test_3
15. Найти файл по имени.
        
        find . -name 3.txt
16. Просмотреть содержимое в реальном времени.

        tail -f 1.txt
17. Вывести несколько первых строк из текстового файла.

        head -4 1.txt
18. Вывести несколько последних строк из текстового файла.

        tail -4 1.txt
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает.
    
        less 1.txt
20. Вывести дату и время.

        date
21. Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request

        curl http://162.55.220.72:5005/terminal-hw-request
22. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13.

	    #!/bin/bash
	    cd homework
	    mkdir test_1 test_2 test_3
	    cd test_2
	    touch 1.txt 2.txt 3.txt 1.json 2.json
        mkdir folder_1 folder_2 folder_3
        ls
        mv 1.txt 1.json ../test_1
