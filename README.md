# result.txt

Повесть временных лет

Я работала в Sublime Text

1. Как я удаляла эти пустые строки:

Сначала я просто удалаила эти пустые строки при помощи Регулярного вырожения : ^\n 

![alt text](https://github.com/wentkonoplya/result.txt/blob/master/1.1.png)

Потом оказалось, что в тексте есть еще пустые строки с пробелами, и наверное, от них тоже надо было избавиться, и я юзанула вот такое Регулярное Вырожение : ^\s 
![alt text](https://github.com/wentkonoplya/result.txt/blob/master/1.2.png)

2. Как я встретил вашу маму:

Чтобы найти все имена собственные, оканчивавшиеся на -слав, я использовала регулярное вырожение:

[А-Я][а-яѣ]+слав[а-яѣ]+

Всего упоминаний: 564

Например, в строке 55 на пике можно увидеть, что слово "выславше" не выделелось!
![alt text](https://github.com/wentkonoplya/result.txt/blob/master/2.png)

3. Упоминания Новгорода:

Использовал_а регулярное выражение: Нов.город+[^.?!;:-]

Всего упоминаний Новгорода нашела: 58
![alt text]

4. Бонус:

Использовал_а регулярное выражение: ([!,.;:"?-])

Заменила на: $1 (пробел)
![alt text](
https://github.com/wentkonoplya/result.txt/blob/master/бонус.png)
