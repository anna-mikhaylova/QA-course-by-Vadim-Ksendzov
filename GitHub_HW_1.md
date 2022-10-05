# GIT Homework 1. Работа с файлами форматов JSON, XML, TXT


### JSON
 
 1. Создать внешний репозиторий c названием JSON
```
1. Авторизоваться на https://github.com/
2. Нажать раздел "Repositories"
3. Нажать кнопку "New"
4. В поле "Repository name" написать JSON
5. Нажать "Create repository"
```
 2. Клонировать репозиторий JSON на локальный компьютер
 ```
 git clone https://github.com/anna-mikhaylova/JSON.git
 ```
 3. Внутри локального JSON создать файл “new.json”
 ```
 cd JSON then cat > new.json and then press control + C
           OR touch new.json
 ```
 4. Добавить файл под гит
 ```
 git add new.json
 ```
 5. Закоммитить файл
 ```
 git commit -m "add new file"
 ```
 6. Отправить файл на внешний GitHub репозиторий
 ```
 git push
 ```
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных). Всё написать в формате JSON
 ```
 vim new.json then press "i" 
 
 {
    "name":"Anna",
    "surname":"Mikhaylova",
    "age":"27",
    "number_of_pets":"3"
}

 then press "esc" then type ":wq"
 ```
 8. Отправить изменения на внешний репозиторий
 ```
 git add new.json then git commit -m "add name, surname, age, number of pets" then git push
 ```
 9. Создать файл preferences.json
 ```
 touch preferences.json
 ```
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON
 ```
 vim preferences.json then press "i" 
 
 {
	"movie":"1+1",
	"series":"Misfits",
	"food":"mushrooms",
	"season":"summer",
	"country":"Canada"
}

 then press "esc" then type ":wq"
 ```
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 ```
 vim skills.json then press "i" 
 
 {
	"skill_1":"terminal",
	"skill_2":"Postman",
	"skill_3":"testing_documentation",
	"skill_4":"SQL"
}

 then press "esc" then type ":wq"
 ```
 12. Отправить сразу 2 файла на внешний репозиторий
 ```
 git add * then 
 git commit -m "create 2 new files" then 
 git push 
 ```
 13. На веб интерфейсе создать файл bug_report.json.
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 ```
 1. Открыть репозиторий JSON
 2. Нажать на кнопку "Add file"
 3. Нажать "Create new file"
 4. В поле name написать "bug_report.json"
 5. В поле Commit new file написать "Create bug_report.json"
 6. Нажать на кнопку Commit new file
 ```
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
 ```
 Нажать на кнопку Карандаш
 
{
  "1":"Bug_id",
  "2":"Reporter_name",
  "3":"Date",
  "4":"Project",
  "5":"Severity",
  "6":"Priority",
  "7":"Title",
  "8":"Description",
  "9":"Steps_to_reproduce",
  "10":"Expected_result",
  "11":"Actual_result"
  "12":"Environment",
  "13":"Attachments"
}
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 ```
 В поле Commit changes написать "Update bug_report.json"
 Нажать на кнопку Commit changes
 ```
 17. Синхронизировать внешний и локальный репозиторий JSON
 ```
 git pull
 ```

---


### XML

 18. Создать внешний репозиторий c названием XML
 ```
1. Авторизоваться на https://github.com/
2. Нажать раздел "Repositories"
3. Нажать кнопку "New"
4. В поле "Repository name" написать XML
5. Нажать "Create repository"
```
 19. Клонировать репозиторий XML на локальный компьютер
 ```
 git clone https://github.com/anna-mikhaylova/XML.git
 ```
 20. Внутри локального XML создать файл “new.xml”
 ```
 cd XML and then 
 touch new.xml
 ```
 21. Добавить файл под гит
 ```
 git add new.xml
 ```
 22. Закоммитить файл
 ```
 git commit -m "create new.xml
 ```
 23. Отправить файл на внешний GitHub репозиторий
 ```
 git push
 ```
 24. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных). Всё написать в формате XML
 ```
 vim new.xml then press "i" 
 
 <QA>
	<first_name>Anna</first_name>
	<last_name>Mikhaylova</last_name>
	<age>27</age>
	<pets>3</pets>
</QA>

 then press "esc" then type ":wq"
 ```
 25. Отправить изменения на внешний репозиторий
 ```
 git add * then 
 git commit -m "modified new.xml" then 
 git push 
 ```
 26. Создать файл preferences.xml
 ```
 touch preferences.xml
 ```
 27. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
 ```
 vim preferences.xml then press "i" 
 
 <preferences>
	<movie>1+1</movie>
	<series>Misfits</series>
	<food>chips</food>
	<season>summer</season>
	<country>Canada</country>
