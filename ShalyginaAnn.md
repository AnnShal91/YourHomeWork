# Инструкция по работе с GIT

 ## Создание и подготовка файла
 * Создаем папку на компьютере.
 * Команда git init - превращает папку в репозитарий
 * Создаем файл, используя кнопку "файл +" и даем ему название, обязательно добавляем расширение файла.
 * Около файла появлеяеется буква U (untract)
 * Команда git add -добавляем файл
 * Команда Git commit-m"N" Фиксирует текущее состояние документа. 

## Основные команды для работы

* git init - инииировать папку или файл
* git add - добавить файл
* git commit - фиксировать состояние файла
* git status - проверить текущее состояние файла
* git checkout - вернутся к ранее сохраненной версии документа
* git log - посмотреть историю комитов
* clear - очистить терминал
* git checkout master - перейти на главную ветку
* git diff - отследить разницу между версиями
* git branch - создать ветку
* git merge - слияние веток (находимся в той ветке, где хотим слияния)


## 4 шага работы в терминале

1. Внести изменения в документ
2. Сохранить изменения с помощью CTRL+S
3. git add добавляем версию
4. git commit -m "Name"  фиксируем комит и даем ему название.

Далее повторяем цикл.

## Особенности работы в MD

* "#" - добавить заголовок
* "##" - заголовок второго уровня
* 1.,2.,3., - нумерованный список
*  "*" - ненумерованный список





#  Второй семинар(2)
## Работа с ветками

## 1. Создание веток
  Git branch - команда, создающая ветки

## 2. Слияние веток

* git merge branch_name - команда, осуществляющая слияние между текущей веткой и branch_name

## 3. Конфликты при слиянии
* при слиянии веток, по-разному фиксирующих изменения одних и тех же областей проекта, возникает конфликт слияния.


Fast Forard -  обновление информации в базовой ветке по принципу "один догоняет другого" 

Автоматическое слияние ОРТ  - слияние двух разных веток, в которых комиты созданы и непротиворечат друг другу. 