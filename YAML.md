# CONCEPTOS BÁSICOS DE YAML

## ¿QUÉ ES YAML?

YAML es un lenguaje de serialización de datos que las personas pueden comprender y suele utilizarse en el diseño de archivos de configuración. Para algunas personas, YAML significa otro lenguaje de marcado más; para otras, es un acrónimo recursivo que quiere decir "YAML no es un lenguaje de marcado", lo que enfatiza la idea de que se utiliza para los datos, no para los documentos. 

<img src="JSON_vector_logo.svg.png" alt="Logo JSON" style="width: 300px; height: 300px;">

## ¿Para qué sirve YAML?

Uno de los usos más comunes es la creación de archivos de configuración. Se recomienda utilizar YAML en lugar de JSON para escribir los archivos de configuración porque es un lenguaje más fácil de comprender, aunque ambos pueden usarse de manera indistinta en la mayoría de los casos.  

Además de Ansible, hay otros elementos que utilizan YAML, como las implementaciones y los recursos de Kubernetes. 

Una de las ventajas de utilizarlo es que se pueden agregar los archivos a un control de versiones, como Github, para rastrear y auditar los cambios.

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
1. [RED HAT](https://www.redhat.com/es/topics/automation/what-is-yaml)
2. [ARIMETRICS](https://www.arimetrics.com/glosario-digital/json)
