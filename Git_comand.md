# Краткая инструкция по командам GIT

## <font color = #07fff> Задание имени пользователя и электронной почты </font>

```sh
git config --global user.name "Ваше Имя"
git config --global user.email "Ваша почта"
```
*Имя пользователя и электронная почта нужны для указания автора коммитов*

## <font color = #07fff> Инициализация GIT </font>

```sh
git init
```
## <font color = #07fff> Добавление файла </font> 

```sh
git add file_name
```
*вместо file_name впишите имя файла для внесения в список отслеживаемых файлов*

## <font color = #07fff> Добавление коммита </font>

```sh
git commit -m "текстовая_метка"
```
*вместо слов текстовая_метка введите в кавычках вашу метку*

## <font color = #07fff> Просмотр статуса </font>

```sh
git status
```

## <font color = #07fff> Просмотр коммитов </font>

```sh
git log
```
краткая форма:

```sh
git log --oneline
```
графическое представление веток:
```sh
git log --graph
```
краткая графическая форма:
```sh
git log --oneline --graph
```

## <font color = #07fff> Переход между ветками или коммитами </font>

```sh
git checkout XXXXXXX
```
*ХХХХХХХ - имя ветки или идентификатор коммита*.

## <font color = #07fff> Создание новой ветки </font> 

```sh
git branch <branch_name>
```
*<branch_name> - имя ветки без скобок*

## <font color = #07fff> Слияние веток </font>

Перед слиянием нужно перейти в ту ветку, в которую планируется слияние.

```sh
git merge <branch_name>
```
*<branch_name> - имя ветки, которую нужно слить с текущей*