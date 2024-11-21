# js_base-scripts

"use strict"; 
/* строгий режим современного JS кода */

// Правилы и типы названия переменных
const vehicleBodyWidth = 5000;
const vehicleBodyLength = 4000;

console.log("Ширина кузова автомобиля: " + vehicleBodyWidth + ', длина: ' + vehicleBodyLength);

// Request
// data
// response

// snake_case
// UPPER_SNAKE_CASE
// Kebab-case
// PascalCase для названия скриптов


const COLOR_RED = '#FFF'; 
/* общее название для переменной const COLOR_RED (кодом не читаемся) */

// ДЗ
const userName = "John";
let userNumber = 25;
userNumber = 24;

console.log(userNumber);

// Классификация типа данных в JS
// Простой тип данных:
let number = 4.6;

console.log(-4/0);
console.log('string' * 9);

const persone = "5";

const bool = true; 
/* булиновое значение true or false / как ответ на вопрос */

/* console.log(something); */

/* let und; 
console.log(und); */

// Объекты (синтаксис фигурных скобок):

const obj = {
    name: "John", /* свойства объекта */
    age: 25,
    isMarried: false
};

/* console.log(obj.name); */

console.log(obj["name"]); 
/* можно использовать квадратные скобки с кавычками внутри*/

/* Массив частный случай объекта */
                0          1         2
let arr = ['plum.png', 'orange.jpg', 6, 'apple.bmp', {}, []]
console.log(arr[1])
/* счет элементов начинается нуля */

const arr = [1, 2, 3]; 
/* arr его элементы и их перечисление */

const arr = ['a', 'b', 'c'];

arr[10] = '3456';

console.log(arr[10]);

/* вложенная структура arrObj */
const arrObj = {
    0: 'a',
    1: 'b',
    2: 'c',
    abc: {
        df: [{}, {}],
        def: {

        }
    }
};

const b = 'b'; /* создает переменную b */

arrObj.b = '1234'; 
/* значение еще не созданного свойства b */
/* arrObj[b] = '1234'; второй вариант */

console.log(arrObj['b']);
console.log(arrObj.b);

const obj = {a: 1, b: 2}; /* ключ / его значение */

const obj = {
    Anna: 500,
    Alice: 800
    /* объект его значение в виде obj */
};


