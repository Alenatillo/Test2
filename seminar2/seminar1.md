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

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:

```
# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6
```

В декоративных целях заголовки можно «закрывать» с
обратной стороны.

## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале
каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более
удобный способ: ставим по три апострофа (на букве Ё) до и после
кода. Также можно указать язык исходного кода.

```HTML
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count" class="publ
isher-nav-color" data-nav="conversation">
 <span class="comment-count">0 комментариев</
span>
 <span class="comment-count-placeholder">Комм
ентарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logou
t">
 <a href="#" class="dropdown-toggle" data-toggl
e="dropdown">
 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```
```php
<?php
$test = '<h2>Привет Всем, я Тефтелька!</h2>

?>
<div><?=$test |?></div>
```

## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML.

## Картинки

## Зачеркивание
