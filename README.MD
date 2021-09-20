# Cabeceras
# cabecera h1
## cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

# Underlines
Underline1
----------
UnderLine2
==========

# Formatos de enfasis

- formato *italica* de la primer forma 
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primer forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~, formato normal
- aqui pordemos usar *formato italico* pero tambien **bold** y ~~tachado~~

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada


# Links
- <a href="www.google.com">esto es un link html </a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# imagenes 
![Logo Github](https://logos-marcas.com/wp-content/uploads/2020/11/GitHub-Logo.png)

# Code Snippets
Codigo en Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en JS
```javaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | burgos | 123456 |
| Tompson | Tomas | 5432 |

# Citas
Esto es un texto referente a una cita que estará abajo
> Esto es una cita

Este es otro texto que no se relaciona con la anterior
> Esto es otra cita

# Lineas divisoras
Esto es un texto que sera dividido por guiones medios

---

Esto es otro texto dividido por asteriscos

***

Esto es otro texto dividido por guiones bajos

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista