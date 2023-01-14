# MarkDown
>sintax MD files


# Описание

----------------
* [Аттрибуты шрифта](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%B0%D1%82%D1%82%D1%80%D0%B8%D0%B1%D1%83%D1%82%D1%8B-%D1%88%D1%80%D0%B8%D1%84%D1%82%D0%B0)
* [Заголовки](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%B7%D0%B0%D0%B3%D0%BE%D0%BB%D0%BE%D0%B2%D0%BA%D0%B8)
* [Ссылки](https://github.com/T0kua/MarkDown/edit/main/README.md#%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B8)
* [Изображения](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F)
* [Цитаты](https://github.com/T0kua/MarkDown/edit/main/README.md#%D1%86%D0%B8%D1%82%D0%B0%D1%82%D1%8B)
* [Списки](https://github.com/T0kua/MarkDown/edit/main/README.md#%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D0%B8)
*  * [Не нумерованный список](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%BD%D0%B5-%D0%BD%D1%83%D0%BC%D0%B5%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9-%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA)
*  * [Нумерованный список](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%BD%D1%83%D0%BC%D0%B5%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9-%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA)
* [Вставка примера кода](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%B2%D1%81%D1%82%D0%B0%D0%B2%D0%BA%D0%B0-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D0%B0-%D0%BA%D0%BE%D0%B4%D0%B0)
## Аттрибуты шрифта

------------------
`*текст*` ИЛИ `_текст_` > *Курсивный текст*

`**текст**` ИЛИ `__текст__` > **жирный текст**

`~~текст~~` > ~~Зачеркнутый текст~~

`---` ИЛИ `***` > горизонтальная линия

-----------

## Заголовки

`# Заголовок первого уровня` >  # Заголовок первого уровня

`## Заголовок второго уровня` > # Заголовок второго уровня

`### Заголовок третьего уровня` > # Заголовок третьего уровня

```
Заголовок первого уровня
=======================

Заголовок второго уровня
-----------------------
```
---------------------
## Ссылки

`[text](link)` > [описание](https://github.com/T0kua/MarkDown/edit/main/README.md#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5)

-------------------------

## Изображения
`![image](link)` 
image - текст который отобразиться в случае ошибки загрузки

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSENbYO5Exs8Owe4qBMW8mi9SKQFYwPf3tS0n69jQyxgA&s)

-----------------------
## Цитаты

`> любовь - это непреодолимое желание быть непреодолимо желаемым` 
> любовь - это непреодолимое желание быть непреодолимо желаемым

количество знаков >(больше) указывает на количество вертикольных полос

`>> на свете много правды , а истинна одна`
>> на свете много правды , а истинна одна

---------------------
## Списки

### Не нумерованный список:

~~~
* Пункт 1
* * пункт 1.2
* Пункт 2
~~~
* Пункт 1
* * пункт 1.2
* Пункт 2
-------------------------
### Нумерованный список:

~~~
1. Пункт 1
2. пункт 2
3. Пункт 3
~~~
1. Пункт 1
2. пункт 2
3. Пункт 3

-----------------------
## Вставка примера кода

`print("hello world")`  > /print("hello world")/

!вместо /(слеша) нужно использоватать знак апострофа

!вместо .(точки) нужно использоватать пробела
```
#with python3
import rangom
if (random.randint(0,100) > 10 :
    print("A")
```

///
#with python3

import rangom

if (random.randint(0,100) > 10 :

....print("A")
    
///
