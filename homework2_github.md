### Homework 2 GitHub
```
1. На локальном репозитории сделать ветки для: Postman, Jmeter, CheckLists, Bug Reports, SQL, Charles, Mobile testing:
```

1) Зайти в свой профиль на *GitHub*
2) Нажать *"Repositories"*
3) Далее кнопка *"New"*
4) Написать название репозитория *"Branches"*, поставить галочку напротив поля *"Add a README file"*, нажать на кнопку *"Create repository"*
5) Зайти в созданный репозиторий *Branches*
6) Нажать на кнопку *"Code"*
7) Скопировать ссылку
8) Зайти в *GitBash*
9) Написать команду `git clone https://github.com/ratenok/branches.git`
10) Зайти в папку Branches: `cd Branches`
11) Создать ветки: `git branch Postman`
    `git branch Jmeter`
   ` git branch CheckLists`
    `git branch Bug_Reports`
   ` git branch SQL`
    `git branch Charles`
    `git branch Mobile_testing`
  
```
2. Запушить все ветки на внешний репозиторий:
```
git push -u origin Postman SQL Jmeter CheckLists Charles Bug_Reports Mobile_testing

```
3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта:
```
1) Зайти в ветку Bug_Reports: `git checkout Bug_Reports`
2) Открыть редактор файла: `vim bug_report.txt`
3) `i` - начать редактирование
4) The structure of a bug report: 
    1) Bug ID
    2) Summary
    3) Description
    4) Steps to reproduce
    5) Actual result
    6) Expected result
    7) Environment
    8) Severity
    9) Priority
    10) Reported by
    11) Reported on
    12) Status
5) `:wq` - сохранить и выйти 


```
4. Запушить структуру баг репорта на внешний репозиторий:
```
1) Добавить файл под гит: `git add bug_report.txt`
2) Закоммитить файл: `git commit -m "Add bug_report.txt file"`
3) Запушить файл на внешний репозиторий: `git push`

```
5. Вмержить ветку Bug Reports в Main:
```
1) Зайти в main: `git checkout main`
2) Вмержить ветку: `git merge Bug_Reports`

```
6. Запушить main на внешний репозиторий:
```
`git push`

```
7. В ветке CheckLists набросать структуру чек листа:
```

1) `git checkout CheckLists`
2) Открыть редактор: `vim checklist.txt`
3) `i` - редактировать
4) The structure of a checklist:
   1) ID
   2) Environment
   3) Title
   4) Input parameters
   5) Expected result
   6) Status 

5. Сохранить и выйти: `:wq`

```
8. Запушить структуру на внешний репозиторий:
```
1) Добавить файл под гит: `git add checklist.txt`
2) Закоммитить файл: `git commit -m "Add checklist.txt file"`
3) Запушить файл на внешний репозиторий: `git push`

```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```

1) Зайти в репозиторию *"Branches"*
2) Нажать на кнопку *"Compare & pull request"*
3) Нажать на кнопку *"Create pull request"*
4) Нажать на кнопку *"Merge pull request"* -> *"Confirm request"*

```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
1) Зайти в GitBash
2) Перейти в ветку main: `git checkout main`
2) Синхронизировать внешнюю и локальную ветки: `git pull`







