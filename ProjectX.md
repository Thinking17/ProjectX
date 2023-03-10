# *Начало работы в Visual Studio Code. (Git)*
## Как только все установлено и настроено делаем следующее:

<font color="red" size=2 >**Примечание (все команды прописываеются без ковычек)**</font>
 

*1. Создаем файл с расширением (например .md) в котором будете работать.*

*2. Инициализируем/создаем репозиторий в системе. Для этого прописываем в консоли* "git init".

Теперь Git отслеживает все изменения вашего проекта. 

*3. Далее необходимо создать свой первый commit :*

* Команда "git add <имя файла>" - добавляет все файлы проекта в ваш будющий commit
* Команда "git commit -m "<коментарий>" (КОМЕНТАРИЙ ПИШЕМ В КОВЫЧКАХ) - соответственно добавляет ваш первый commit. 

Замечательно! Мы создали наш первый репозиторий c привязанным к нему commit.

#  *Инструкции при работе с Markdown.*

## Выделение текста (как обособлять)

* Чтобы выделить текст курсивом необходимо обрамить его звездочками(*) или знак нижнего подчеркивания (_). Например *вот так* или _вот так_. 

* Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками(**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__. 

* Чтобы сделать зачеркнутый текст, необходимо обрамить его двойным знаком (~~). 
Наример, ~~Вот так~~

Альтернаивыне способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _**текст может курсивным и при этом полужирным**_.

## Списки 

Чтобы добавить ненумерованные списки, необходимо пунткты выделить звездочкой(*) или знаком (+). Например, вот так: 
* Элемент 1 
* Элемент 2 
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
Наприме, вот так:

1. Первый пункт 
2. Второй пункт 

## Работа с таблицами

Чтобы составить самую простую блицу не обходимо вставить пунктирную линию после первой строки.
И отделить каждый столбец знаком ( | ). 

Например:

| This is a Table      | This is a Table      | This is a Table |
| -------------------- | -------------------- |-----------------| 
| 100                  | 50                   |80               |
| 30                   | 60                   |90               |

Чтобы выровнять столбцы можно поставить знак ( : )

Например:

| This is a Table      | This is a Table      | This is a Table |
| :------------------- | --------------------:|:---------------:| 
| 100                  | 50                   |80               |
| 30                   | 60                   |90               |



## Работа с изображениями 

Изображение должно находится в вашей рабочей папке.

Чтобы вставить изображения в текст, достаточно написать следующее ![коментарий](название файла) :

![Это красивая рука](Tastatur.png)
 
## Цитаты

Чтобы добавить цитату достаточно вначале поставить знак (<) Например:

> Что разум человека может постигнуть и во что он может поверить, того он способен достичь.

Блок цитирования обычно отображается с отступом и имеет другой цвет фона.

## Алгоритм создания запроса на изменения данных(pull request)

1. Форкнуть рипозиторий(fork)
2. Делаем клон форкнутого репозитория к себе на компьютер(clone)
3. Создаем новую ветку и добавляем изменения 
4. git push --set-upstream origin request
5. Подредактировать pull requst на github