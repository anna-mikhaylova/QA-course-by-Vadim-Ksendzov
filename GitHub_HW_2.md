# GitHub. HW_2. Работа с ветками


1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bag Reports
git branch SQL
git branch Charles
git branch Mobile testing
```
2. Запушить все ветки на внешний репозиторий
```
git push -u origin --all
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout BagReports then 
vim bag_report.txt then press "i" 

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

then press "esc" then type ":wq"
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add bag_report.txt ; git commit -m "add bag_report.txt" then 
git push
```
5. Вмержить ветку Bag Reports в Main
```
git checkout main then 
git merge BagReports
```
6. Запушить main на внешний репозиторий
```
git push
```
7. В ветке CheckLists набросать структуру чек листа
```
git checkout CheckLists then 
vim check_list.txt then press "i" 

1. id
2. title
3. inputs
4. expect result
5. status
6. bug

then press "esc" then type ":wq"
```
8. Запушить структуру на внешний репозиторий
```
git add check_list.txt ; git commit -m "add check_list.txt"
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
1. Нажать кнопку "Compare & pull request"
2. Нажать "create pull request"
3. После проверки нажать "Merge pull request"
4. Нажать "Confirm merge"
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull
```