
Необходимо использовать два обработчика событий: `document.onkeydown` и `document.onkeyup`.

Создадим множество `pressed = new Set()`, в которое будем записывать клавиши, нажатые в данный момент.

В первом обработчике будем добавлять в него значения, а во втором удалять. Каждый раз, как отрабатывает `keydown`, будем проверять -- все ли нужные клавиши нажаты, и, если да -- выводить сообщение.
