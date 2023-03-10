# ИНСТРУКЦИЯ ПО РАБОТЕ С MARKDOWN

##  1. ВЫДЕЛЕНИЕ ТЕКСТА 
Чтобы выделить текст **жирным** необходимо записать так: две * перед словом и после, которое хотим выделить.

Чтобы выделить текст *курсивом* необходимо записать: одна * перед словом или выражением,которое хотим выделить.

Если # поставить в начале строки, выделиться заголовок. 

Чтобы текст выделить ***жирным и курсивом*** одновременно: три * без пробела до и после слова или выражения.

Чтобы текст или ~~слово~~ зачеркнуть: нужно перед ними поставит два знака ~ 

Если писать перед словом или предложением span style="color:blue", заключенные в <>, то можно выделить текст цветом <span style="color:red">например так, <span style="color:blue"> или так,<span style="color:green"> и даже так.

Апострофом  можно выделить текст или слово, если обрамить. `Например так`

## 2. СПИСКИ
Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные) списки.
Для формирования упорядоченный списков в качестве маркеров используются числа с точкой.

1.
2. 
3.

Маркеры списков обычно начинаются с начала строчки, однако могут быть сдвинуты, но не более, чем на три пробела. За маркером должен следовать пробел. Если использовать *, -, +, получиться так:

* так
* и так далее


## 3. РАБОТА С ИЗОБРАЖЕНИЕМ

Если заранее закинуть картинку в папку, с которой работаем, где находится наш текущий файл, то написать нужно: *! в таких скобках [] текст и в круглых ()* название файла, у меня получилось ![Клубника] (i.jpg), только пробел между скобками не нужен.

![Клубника](i.jpg)

Если файл в другой папке, в круглых скобках указывать URL -адрес изображения (путь).

## 4. ССЫЛКИ

Markdown поддерживает два стиля оформления ссылок:

* гиперссылка с немедленным указанием адреса;
* гиперссылка - сноска
 

[ссылка](https://gb.ru/) без заголовка. текст "ссылка" заключается в квадратные [] скобки, а адрес страницы сразу без пробела в () круглые.

[ссылка](https://gb.ru "Школа GigBrains") с тайтлом. В круглых скобках к адресу добавить в кавычках название.

ссылка <https://gb.ru/> безанкорная. Ссылку заключить в <>.

## 5. ТАБЛИЦЫ 

Обязательно требуют заголовок и настройки выравнивания (второй строкой). Выравнивание задается двоеточием. Колонки задаются вертикальными палками (|).

| 1 | 2 | 3 |
|---|:-:|--:|
|100|200|300|
|1000|2000|3000|

## 6. ЦИТАТЫ

Для обозначения цитат используется знак "больше" ">". Его можно вставлять как перед каждой строкой цитаты, так и перед первой строкой параграфа. Также можно создавать вложенные цитаты (цитаты внутри цитат). Пример:

> первая цитата

> вторая 

Вложенная:
> Начало
>> Затем
>>>Продолжение
>>>>И так далее

# ЗАКЛЮЧЕНИЕ

Markdown - удобочитаемый язык разметки. Его можно открывать и изменять в любом редакторе текста. Широко используется для написания документаций и README - файлов.

