# **Задача 0.7. Строительство дорог**
*Имя входного файла: input.txt <br/>
Имя выходного файла: output.txt <br/>
Ограничение по времени: 1 с <br/>
Ограничение по памяти: 256 МБ*

Берляндия состоит из $n$ городов. Изначально все города изолированы, то есть между городами нету дорог.По очереди будут добавляться дороги между парами городов. Необходимо после каждой добавленной дороги узнать, какое количество компонент связности из городов получилось.

## **Формат входных данных**
Первая строка входного файла содержит два целых числа $n$ и $q$ ($1 \leqslant n, q \leqslant 500000$) — количество городов и запросов соответственно.Каждая из следующих $q$ строк содержит два целых числа $u$, $v$ — между какой парой городов будет построена дорога. В данной задаче между любой парой городов строится не более одной дороги, а для любого запроса справедливо $u \ne v$.

## **Формат выходных данных**
На каждый запрос второго типа необходимо вывести одно число — количество компонент связности в графе из городов.

# **Примеры**
> input.txt :<br/>
5 5<br/>
1 2<br/>
3 4<br/>
1 3<br/>
3 5<br/>
1 5<br/>
output.txt :<br/>
4<br/>
3<br/>
2<br/>
1<br/>
1<br/>