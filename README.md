# fchars
Библиотека для рисования букв и цифр в canvas.
## Демо
https://gloagent.ru/category/blog/web/fchars.html
## Пример использования
```javascript
var canvas = document.getElementById("fchar"); //берем канвас
var ctx = canvas.getContext("2d");
canvas.width = canvas.offsetWidth; //адаптируем высоту и ширину
canvas.height = canvas.offsetHeight;
var chr = new FChars('fchar');
chr.paint_text('Gloagent fcharjs hello world +-^*#', ctx, 35, 'black', 20); //пишем текст красным цветом, где каждый "пиксель" размером в 80 (80*5 на символ) и добавляем отступы между символами в 10.
```
