# Version del curso
Version Actual: v1.2.2.

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~, formato nomal.
- Aqui podemo usar formato *italico*, pero tambien **bold** y ~~tachado~~

# Listas
1. Esto e sun item de lista ordenada.
2. Esto e sun item de lista ordenada.
3. Esto e sun item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http:google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://1000marcas.net/wp-content/uploads/2020/02/GitHub-logo-1.jpg)

# Code Snippets
Codigo en JSON
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
Codigo en JavaScript
```JavaScript
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
| Maxi   | Burgos   | 343423    |
| Miguel | Sarabia  | 434412    |

# Citas
Esto es un texto referente a una cita que pondremos debajo: 
> Esto es una Cita

Esto es otro texto no relacionado con la cita 
> Esto es otra cita

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___

# Saltos de Linea 
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.

