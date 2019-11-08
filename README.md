## Lesson-2 homework

###  Required
```js
var letters = [];
var row = 'Backend As A Service'.split(" ");
row.forEach(function(el) {return letters.push(el[0])
});
console.log(letters);
console.log(letters.join(''));
```
#### здесь я пробую стрелочную функцию на вкус)))
```js
var letters = [];
var row = 'Backend As A Service'.split(" ");
row.forEach((el) => letters.push(el[0]));
console.log(letters);
console.log(letters.join(''));
```
### Additional 

```js
var a = prompt ( "Введите число" );
var date = new Date;
        
function showSymbol(symbol) {
  if ( !isNaN(symbol) )
      console.log( date.toLocaleString() );
  else console.log('Неверный тип данных');
}

showSymbol(a);
```
### второй способ
```js

var a = prompt( 'Введите число' );
var date = new Date;

function showSymbol(symbol) {
  if( +symbol )
     console.log( date.toLocaleString() )
   else console.log( 'Неверный тип данных' );
}

showSymbol( a );

```

### Последнее задание не сделала, еще посижу, пока тяжело