</preferences>

 then press "esc" then type ":wq"
 ```
 28. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 ```
 vim preferences.xml then press "i" 
 
 <preferences>
	<movie>1+1</movie>
	<series>Misfits</series>
	<food>chips</food>
	<season>summer</season>
	<country>Canada</country>
</preferences>

 then press "esc" then type ":wq"
 ```
 29. Сделать коммит в одну строку
 ```
 git add * ; git commit -m "create 2new xml file"
 ```
 30. Отправить сразу 2 файла на внешний репозиторий
 ```
 git push
 ```
 31. На веб интерфейсе создать файл bug_report.xml
 32. Сделать Commit changes (сохранить) изменения на веб интерфейсе
  ```
 1. Открыть репозиторий XML
 2. Нажать на кнопку "Add file"
 3. Нажать "Create new file"
 4. В поле name написать "bug_report.xml"
 5. В поле Commit new file написать "Create bug_report.xml"
 6. Нажать на кнопку Commit new file
 ```
 33. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
 ```
 Нажать на кнопку Карандаш
 
<bug_report> 
   <1>Bug_id</1>
   <2>Reporter_name</2>
   <3>Date</3>
   <4>Project</4>
   <5>Severity</5>
   <6>Priority</6>
   <7>Title</7>
   <8>Description</8>
   <9>Steps_to_reproduce</9>
   <10>Expected_result</10>
   <11>Actual_result</11>
   <12>Environment</12>
   <13>Attachments</13>
</bug_report>
```
 34. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 ```
 В поле Commit changes написать "Update bug_report.xml"
 Нажать на кнопку Commit changes
 ```
 35. Синхронизировать внешний и локальный репозиторий XML
 ```
 git pull
 ```

---

### TXT

 1. Создать внешний репозиторий c названием TXT
 ```
1. Авторизоваться на https://github.com/
2. Нажать раздел "Repositories"
3. Нажать кнопку "New"
4. В поле "Repository name" написать TXT
5. Нажать "Create repository"
```
 2. Клонировать репозиторий TXT на локальный компьютер
 ```
 git clone https://github.com/anna-mikhaylova/TXT.git
 ```
 3. Внутри локального TXT создать файл “new.txt”
 ```
 cd TXT then 
 touch new.txt
 ```
 4. Добавить файл под гит
 ```
 git add new.txt 
 ```
 5. Закоммитить файл
 ```
 git commit -m "create new txt file"
 ```
 6. Отправить файл на внешний GitHub репозиторий
 ```
 git push
 ```
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных). Всё написать в формате TXT
 ```
 vim new.txt then press "i" 
 
 Name - Anna
 Surname - Mikhaylova
 Age - 27
 Pets - 3
 
 then press "esc" then type ":wq"
 ```
 8. Отправить изменения на внешний репозиторий
 ```
 git add new.txt then 
 git commit -m "add personal information" then 
 git push
 ```
 9. Создать файл preferences.txt
 ```
 touch preferences.txt
 ```
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT
 ```
 vim preferences.txt then press "i" 
 
 fav_movie - 1+1
 fav_series - Misfits
 fav_food - chips
 fav_season - summer
 country - Canada
 
 then press "esc" then type ":wq"
 ```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 ```
 vim skills.txt then press "i" 
 
 skill_1 - terminal
 skill_2 - Postman
 skill_3 - testing_documentation
 skill_4 - SQL

 then press "esc" then type ":wq"
 ```
 12. Сделать коммит в одну строку
 ```
 git add * ; git commit -m "add information"
 ```
 13. Отправить сразу 2 файла на внешний репозиторий
 ```
 git push
 ```
 14. На веб интерфейсе создать файл bug_report.txt
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 ```
 1. Открыть репозиторий TXT
 2. Нажать на кнопку "Add file"
 3. Нажать "Create new file"
 4. В поле name написать "bug_report.txt"
 5. В поле Commit new file написать "Create bug_report.txt"
 6. Нажать на кнопку Commit new file
 ```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
 ```
 Нажать кнопку Карандаш
 
 1 - Bug_id
 2 - Reporter_name
 3 - Date
 4 - Project
 5 - Severity
 6 - Priority
 7 - Title
 8 - Description
 9 - Steps_to_reproduce
 10 - Expected_result
 11 - Actual_result
 12 - Environment
 13 - Attachments
 ```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 ```
 В поле Commit changes написать "Update bug_report.txt"
 Нажать на кнопку Commit changes
 ```
 18. Синхронизировать внешний и локальный репозиторий TXT
 ```
 git pull
 ```