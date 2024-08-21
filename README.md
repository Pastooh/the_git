# Шпаргалка markdown

## Выделение текста

Вы можете выделять текст в markdown с помощью символов `_` или `*`. Например:

Пример _курсива_ и **жирного** текста.

## Заголовки

Заголовки можно создавать с помощью символа `#`. Чем больше `#`, тем меньше заголовок. Например:

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня

## Выделение кода

Чтобы выделить текст как код, поместите его в тройные кавычки "```". 

```
mkdir my_project
cd my_project
git init
ls -al
```

Это лишь некоторые функции markdown.
Больше информации на [GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Список основных команд по работе с git в консоли:
`git version` **тут понятно**<br>
`git init` **инициализация проекта в текущей папке**<br>
`git add .` **добавление всех файлов в папке в проект**<br>
`git status` **текущее состояние проекта**<br>
`git commit -m "Comment"` **подтверждаем изменения в репозиторий**<br>
`git config --global user.name "$USERNAME"` **Конфигурим подключение в конфиге git**<br>
`git config --global user.email "$USERMAIL"` **Конфигурим подключение в конфиге git**<br>
`git config --global init.defaultbranch "main"` **Меняем название дефолтной ветки** (Или можно было инициализировать проект при помощи команды `git init -b main`)<br>
`git config --list` **Проверяем переменные**<br>
`git remote add origin git@github.com:$USERNAME/$PROJECTNAME.git` **подключаем текущий репозиторий к удалённому. На Гитхаб должен быть прокинут ключ SSH**<br>
`git remote -v` **проверка подключения**<br>
`git push -u origin main` **публикуем в ветку main**<br>
`git push` **публикуем в удалённый репозиторий(default branch)**<br>
