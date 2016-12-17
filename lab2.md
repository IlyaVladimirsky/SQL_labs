
##Описание базы данных

Для выполнения заданий используется база данных книготорговой компании pubs, которая включает три таблицы, определяющие сущности: 
таблица authors определяет авторов, таблица publishers – издателей, titles – сами книги, titleauthor – задает отношение между 
таблицами titles и authors. Связь между таблицами titles и publishers определяется столбцом pub_id в этих таблицах. Ниже приводится 
описание полей таблиц.

Таблица authors:
- au_id: идентификатор автора
- au_lname:	фамилия автора
- au_fname:	имя автора
- phone: номер телефона
- address: адрес(улица, дом, квартира)
- city:	город проживания
- state: штат проживания
- zip: код
- contract:	наличие контракта

Таблица publishers:
- pub_id:	идентификатор издательства
- pub_name:	название издательства
- city:	город
- state: штат
- country: страна

Таблица titles:
- title_id:	идентификатор книги
- title: название книги
- type:	тип книги
- pub_id:	идентификатор издательства
- price: цена
- advance: стоимость предварительной продажи
- ytd_sales: число книг, проданных в текущем году
- notes: замечания
- pubdate: дата опубликования

Таблица titleauthor:
- au_id	идентификатор названия книги,
- title_id	идентификатор книги,
- au_ord	порядок автора вasdf названии книги
- royaltyper	авторский гонорар

В столбцах type таблицы titles используются следующие типы книг:
- business:	книги по бизнесу
- mod_cook:	книги по современной кулинарии
- popular_comp:	книги по компьютерной тематике
- psychology:	книги по психологии
- trad_cook: книги по традиционной кулинарии
- UNDECIDED: неопределенный тип книги

В столбце state таблиц authors и publishers используются следующие обозначения административных единиц:
- CA	Калифорния
- DC	округ Колумбия
- IL	штат Иллинойс
- IN	штат Индиана
- RS	штат Канsdfзас
- MD	штат Мэриленд
- MA	штат Массачусетс
- MI	штат Мичиган
- NY	штат Нью-Йорк
- OR	штат Орегон
- TN	штат Теннеси
- TX	штат Техас
 -UT	штат Юта

Домен городов (city) включает города: Ann Arbor, Berkeley, Boston, Chicago, Corvallis, Colevo, Dallas, Gary, Lawrence, Menlo Park, Munchen, Nashville, New York, Oaklend, Palo Alto, Paris, Rockvill, Salt Lake City, San Francisco, San Jose, Vacaville, Walnul Creek, Washington. 
