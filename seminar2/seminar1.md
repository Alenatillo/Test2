# Создание туториала по Git

## Как создать репозиторий

Чтобы создать репозиторий, неоходимо выполни следующую команду:

```
git init
```

## Как просмотреть состояние репозитория

Чтобы просмотреть
состояние 
репозитория, используйте 
следующую команду:

```
git status
```

## Как добавить файл на отслеживание

Чтобы добавить файл на отслеживание, используйте следующую команду:

```
git add <названиефайла.расширение>
```

## Как просмотреть историю всех коммитов

Чтобы просмотреть 
историю всех
коммитов, неоходимо выполни 
следующую команду:

```
git reflog
```
или же

```
git log
```

## Как добавить переключение между коммитом

Чтобы добавить переключение между коммитами, добавьте следующую команду:

```
git checkout
```

или же:

```
git switch
```

## Как просмотреть разницу между текущим файлом и закоммиченным файлом

Чтобы просмотреть 
разницу между 
текущим файлом и
закоммиченным 
файлом, выпоните следующую команду:

```
git diff
```

## Как изменить описание только последнего коммита

Для изменения **только** последнго коммита, выпоните 
следующую команду:

```
git commit --amend -m "Новое описание"
```


# Краткая инструкция по MarkDown

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа > .

This is a blockquote with two paragraphs. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак > ставится перед каждым
элементом цитаты, будь то абзац, заголовок или пустая строка:

This is a blockquote with two paragraphs. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные
цитаты:
This is a header.
Вложенная цитата.
Here's some example code:
return shell_exec("echo $input | $markdown
_script");

## Заголовки

## Исходный код

## Таблицы
