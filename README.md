# java_toy_shop

## Промежуточная аттестация
## Информация о проекте
Проект состоит из 2 частей:
Linux - Выполнить в командной строке
Программа на Java - Необходимо написать программу, для розыгрыша игрушек в магазине детских товаров.

Эти 2 части не взаимосвязанные. Т.е. не нужно с помощью программы на Java выполнять команды в Linux
 
*У кого не было курса по Linux – Пропускаем 1 часть по Linux. При сдаче проекта укажите это.
 
Подробное описание задач – ниже.
 
 
## Как сдавать проект
 
Первую часть по Linux можно сдавать скринами терминала, текстовым или PDF файлом и приложить к проекту и\или добавить на github. 
(У кого не было этого курса - пропускаем это задние)

Вторую часть программы на Java – выкладываем в отдельный общедоступный репозиторий Github
Программа должна запускаться и работать, ошибок при выполнении программы быть не должно.
 
 
## Задание 1
 
1)   Используйте команды операционной системы Linux и создайте две новых директории – «Игрушки для школьников» и «Игрушки для дошколят»
2)   Создайте в директории «Игрушки для школьников» текстовые файлы - «Роботы», «Конструктор», «Настольные игры»
3)    Создайте в директории «Игрушки для дошколят» текстовые файлы «Мягкие игрушки», «Куклы», «Машинки»
4)   Объединить 2 директории в одну «Имя Игрушки»
5)   Переименовать директорию «Имя Игрушки» в «Игрушки»
6)   Просмотреть содержимое каталога «Игрушки».
7)   Установить и удалить snap-пакет. (Любой, какой хотите)
8)   Добавить произвольную задачу для выполнения каждые 3 минуты (Например, запись в текстовый файл чего-то или копирование из каталога А в каталог Б).
 
 
 
## Задание 2
 
Необходимо написать программу – розыгрыша игрушек в магазине детских товаров.
Стараемся применять ООП и работу с файлами.
Если какой-то пункт не изучали и не знаете, как сделать, то можете сделать своим способом. Например, у кого в курсе не было ООП, то применяем списки\массивы\словари
 
Желательный функционал программы:
В программе должен быть минимум один класс со следующими свойствами:
id игрушки,
текстовое название,
количество
частота выпадения игрушки (вес в % от 100)
 
Метод добавление новых игрушек и возможность изменения веса (частоты выпадения игрушки)
Возможность организовать розыгрыш игрушек.
Например, следующим образом:
С помощью метода выбора призовой игрушки – мы получаем эту призовую игрушку и записываем в список\массив.
Это список призовых игрушек, которые ожидают выдачи.
Еще у нас должен быть метод – получения призовой игрушки.
После его вызова – мы удаляем из списка\массива первую игрушку и сдвигаем массив. А эту игрушку записываем в текстовый файл.
Не забываем уменьшить количество игрушек

К написанию программы можно подойти более творчески и делать так, как Вы поняли задание. Немного менять и отходить от примера выше.
