# Linux terminal (GitBash) commands (MacOS)

1) Посмотреть где я
```pwd```
2) Создать папку
```mkdir folder_name```
3) Зайти в папку
```cd folder_name```
4) Создать 3 папки
```
mkdir folder_name1 folder_name2 folder_name3 OR
mkdir folder_name{1,2,3}
```
5) Зайти в любоую папку
```cd folder_name3```
6) Создать 5 файлов (3 txt, 2 json)
```
touch file1.txt file2.txt file3.txt file1.json file2.json OR 
touch file{1,2,3}.txt file{1,2}.json
```
7) Создать 3 папки
```
mkdir folder_name1 folder_name2 folder_name3 OR 
mkdir folder_name{1,2,3}
```
8) Вывести список содержимого папки
```
ls OR 
ls -a  = with hidden files OR 
ls -la = with hidden files, date of creation, rights OR 
ls -R  = with files of subfolders
```
9) + Открыть любой txt файл
```
open file1.txt = with default editor OR 
vim file1.txt  = with vim utilitу OR 
nano file1.txt = with nano utility
```
10) + написать туда что-нибудь, любой текст
```
just type your text = with default editor OR 
press "i" then type your text = with vim utility OR 
just type your text = with nano utility
```
11) + сохранить и выйти
```
command + S then command + W = with default editor OR 
press "esc" then type ":wq" then press "enter" = with vim utility OR 
command + O then command + X = with nano utility
```
12) Выйти из папки на уровень выше
```cd ..```
13) переместить любые 2 файла, которые вы создали, в любую другую папку
```
mv path/{file1.txt,file2.txt} path OR 
mv file1.txt file2.txt ../ = move to level up directory OR 
mv folder_name1/{file1.txt,file2.txt} folder_name2 = move from one to another folder within same directory
```
14) скопировать любые 2 файла, которые вы создали, в любую другую папку
```
cp path/{file1.json,file2.json} path OR 
cp file1.json file2.json ../ = copy to level up directory OR 
cp folder_name1/{file1.json,file2.json} folder_name2 = copy from one to another folder within same directory
```
15) Найти файл по имени
```
find path -name file1.txt OR 
find path -iname FiLe1.txt = file name case insensitive OR 
find path -name "*.txt" = if name is unknown OR 
find path -name "file1.*" -type f = if extension is unknown, look for files only OR 
find path -not -name "*.txt" -type f = except .txt files
```
16) просмотреть содержимое в реальном времени
```
tail -f file1.txt = permanent real time monitoring (default 10 last rows)
```
17) вывести несколько первых строк из текстового файла
```
head file1.txt = default 10 first rows OR 
head -n3 file1.txt = 3 first rows
```
18) вывести несколько последних строк из текстового файла
```
tail file1.txt = default 10 last rows OR 
tail -n3 file1.txt = 3 last rows
```
19) просмотреть содержимое длинного файла (команда less)
```less file1.txt ```
20) вывести дату и время
```date```


---



## Задание *
1) Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request
```
$ curl http запрос на сервер http://162.55.220.72:5005/terminal-hw-request > 
response: {"Intro":"Hello!! This is your the first response from server","Tasks":{"Task_1":"Send the next URL in terminal: http://162.55.220.72:5005/get_method?name=(set_your_String)&age=(set_your_number)","result":["Your_String","Your_number"]}}

$ curl 'http://162.55.220.72:5005/get_method?name=Anna&age=27' >
response: ["Anna","27"]
```

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```
#!/bin/bash

#чтобы сделать файл исполняемым в terminal: chmod ugo+x файл_скрипта затем ./файл_скрипта

#Создать папку
mkdir foldername

#3.Зайти в папку
cd foldername

#4.Создать 3 папки
mkdir folder{1,2,3}

#5.Зайти в папку
cd folder1

#6.Создать 5 файлов (3 txt, 2 json)
touch file{1,2,3}.txt file{1,2}.json

#7.Создать 3 папки
mkdir folder{11,22,33}

#8.Вывести список содержимого папки
ls

#13.Переместить любые 2 файла, которые вы создали, в любую другую папку
mv file1.txt,file2.txt folder22
```
