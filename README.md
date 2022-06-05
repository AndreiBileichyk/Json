<<<<<<< HEAD
# JSON
Создать внешний репозиторий c названием JSON:
создаем на гит хабе репозиторий с названием Json

Клонировать репозиторий JSON на локальный компьютер:
git clone git@github.com:AndreiBileichyk/Json.git

Внутри локального JSON создать файл “new.json”:
touch new.json

Добавить файл под гит:
git add new.json

Закоммитить файл:
git commit -m "add new file"

Отправить файл на внешний GitHub репозиторий.
git push

Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать вформате JSON:
vim new.json
{
"name": "Билейчик Андрей Валентинович",
"age": 36,
"number of pets": 1,
"future desired salary": 500
}
:wq

Отправить изменения на внешний репозиторий:
git add .
git commit -m "update new.json"
git push

Создать файл preferences.json:
touch preferences.json

В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:
touch preferences.json
vim preferences.json
{
"favorite movie": "Легенда №17",
"favorite show": "Молодежка",
"favourite food": "пицца",
"favorite time of year": "зима",
"party you wish to visit": "Сингапур"
}
:wq

Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON :
touch sklls.json
vim sklls.json
{
"my new skills": "Git, github, git bash, Jmeter, mobile and web testing, API, sql,data transfer protocols"
}
:wq

Отправить сразу 2 файла на внешний репозиторий : 
git add . 
git commit -m "add two new file"
git push

На веб интерфейсе создать файл bug_report.json":
на github в репозитории Json нажимаем add file - create new file- bug_report.json 
Сделать Commit changes (сохранить) изменения на веб интерфейсе:
в Commit changes пишем Create bug_report.json и нажимаем Commit changes

На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:
Войти в bug_report.json
Заполнить: {
"Summary": "Что? Где? При каких условиях?",
  "Description": "STR, result, expected result",
  "Priority": "Low",
  "Environment": "windows 10, google chrom ver..",
  "Attachment": "scrin"
}

Сделать Commit changes (сохранить) изменения на веб интерфейсе:
В Commit changes написать: filling in the file
Нажать Commit changes

Синхронизировать внешний и локальный репозиторий JSON:
В консоли набрать:
Git fetch
Git pull
=======

>>>>>>> 3185c32392a8153635bac0746682da871f8ae80a
