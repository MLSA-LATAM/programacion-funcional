# Introducción a la programación funcional

| Recurso | Link |
| ------- | ---- |
| Presentación | [👨‍🏫](https://www.canva.com/design/DAE9uKCYLaA/-fAtzpkxqSciWpnMJLR0Eg/view?utm_content=DAE9uKCYLaA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) |
| Video | [📹](https://www.facebook.com/100815372125933/videos/1002122680699072/)

# Conceptos e ideas Importantes

## Paradimas declarativos vs imperativos
## Imperativos
> Una secuencia de operaciones a realizar. Especificamos la secuencia de operaciones utilizando condicionales o ciclos (if, for, while, etc.)

**Algunos lenguajes imperativos**:

![Python](https://img.shields.io/badge/-Python-white?logo=python&logoColor=3776AB&style=for-the-badge)

![C++](https://img.shields.io/badge/-C++-white?logo=c%2B%2B&logoColor=00599C&style=for-the-badge)

![JavaScript](https://img.shields.io/badge/-JavaScript-white?logo=javascript&logoColor=F7DF1E&style=for-the-badge)

![PHP](https://img.shields.io/badge/-PHP-white?logo=php&logoColor=777BB4&style=for-the-badge)

## Declarativos:
> Se especifica el resultado deseado, no cómo lograrlo.

Algunos ejemplos de lenguajes declarativos:

![Clojure](https://img.shields.io/badge/-Clojure-white?logo=clojure&logoColor=5881D8&style=for-the-badge)

![Haskell](https://img.shields.io/badge/-Haskell-white?logo=haskell&logoColor=5D4F85&style=for-the-badge)

![SQL](https://img.shields.io/badge/-SQL-white?logo=mysql&logoColor=4479A1&style=for-the-badge)

![Erlang](https://img.shields.io/badge/-Erlang-white?logo=erlang&logoColor=A90533&style=for-the-badge)

Los diferentes lenguajes de programación declarativos pueden, a su vez, dividirse en dos paradigmas: lenguajes de programación **funcional** y lenguajes de programación **lógica**.


## Programación Funcional

> La programación funcional es un paradigma de programación en el que tratamos de vincular todo en el estilo de **funciones matemáticas puras**. Utiliza *expresiones* en lugar de *statements*.

Se basa en el **cálculo lambda**

## Cálculo Lambda

> Es un sistema formal diseñado para investigar la definición de función, la noción de aplicación de funciones y la recursión. Diseñado por Alonzo Church y Stephen Kleene

## Funciones

> Definición *Matemática*: regla que asigna a cada elemento de un primer conjunto un único elemento de un segundo conjunto.

> Definición en programación: bloque de código que realiza alguna *operación*. Toma uno o más **argumentos** y calcula un resultado.

Ejemplos de funciones en Python

1. Función que toma un parámetro (name) y regresa un mensaje "Hello Daniel", por ejemplo.
```python
def hello(name:str)->str:
    return "Hello, "+name
```

2. Función que suma dos números
```python
def add(n1:int, n2:int)->int:
    return n1+n2
```

3. Función que suma los valores de un array o lista:
```python
def add_array(array:List[int])->int:
    total:int=0
    for element in array:
        total+=element
```

Pasemos a un lenguaje diferente, veamos las funciones anteriores en *Haskell*:

1. Función que regresa un mensaje de Hello y un nombre que pase:
```haskell
hello name = "Hello, "++name
```

2. Función que suma dos números
```haskell
add n1 n2 = n1+n2
```

3. Función que suma los valores de un array o lista:
```haskell
Con Prelude
sum [1..5] -> [1, 2, 3, 4, 5]
sum myLista

Recursividad
sumList :: (Num a) => [a] -> a
sumList [] = 0
sumList (x:xs) = x + sum' (xs)
```

## Funciones Puras
P:

> Siempre devuelve el mismo *resultado* para los mismos valores de **argumento** y no tiene *efectos secundarios* como modificar un argumento (o variable global).

Q:

> Facilidad de escritura para aplicaciones *paralelas/concurrentes*

![Tex Implicación](https://latex.codecogs.com/svg.image?p\rightarrow&space;q)




# RECURSOS PARA APRENDER PROGRAMACIÓN FUNCIONAL

* [Functional Programming in Haskell: Supercharge Your Coding](https://www.futurelearn.com/courses/functional-programming-haskell)
* [Functional Programming in Erlang](https://www.futurelearn.com/courses/functional-programming-erlang)
* [Functional Programming Principles in Scala](https://es.coursera.org/learn/scala-functional-programming)
* [HackerRank in Haskell](https://www.classcentral.com/course/youtube-haskellrank-59641/classroom)
* [Haskell for Beginners](https://www.classcentral.com/course/youtube-haskell-for-beginners-59640/classroom)
