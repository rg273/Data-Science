![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

## Clase 4

https://aprendeconalf.es/docencia/python/manual/pandas/

https://profile.es/blog/pandas-python/

https://platzi.com/clases/1794-pandas/27906-estructuras-de-dataframes-en-detalle/

Una variable es un espacio de memoria donde guardamos un dato, ese espacio de memoria a la vez recibe un nombre y esto conforma la estructura de datos más simple que podemos encontrar.

![unaImagenConBoxShadow](../_src/assets/02_imagen01.jpg)

Por otro lado existen ciertas normas a la hora de nombrar variables:

* El nombre no puede empezar con un número<br>
  Por ejemplo "mi_variable" sería correcto, pero "123mi_variable" sería erróneo 
* No se permite el uso de guiones del medio -<br>
  Por ejemplo "mi-variable" sería erróneo
* No se permite el uso de espacios.<br>
  Por ejemplo "mi variable" sería erróneo
* No usar nombres reservados para Python. Las palabras reservadas son utilizadas por Python internamente, por lo que no podemos usarlas para nuestras variables o funciones.<br>
  Por ejemplo, a veces podríamos usar "int" ó "for" y esto nos daría error, porque como se verá más adelante, esas palabras son parte de la sintaxis de Python.

### Subtitulo

Sin embargo, cuando ese dato no lo alojamos en una variable y lo utilizamos directamente, recibe el nombre de constante.

<hr width="75%">
  <p align="center">
  Tip: En Python hay algunas funcionalidades ya presentes por defecto, como por ejemplo la funcion **print()** que permite mostrar una salida por pantalla y la función range() que devuelve un rango numérico según los parámetros que recibe y con la función **type()** es posible ver el tipo de dato de una variable
  </p>
<hr width="75%">

### Ejemplo Tabla

**Operaciones aritméticas:**

| Operación | Operador | Ejemplo |
| :---      |  :----:  |    ---: |
| Suma      | + | 3 + 5.5 = 8.5 |
| Resta   | -  | 4 - 1 = 3  |
| Multiplicación | *  | 4 * 2 = 8  |
| Potenciación | 4<sup>2</sup>  | 4**2 = 16  |
| División (Cociente) | /  | 4 / 2 = 2  |
| División (parte entera) | //  | 14 // 3 = 4  |
| División (resto) | %  | 14 % 3 =  2 |

### Algunos ejemplos en Python:

```python
>>> a = 'Hola '
>>> b = 'Mundo !'
>>> print(a + b)
Hola Mundo !

>>> x = 3
>>> y = 12
>>> print(x + y)
15

>>> print(a + x)
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_18232/136165486.py in <module>
----> 1 print(a + x)

TypeError: can only concatenate str (not "int") to str
```

## Homework

Completa la tarea descrita en el archivo [README](https://github.com/soyHenry/Python-Prep/blob/4aec1885136fdcff98899d2be13c8908b39f8b21/02%20-%20Variables%20y%20Tipos%20de%20Datos/Prep_Course_Homework_02.md)

<table class="hide" width="100%" style='table-layout:fixed;'>
  <tr>
    <td>
      <a href="https://airtable.com/shrSzEYT4idEFGB8d?prefill_clase=00-PrimerosPasos">
        <img src="https://static.thenounproject.com/png/204643-200.png" width="100"/>
        <br>
        Hacé click acá para dejar tu feedback sobre esta clase.
      </a>
    </td>
  </tr>
</table>
