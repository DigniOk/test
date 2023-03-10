# Инструкция для работы с MarkDown

## Выделение текста

Чтобы выделить текст курсировлм необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его дваойными звездочками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при это быть **полужирным**_

## Списки

Чтобы Добавить ненумерованные списки, нуобходимо пункты выделить звездочкой(*) или знаком +. Например, вот так:

* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы Добавить нумерованные списки, нуобходимо пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображения

Чтобы вставить изображение в текст достаточно написать следующее:
![GeekBrains](geek.jpg)

## Ссылки

Существует два варианта оформления ссылок. Первый - обычная вставка в текст:

[Первый вариант](https://gb.ru/ "GeekBrains")

[Второй вариант][2] - оформление ссылки в виде сноски. Когда в текст вставляется конструкция вида

[2]: https://gb.ru/

## Работа с таблицами

Вертикальные линии обозначают столбцы.

| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |

Внешние вертикальные линии (|) не обязательны и нужны только, чтобы сам код Markdown выглядел красиво.

## Цитаты

Если в начале строки поставить треугольную скобку (>), то Markdown превратит текст после неё в цитату. Внутри могут быть любые блоки: параграфы, заголовки или даже другие цитаты.

> Одна треугольная скобка
превращает в цитату несколько строк,
идущих друг за другом.

## Команды GIT

**git add**
  добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита. По умолчанию git commit использует лишь этот индекс, так что вы можете использовать git add для сборки слепка вашего следующего коммита.

**git status**
показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.

**git commit**
берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.

**git branch**
это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.

**git checkout**
используется для переключения веток и выгрузки их содержимого в рабочую директорию.

**git merge**
используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит.

**git log**
используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.

**git pull**
работает как комбинация команд git fetch и git merge, т.е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

**git push**
используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.


## Заключение

_Наконец то закончил!!!!_ 
**УРА УРА УРА**, _Я МОЛОДЕЦ_
>Отношения — это компромисс, умение прислушаться к другому человеку, понять его, объяснить себя, свои желания, отношения к миру, причины поступков. Молчать и дуться, решив, что всё понятно и так и «он должен осознавать, как неправ…» — ну просто детский сад какой-то — никто никому ничего не должен. Объясняй, проси объяснить, прощай, проси простить, разговаривай, только не уходи в тупик молчания и обид, нелепого и идиотского самолюбия.
