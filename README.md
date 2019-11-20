# Lesson 1
## Задание 1 

```js
var cashOfTickets ;
for (cashOfTickets= 0; cashOfTickets<=700 ; cashOfTickets+=100) {
 if(cashOfTickets>=660){
 console.log(cashOfTickets);
 }
}
alert("Денег на кино хватает, го за билетами!!!")
```
## Задание 2

```js
var name, password;

function movieRegistration() {
  return name = prompt("Введите Имя (минимум 3 символа)"), password = prompt("Введите Пароль (минимум 6 символов)")
}
do {
	alert ("Для регистрации заполните поля: Имя и Пароль");
  movieRegistration ();
} 
while ((typeof name === 'undefined' ||password === 'undefined' ) || (name.trim().length < 3 || password.trim().length < 6)) {
}
alert ("Регистрация успешна!!!")
```
