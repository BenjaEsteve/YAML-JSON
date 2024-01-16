# CONCEPTOS BÁSICOS DE JSON

## ¿QUÉ ES JSON?

JSON (acrónimo de JavaScript Object Notation, 'notación de objeto de JavaScript') es un formato de texto sencillo para el intercambio de datos. Se trata de un subconjunto de la notación literal de objetos de JavaScript, aunque, debido a su amplia adopción como alternativa a XML, se considera un formato independiente del lenguaje.

<img src="JSON_vector_logo.svg.png" alt="Logo JSON" style="width: 300px; height: 300px;">

JSON_vector_logo.svg.png

## ¿Para qué sirve JSON?

JSON se utiliza a menudo como alternativa a otras bases de datos y formatos de almacenamiento de datos, como XML o CSV. Es especialmente popular en aplicaciones web, donde se puede convertir fácilmente desde y hacia otros formatos como HTML y JavaScript. Además, como la sintaxis de JSON es sencilla y fácil de entender, muchos desarrolladores lo encuentran mucho más fácil de usar que otros formatos de datos.

## CARACTERÍSTICAS DE JSON

JSON (JavaScript Object Notation) es un formato de intercambio de datos que se utiliza para representar información estructurada en forma de pares clave-valor. Aquí hay algunas características clave de JSON:

### 1. Sintaxis Ligera y Fácil de Leer:
La sintaxis de JSON es sencilla y fácil de entender tanto para los humanos como para las máquinas.
        
### 2. Estructura de Pares Clave-Valor:
Los datos en JSON se representan en pares clave-valor, lo que facilita la asociación de información.

### 3. Tipos de Datos Soportados:
JSON admite tipos de datos como cadenas de texto, números, booleanos, objetos, arreglos y valores nulos.

### 4. Anidación:
Puedes anidar objetos y arreglos dentro de otros objetos y arreglos en JSON, lo que permite representar estructuras de datos complejas.

### 5. Independiente del Lenguaje:
Aunque tiene "JavaScript" en su nombre, JSON es un formato independiente del lenguaje y se puede utilizar con la mayoría de los lenguajes de programación.

### 6. Fácil de Convertir:
JSON se puede convertir fácilmente en estructuras de datos utilizadas en muchos lenguajes de programación, y viceversa.

### 7. Amplia Adopción:
Debido a su simplicidad y flexibilidad, JSON ha sido ampliamente adoptado y se utiliza comúnmente para el intercambio de datos en aplicaciones web y servicios web.

### 8. Soporte Nativo en JavaScript:
En JavaScript, trabajar con JSON es muy fácil ya que el lenguaje incluye funciones nativas (JSON.parse() y JSON.stringify()) para analizar y generar JSON, respectivamente.

### 9. Sin Funciones o Comportamientos:
JSON es un formato de datos y no incluye funciones ni comportamientos, lo que lo hace seguro para intercambiar datos entre sistemas.

### 10. Extensibilidad:
Puedes extender JSON agregando nuevos campos o estructuras según sea necesario, lo que facilita la evolución de los datos con el tiempo.

## EJEMPLO

```json
{
  "libros": [
    {
      "título": "El señor de los anillos",
      "autor": "J.R.R. Tolkien",
      "año": 1954
    },
    {
      "título": "1984",
      "autor": "George Orwell",
      "año": 1949
    },
    {
      "título": "Matar a un ruiseñor",
      "autor": "Harper Lee",
      "año": 1960
    }
  ]
}
```

## BIBLIOGRAFÍA
1. https://www.arimetrics.com/glosario-digital/json
2. https://es.wikipedia.org/wiki/JSON

