# команды git 
## создание репозитория 
`git config --global user.name "имя_пользователя"`
>ввод имени пользователя 
```
git config --global user.email "свой_email"
```
>ввод почты пользователя
```
cd "ссылка на папку"
```
>укзывает путь к папке
```
pwd
```
>показывает текущую папку
```
ls -la
```
>показывает содержимое папки
```
git init
```
>создает репозиторий в выбранной папке
```
git config --list
```
>отображает введеные данные
## команды при изменении в репозитории
```
git add
```
>добавляет файлы из репозитория в индекс
```
git status
```
>показывает состояние и изменения репозитория
```
git commit
```
>добавляет комментарий к измененному файлу
```
git log
```
>показывает историю коммитов
```
git clone
```
>загружает репозиторий с сервера если его у тебя нет
## перенос репозитория на сайт
```
git remote add origin "сайт"
```
>связывает сайт с нужной папкой 
```
git push -u origin main
```
>добавляет всё изменения в папке на сайт
## работа веток в репозитории
```
git branch -M main
```
>создает основную ветку
```
git remote -v
```
>просмотр в какой вы находитесь ветке 
```
git remote rm origin
```
>отлючение от репозитория, ветки
```
git checkout -b branch1
```
>в первый раз пишется так и она создаёт новую временную ветку и сразу переходит туда, во второй раз пишется без -b и просто переход
```
git checkout main
```
>чтобы вернуться обратно в ветку
```
git branch
```
>показывает сколько веток и выделит ту ветку, в которой вы находитесь
```
git merge "название ветки"
```
>слияние веток
```
git branch -d "название ветки"
```
>удаление ветки
