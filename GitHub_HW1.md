## GITHub. Homework 1

## JSON
#### 4. Create external repository named JSON 
Web Git Hub => "Repositories" Tab => [New] Button => Repository Name "JSON" => Click "Add a REDMI file" => [Create repository"] Button
#### 5. Clone JSON repository to local computer
git clone "https://github.com/DariaMartinovskaya/JSON.git"
#### 6. Create file “new.json” inside JSON repository
touch new.json
#### 7. Add the file to git
git add new.json
#### 8. Commit the file
git commit -m new.json
#### 9. Send the file to external GitHub repository
git push
#### 10. Edit content of “new.json” file - add the information about yourself (Full name, age, amount of pets, future desired salary). To be written in JSON format
vim new.json => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter" 
#### 11. Send changes to external repository
git commit -am + git push
#### 12. Create preferences.json file
touch preferences.json
#### 13. Add information about your preferences (favorite film, favorite series, favorite food, favorite season, country you would like to visit) into preferences.json file in JSON format
vim preferences.json => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter"
#### 14. Create sklls.json file and add information about skills to be learnt during the course in JSON format
touch skills.json + vim skills.json => i (edit mode) => [Input data] => "esc" + ":wq" + "Enter"
#### 15. Send 2 files to external repository at the same time
git add . && git commit -m "2Files" + git push
#### 16. Create bug_report.json file on external repository
Web Git Hub => Repositories => "JSON" => Click [Add file] Button => Choose "Create new file" => Name of the file: "bug_report.json" 
#### 17. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 18. Modify bug_report.json file on the web interface, add a bug report in JSON format
Choose bug_report.json => Edit this file button 
#### 19. Commit changes (save) changes on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 20. Synchronize external and local JSON repositories 
git pull

## XML
#### 21. Create external repository named XML
Web Git Hub => "Repositories" Tab => [New] Button => Repository Name "XML" => Click "Add a REDMI file" => [Create repository"] Button
#### 22. Clone XML repository to local computer
git clone https://github.com/DariaMartinovskaya/XML.git
#### 23. Create file “new.xml” inside XML repository
touch new.xml
#### 24. Add the file to git
git add new.xml
#### 25. Commit the file
git commit -m new.xml
#### 26. Send the file to external GitHub repository
git push
#### 27. Edit content of “new.xml” file- add the information about yourself (Full name, age, amount of pets, future desired salary). To be written in XML format
vim new.xml => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter" 
#### 28. Send changes to external repository
git add new.xml + git commit -m new.xml + git push
#### 29. Create preferences.xml file
touch preferences.xml
#### 30. Add information about your preferences (favorite film, favorite series, favorite food, favorite season, country you would like to visit) into preferences.xml file in XML format
vim preferences.xml => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter"
#### 31. Create sklls.xml file and add information about skills to be learnt during the course in XML format
touch skills.xml => vim skills.xml => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter" 
#### 32. Make a commit in one line
git add . && git commit -m "comment" 
#### 33. Send 2 files to external repository at the same time
git push
#### 34. Create bug_report.xml file on the web interface
Web Git Hub => Repositories => "XML" => Click [Add file] Button => Choose "Create new file" => Name of the file: "bug_report.xml"
#### 35. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 36. Modify bug_report.xml file on the web interface, add bug report in XML format
Choose bug_report.xml => Edit this file button
#### 37. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 38. Synchronize external and local XML repositories
git pull

## TXT
#### 1. Create external repository named TXT
Web Git Hub => "Repositories" Tab => [New] Button => Repository Name "TXT" => Click "Add a REDMI file" => [Create repository"] Button
#### 2. Clone TXT repository to local computer
git clone https://github.com/DariaMartinovskaya/TXT.git
#### 3. Create file “txt.xml” inside TXT repository
touch new.txt
#### 4. Add the file to git
git add new.txt
#### 5. Commit the file
git commit -m new.txt
#### 6. Send the file to external GitHub repository
git push
#### 7. Edit content of “new.txt” file - add the information about yourself (Full name, age, amount of pets, future desired salary). To be written in TXT format
cat => "Input data" => Ctrl + C
#### 8. Send changes to external repository
git add new.txt + git commit -m new.txt + git push
#### 9. Create preferences.txt file
touch references.txt
#### 10. Add information about your preferences (favorite film, favorite series, favorite food, favorite season, country you would like to visit) into preferences.txt file in TXT format
cat > preferences.txt => "Input data" => Ctrl + C
#### 11. Create sklls.txt file and add information about skills to be learnt during the course in TXT format
touch skills.txt; cat > touch.txt => "Input data" => Ctrl + C
#### 12. Make a commit in one line
git add . && git commit -m "2Files" 
#### 13. Send 2 files to external repository at the same time
git push
#### 14. Create bug_report.txt file on the web interface
Web Git Hub => Repositories => "XML" => Click [Add file] Button => Choose "Create new file" => Name of the file: "bug_report.txt"
#### 15. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 16. Modify bug_report.txt file on the web interface, add bug report in TXT format
Choose bug_report.txt => Edit this file button
#### 17. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 18. Synchronize external and local TXT repositories 
git pull

=============
## Main commands:

cd Git_intro

git clone https://github.com/DariaMartinovskaya/Terminal.git - создание копии (удаленного) репозитория

git add X.txt (добавление файла в область подготовленнных файлов)

git add . (отправить всё)

git status - отображение состояния рабочего каталога

git commit -m - сохранение версий ("замораживание историй"), где "-m" означает "message" (=комментарий)

git push - отправка локальной ветки на удаленный репозиторий

git commit -a -m (в одну команду можно, если файл "modified")

vim new.json. i - edit, esc + :wq - exit from edit mode

git pull - синхронизация внешнего и локального репозитория

git merge --abort - прерывание процесса слияния и восстановление конфликтующих файлов до стабильного состояния

git reset - восстановление конфликтующих файлов до стабильного состояния
