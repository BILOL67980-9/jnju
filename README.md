# Что такое Мвссив(Array) 

***Объекты позволяют хранить данные со строковыми ключами. Это замечательно.***

***Но довольно часто мы понимаем, что нам необходима упорядоченная коллекция данных, в которой присутствуют 1-й, 2-й, 3-й элементы и т.д. Например, она понадобится нам для хранения списка чего-либо: пользователей, товаров, элементов HTML и т.д.***

***В этом случае использовать объект неудобно, так как он не предоставляет методов управления порядком элементов. Мы не можем вставить новое свойство «между» уже существующими. Объекты просто не предназначены для этих целей.***

## Для хранения упорядоченных коллекций существует особая структура данных, которая называется массив,

```java script
let arr=[1,2,3,4,5]
consol.log(arr) // [1,2,3,4,5]
``` 
## A также можно изменить элементы масива 

```java script
let arr=[1,2,3,4,5]
let arr[1]=3
consol.log(arr) // 1,3,3,4,5
```

## Сколько Методов в Array ?

***В Array много методов но 12 из них это основные***

**это**

> **push**
> **pop**
> **unshift**
> **shift**
> **toString**
> **indexOf()**
> **includes()**
> **concate**
> **slice**

![image](https://github.com/user-attachments/assets/b2e75a3e-22b1-4edf-a62d-e59cba48dc8e)


## Что такое ***push*** ?

## **1. some()**

**Этот метод проверяет, удовлетворяет ли какой-либо элемент массива условию, заданному в передаваемой функции. Он вернет значение true, если хотя бы один элемент совпадет с проверяемой функцией, и значение false — если нет.**

## **2. reduce()**

**Этот метод принимает функцию, которая имеет в качестве аргумента аккумулятор и значение. Он применяет функцию к аккумулятору и каждому значению массива, чтобы в результате вернуть только одно значение.**

## **3. every()**

**Этот метод проверяет, удовлетворяют ли все элементы массива условию, заданному в передаваемой функции. Он вернет значение true, если каждый элемент совпадет с проверяемой функцией, и значение false — если нет**

## **4. map()**

**Этот метод принимает функцию в качестве параметра и создает новый массив с результатом вызова указанной функции для каждого элемента массива. Он всегда будет возвращать одинаковое количество элементов.**

## **5. flat()**

**Этот метод принимает в качестве аргумента массив массивов и сглаживает вложенные массивы в массив верхнего уровня. Обратите внимание, что этот метод работает только для одного уровня.**


## **6. pop**

**Этот метод проверяет, удовлетворяет ли какой-либо элемент массива условию, заданному в передаваемой функции. Он вернет значение true, если хотя бы один элемент совпадет с проверяемой функцией, и значение false — если нет.**

## **7. push**

**Этот метод принимает функцию, которая имеет в качестве аргумента аккумулятор и значение. Он применяет функцию к аккумулятору и каждому значению массива, чтобы в результате вернуть только одно значение.**

## **8. indexOf()**

**Этот метод проверяет, удовлетворяют ли все элементы массива условию, заданному в передаваемой функции. Он вернет значение true, если каждый элемент совпадет с проверяемой функцией, и значение false — если нет**

## **9. index()**

**Этот метод принимает функцию в качестве параметра и создает новый массив с результатом вызова указанной функции для каждого элемента массива. Он всегда будет возвращать одинаковое количество элементов.**

## **10. slice()**

+ **Этот метод принимает в качестве аргумента массив массивов и сглаживает вложенные массивы в массив верхнего уровня. Обратите внимание, что этот метод работает только для одного уровня.**

# **Метод колбек**

> map()
> forEach()



