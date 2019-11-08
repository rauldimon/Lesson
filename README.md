# Lesson 2
## Задание 1 
```js
var letters = [];
var massage = "Backend As A Service".split(" ");
for ( var i = 0; i < massage.length; i++ ) {
    letters.push( massage[i] [0] );
}
console.log ( letters );

var a = letters.join('');
console.log (a);
```

## Задание 2

```js
var number = 0 ;
function getDataNow (number) {
  if ( typeof number === 'number')
    return new Date ().toLocaleString();
  else return (`Не верный тип данных`);
}
var exit = getDataNow(number);
console.log(exit); 
```

## Задание 3

Совсем не понял(((
