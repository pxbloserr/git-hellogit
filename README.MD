# Cabecera h1
## cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

# Subrayados

underline 1
-----------

underline 2
===========

# Énfasis
se pueden combinar todas entre si como ***~~aqui~~***

- *letra italica 1*
- _letra italica 2_

- formato **bold o strong**
- formato __bold o strong__

- formato ~~tachado~~

# Listas
#### lista ordenada
1. item de lista ordenada
2. item de lista ordenada
3. item de lista ordenada

#### lista desordenada
- item de lista desordenada
- item de lista desordenada
- item de lista desordenada

# Links

- <a href="https://google.es">liks uno como html</a>
- [link en markdown](http://google.com)
- [link en markdown al index](index.html)

# Imagenes

![logo github](https://logos-world.net/wp-content/uploads/2020/11/GitHub-Symbol.png)

# Code Snippets

mirar en [highlight.js](https://highlightjs.org/) demo para ver resaltados según lenguaje.

Código en JSON

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
Código en Javascript

```Javascript
[
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
]
```

# Tablas

Se utiliza " | " para hacer las columnas y cada fila es una línea en el código. 

 | Nombre | Apellido | Documento |
 |--------|----------|----------|
 | Maxi | Burgos | 123456c |
 | Pablo | Serrano | 123456c |
 | Lucas | Soto | 123456c |

# Citas
Texto referente a una cita que se pondrá mas abajo ">"
> Esto es una cita. 

Esto es aparte de la cita, se deja un espacio entre medias y se abre otra cita.
> Esto es otra cita.

# Líneas divisoras

Estro es un texto que se va a dividir "---"

---

Esto es otro texto dividido "___"

___

Eso es otro texto dividido "***" 

***

# Saltos de línea

Se deja un enter de espacio entre los párrafos, si pones muchos sigue dejando solo uno.

Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.