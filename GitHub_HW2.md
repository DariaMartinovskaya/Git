## GITHub. Homework 2

#### 1. Create branches for on the local repository
git branch 

- git branch Postman

- git branch Jmeter

- git branch CheckLists

- git branch BugReports

- git branch SQL

- git branch Charles

- git branch MobileTesting

#### 2. Push all branches to remote repository
git push -u origin --all
#### 3. Create text document with the structure of bug report in the BugReports branch
git checkout BugReports => vim BugReport.txt => i + "Text" + esc + :wq
#### 4. Push structure of bug report to external repository
git add BugReport.txt => git commit -m BugReport.txt => git push 
#### 5. Merge BugReports branch to Main branch
git checkout main => git merge BugReports
#### 6. Push main to external repository
git push
#### 7. Create the structure of bug report in CheckLists branch
git checkout CheckLists => vim Checklist.txt => i + "Text" + esc + :qw
#### 8. Push structure to external repository
git add Checklist.txt => git commit -m Checklist.txt => git push
#### 9. Create Pull Request of CheckLists branch to main on external repository
Web Git Hub => Click [Compare & pull request] Button => Click [Create ull request] Button => Click [Merge pull request] Button => Click [Confirm merge] Button
#### 10. Synchronize external and local repositories
git checkout main => git pull

=============
## Main commands: 

git clone - создание копии (удаленного) репозитория

git checkout - позволяет переключаться между последними коммитами (ветками)

git checkout -b - создание ветки и переключение на нее

git pull - синхрониация внешнего и локального репозитория

git push - отправка локальной ветки на удаленный репоиторий

git push -u origin master / main / --all - связь между той веткой, в которой вы находитесь, и веткой master на удалённом сервере (-u = origin master - по умолчанию)

git push -u origin new_branch - отправка новой ветки в удаленный репозиторий

git push --delete origin existing_branch - удаление удаленной ветки

git commit -m - сохранение версий ("замораживание историй")

git status - отражает состояние текущего каталога

git branch - показывает какие ветки есть и в какой ветке мы сейчас находимся

git branch -d "branch's name" - удаление ветки

git fetch origin "branch's name" - возврат удаленной ветки

git merge - выполняет слияние отдельных направлений разработки, созданных с помощью команды git branch

git merge --abort - прерывание слияния в случае конфликта

git reset - восстановление конфликтующих файлов до стабильного состояния при конфликте

git restore <file> - отмена измененного файла

git rebase branch_name - перебазирование (это процесс объединения или перемещения последовательности коммитов на новый родительский снимок)

rm -rf .git - удалить репозиторий локально

Discrepancies between external and local repositories: git checkout main => ls -la => git fetch (if there are changes) => git pull
