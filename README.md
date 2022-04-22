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

![Función](data:image/jpeg;base64,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)

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