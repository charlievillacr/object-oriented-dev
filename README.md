# Programación Orientada a Objetos (POO)

- Simplifica la programación.
- Viene de la metodología: "Orientación a objetos".
- Surge a partir de los problemas que tenemos y necesitamos plasmar en código.

## Clase Num.4 URL

[Paradigma Orientado a Objetos](https://platzi.com/clases/1474-oop/16670-paradigma-orientado-a-objetos/)


## Paradigma

- Teoría que suministra la base y modelo para resolver problemas.


## Compuesto de 4 Elementos

1. Clases 
2. Propiedades
3. Métodos
4. Objetos

## 4 Pilares

1. Encapsulamiento
2. Abstracción
3. Herencia
4. Polimorfismo

## Lenguajes orientados a objetos

1. JavaScript
2. Python
3. Java
4. PHP

5. C++
6. C#
7. Ruby
8. Perl
9. Kotlin


## Java
- Orientado a Objetos natiralmente.
- Android
- Server Side
<!-- Buscar cursos de programación funcional -->
- Extensión: .java

## PHP
- Lenguaje interpretado.
- Pensado para la web.

## PYTHON

- Diseñado para ser fácil de usar
- Múltiples usos: Web, Server Side, Análisis de Datos, Machine Learning.
- Extensión: .py

## JavaScript

- Lenguaje interpretado
- Orientado a 

## Diagramas de Modelado / Object Modeling Techniques (O.M.T.)
- OMT since 1991 (Deprecated)
- Metología para el analisís orientado a objetos.



## Unified modeling Language (UML) 
- Es un lenguaje estandar de modelos de sistemas orientados a objetos.
- Plasmar nuestro analisis en un grafico.
- UML: Unified Modeling Languaje (Lenguaje de Modelado Unificado).

1. Clases
2. Casos de Uso
3. Objetos
4. Actividades
5. Iteracion
6. Estados
7. Implementación

<!-- Investigar más sobre Ingeniería de Software -->

## Ejemplo de Entregable: Modelo UML del Proyecto
- Una manera gráfica de represenra una situación.
<!-- UML is King -->


## Las clases
- Se representan así
|------------------------------------|
|               Clase                |
|------------------------------------|
| + attribute1:type = defaultValue   |
| + attribute2:type                  |
| - attribute3:type                  |
|------------------------------------|
| + operantion1(params):returnType   |
| - operation2(params)               |
| - operation3()                     |
|------------------------------------|


- En la parte superior de colocan los atributos o propiedades, y debajo las operaciones de la clase. Notarás que el primer caractér con el que empiezan es sun íbolo. Este denotará la visibilidad del atributo o método, esto es un termino que tiene que ver Encapsulamiento y veremos más adelante a detalle.

## Estos son los niveles de visibilidad que puedes tener:

- private
+ public
# protected
~ default

- Una forma de representa las relaciones que tendrá un elemento con otro es a través de la flechas en UML, y aquí tenemos varios tipos, estos son los más comúnes:

## Asociación

====>

## MODULARIDAD

- La modularidad va muy relacionada con las clases y es un principio de la Programación Orientado a Objetos y va de la mano con el Diseño Modular que significa dividir un sistema en partes pequeñas y estas serán nuestros módulos pudiendo funcionar de manera independiente.

### La modularidad de nuestro código nos va a permitir

- Reutilizar código
- Evitar colapsos
- Hacer nuestro código más mantenible
- Legibilidad
- Resolución rápida de problemas
- Una buena práctica es separando las clases en archivos diferentes.

<!-- DIVIDE & VENCERÁS -->


## CLASE

- Modularidad
- Divide el programa en diferentes partes o módulo/ clases.
- Separar las clases en archivos.


<!-- Próxima Clase - Diagramas UML -->

## OBJETOS

- Los Objetos son aquellos que tienen propiedades y comportamientos, también serán sustantivos.

<!-- Siempre tienen: Propiedades y comportamientos -->

<!-- Identificar los objetos -->

### Pueden ser Físicos o Conceptuales

- Las Propiedades también pueden llamarse atributos y estos también serán sustantivos. Algunos atributos o propiedades son nombre, tamaño, forma, estado, etc. Son todas las características del objeto.

- Objeto fisico: manzana

- Los Comportamientos serán todas las operaciones que el objeto puede hacer, suelen ser verbos o sustantivos y verbo. Algunos ejemplos pueden ser que el usuario pueda hacer login y logout.

- Objeto conceptual = Simbologías

- ¿Estos pueden tener atributos y comportamientos?

- Objeto conceptual = Sesión de usuario

- Hizo log in, log out, identficador de la sesión, etc.

- User = Objeto físico

- Session = Objeto conceptual

- Objeto conceptual = cuenta de un banco

- Objeto físico = tarjeta de débito.

## Propiedades = Atributos

- Propiedades también pueden llamarse atributos serán sustantivos.


- Por ejemplo:

1. Nombre
2. Tamaño
3. Forma
4. Estado

<!-- Atributos -->


# Comportamientos

- Serán todas la operaciones del objeto, suelen ser verbos o sustantivo y verbo.

1. login()
2. logout()
3. makeReport()

## Perro

<!-- Propiedades -->
+ nombre
+ color
+ raza
+ altura

<!-- Comportamientos -->
+ ladrar
+ comer
+ dormir
+ correr

### Adopciones
<!-- Propiedades -->
+ id
+ nombre
+ color
+ raza
+ altura

<!-- Comportamientos -->
+ serAdoptado()

## Abstracción y Clases

### CLASE

- Es el MODELO sobre el cual se construirá nuestro objeto.

- La clase es la PLANTILLA, que nos permitirá crear más objetos(instanciar, más adelante).

### ABSTRACCIÓN
<!-- Analizar Objetos para crear Clases -->
- La abstracción es extraer las propiedades y comportamientos que tienen en común varios objetos (o uno solo) para crear la plantilla, el molde, la clase.

<!-- Curso Programación Orientada a Objetos -->

#### EJEMPLO: Uber

<!-- Clase 11 - Analizando Uber -->

- Necesidad: Traslado desde punto A hasta punto B.

1. Solicitud del auto
2. Elijo destino a => b
3. Tipos de autos => Conductor
    a. UberX
    b. UberPool
    c. UberBlack
    d. UberVan
4. Conductor => Auto => Viaje => Costo $ del Viaje

- Objetos:

1. User:
    1. id
    2. name
    3. document
    4. email
    5. password

2. Route:
    1. start: [2] // latitude & longitud
    2. end: [2]  // latitude & longitud

3. Cars: 
    1. Uberx: {
        id,
        license,
        driver,
        passengers,
        brand,
        model,
    }
    2. Uberpool: {
        id,
        license,
        driver,
        passengers,
        brand,
        model,
    }
    3. Uberblack: {
        id,
        license,
        driver, 
        passengers,
        typeOfCarAccepted[],
        seatsMaterial[],
    }
    4. Ubervan: {
        id,
        license,
        driver
        passengers,
        typeOfCarAccepted[],
        seatsMaterial[],
    }

4. Driver: 
    1. id
    2. name
    3. document
    4. email
    5. password

5. Amount:
    1. card: {
        id,
        number,
        cvv,
        date
    }
    2. paypal: {
        id,
        email
    }
    3. cash: {
        id,
    }

6. Trip: {
    user,
    destination,
    type of car,
    payment Option,
}


#### RETO 1: identificando objetos

+ Toma como referencia nuestro Sistema de Adopciones e identifica todos los objetos.

1. Perros: Nombre,

2. Dueños: Nombre,


## UML 

|------------------------------------|
|         Nombre de Clase            |    IDENTIDAD
|------------------------------------|
| + Atributo1:                       |
|   Atributo2:                       |    ESTADO
|   Atributo3:                       |
|------------------------------------|
| + Operación1:                      |
|   Operación2:                      |    COMPORTAMIENTO
|   Operación3:                      |
|------------------------------------|

### EJEMPLO

|--------------------------|
|          Person          |    IDENTIDAD
|--------------------------|
| + name:                  |    ESTADO 
|--------------------------|
| + walk()                 |    COMPORTAMIENTO
|--------------------------|


# Java
- class Person{}
# Python
- class Person:
# JavaScript
- functionPerson() {}
# PHP
classPerson{}


# Java
- class Person{
    String name= "";
    void walk() {}
}

# Python
- class Person:
    name = "";
    def walk():

# JavaScript
- Person.prototype.walk = function() {
    
}

# PHP
- classPerson{}