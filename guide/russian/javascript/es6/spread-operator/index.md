---
title: Spread Operator
localeTitle: Оператор распространения
---## Оператор распространения

Оператор распространения ( `...` ) позволяет получить элементы коллекции.

Одним из наиболее используемых комм является использование объектов `Node` при использовании селекторов запросов в браузере, чтобы сделать их итерабельными объектами массива:

```javascript
const paragraphs = document.querySelectorAll('p.paragraph'); 
 const arr = [...paragraphs]; 
```

Другое использование оператора спредов для конкатенации массива:

```javascript
const arr_1 = [1, 2, 3, 4] 
 const arr_2 = [5, 6, 7, 8] 
 const arr_final = [...arr_1, ...arr_2] 
 // arr_final = [1, 2, 3, 4, 5, 6, 7, 8] 

```