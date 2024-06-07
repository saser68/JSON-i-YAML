> [!NOTE]
La información relatada en este documento podría no ser correcta




# JSON-i-YAML

### Que es YAML? ###
  YAML  es un formato de serialización de datos legible por humanos inspirado en lenguajes como XML, C, Python, Perl, así como en el formato de los correos electrónicos.

+ YAML es un formato de serialización de datos que significa YAML ain’t Markup language.
Una de las principales ventajas de usar YAML es la legibilidad y la escitura.
+ Otra ventaja esmla de la capacidad de admitior distintos casos como datos 
+ Tiene un soporte muy
+  YAML también contiene valores sencillos (escalares), que son datos arbitrarios (codificados en Unicode) que se pueden utilizar como cadenas, números enteros, fechas, números o booleanos.

### Qué es JSON ###
JSON (JavaScript Object Notation) es un formato de texto pensado para el intercambio de datos. Su sintaxis está basada originalmente en la sintaxis de JavaScript, pero realmente es independiente de cualquier lenguaje de programación.
El formato JSON fue definido por Douglas Crockford a finales de 2002 y dado a conocer a través de su página web http://json.org/. Esta página contenía la definición del formato y una implementación en Java. En poco tiempo el uso del formato se extendió y aparecieron implementaciones para todos los lenguajes de programación. El motivo de su éxito es su sencillez y facilidad de uso.

 ### SINTAXIS ###


+ En JSON existen dos tipos de elementos

    matrices (arrays): Las matrices son listas de valores separados por comas. Las matrices se escriben entre corchetes [ ] 

````
```
[1, "pepe", 3.14, "Pepito Conejo"]
```
````


+ objetos (objects). Los objetos son listas de parejas nombre / valor. El nombre y el valor están separados por dos puntos : y las parejas están separadas por comas. Los objetos se escriben entre llaves { } y los nombres de las parejas se escriben siempre entre comillas dobles. 


````
```
{"nombre": "Pepito Conejo", "edad": 25, "carnet de conducir": true}
```
````


+ Los espacios en blanco y los saltos de línea no son significativos, es decir, puede haber cualquier número de espacios en blanco o saltos de línea separando cualquier elemento o símbolo del documento. 


````
```
Correcto

[
  {
    "nombre": "Pepito Conejo",
    "edad": 25,
    "carnet de conducir": true
  },
  {
    "nombre": "Ana Barberá",
    "edad": 90,
    "carnet de conducir": false
  }
]

```
````

### JSON-RPC ###

| RPC | Descripcion |
| --- | --- |
| jsonrpc | Una cadena que indica la versión ("2.0") |
| method | Una cadena que indica el método invocado. |
| params | (optativo) una matriz o una lista de valores |
| id | Un número o cadena establecido por el cliente |
|jsonrpc | Una cadena que indica la versión ("2.0") |
| result | (optativo) el resultado de la consulta, en forma de valor, matriz o lista.  |
| 1error | (optativo) una matriz o una lista de errores, con la estructura siguiente:  |
| 1.1code | Código de error (número entero) |
| 1.2message | Descripción breve del error |
| 1.3data | (optativo) matriz o lista de valores con información adicional sobre el error |






 ### Otros ###

Las versiones obsoletas de las normas sobre JSON son las siguientes:

   + julio de 2006: RFC 4627: The application/json Media Type for JavaScript Object Notation, escrita por D. Crockford. Reemplazada en marzo de 2014 por la RFC 7159.
   +   marzo de 2013: RFC 7158: The JavaScript Object Notation (JSON) Data Interchange Format, editada por Tim Bray. Reemplazada en marzo de 2014 por la RFC 7159.
   + octubre de 2013: ECMA 404 (1º ed): The JSON Data Interchange Format. Reemplazada en diciembre de 2017 por la segunda versión.
   +   enero de 2014: JSON-LD 1.0 (A JSON-based Serialization for Linked Data), editada por Manu Sporny y otros.
   +  enero de 2014: JSON-LD 1.0 Processing Algorithms and API, editada por Dave Longley y otros.
   +  marzo de 2014: RFC 7159: The JavaScript Object Notation (JSON) Data Interchange Format, editada por Tim Bray. Reemplazada en diciembre de 2017 por la RFC 8259.




