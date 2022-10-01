# TXT
GIT Homework 1. TXT
 1. Создать внешний репозиторий c названием TXT.
 Выполняю действия на сайте: New repository -> TXT, ставлю галочку "Добавить Readme file", чтобы при клонировании на локальный компьютер не было предупреждения о клонировании пустой папки.

 2. Клонировать репозиторий TXT на локальный компьютер.
 $ git clone https://github.com/JosieVi/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
 $ cd TXT 
 $ touch new.txt

 4. Добавить файл под гит.
 $ git add new.txt

 5. Закоммитить файл.
 $ git commit -m "add new.txt to repository TXT"

 6. Отправить файл на внешний GitHub репозиторий.
 $ git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 $ nano new.txt
Name: Olga
Age: 36
Number of pets: 0
Desired salary: 3000$

Ctrl+C

 8. Отправить изменения на внешний репозиторий.
 $ git add . 
 $ git commit -m "add completed file new.txt to repository TXT"
 $ git push
 
 9. Создать файл preferences.txt
 $ touch preferences.txt

 10. В файл “preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна, которую хотели бы посетить) в формате TXT.
 $ nano preferences.txt
Favorite movie: Lord of the Rings
Favorite TV show: Queen's Gambit
Favorite food: Fruits
Favorite time of year: Spring
Desired country: Finland

Ctrl+C

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 $ cat > skills.txt
Skills: Linux terminal commands, JavaScript, Git, Postman, DBeaver

Ctrl+C

 12. Сделать коммит в одну строку.
 $ git add . && git commit -m "add files preferences.json, skills.json to repository TXT"

 13. Отправить сразу 2 файла на внешний репозиторий.
 $ git push

 14. На веб интерфейсе создать файл bug_report.txt.
 Repository TXT -> Add file -> Create new file -> bug_report.json

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Bug #1
Summary: "Login: Error messages in the login from are displayed in English"
Environment: "All browsers / devices"
Severity: "Major"
Steps for reproduce:
1. Open https://
2. Follow 'Inloggen' link
3. Fill required fields with invalid data
4. Click 'Inloggen' button
5. Pay attention to error messages
Actual results: "Error messages in the login form are displayed in English"
Expected results: "Error messages in the login form are displayed in the chosen language"

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT
 $ git pull
