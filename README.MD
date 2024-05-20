# Cabecera h1 "#"
## cabecera h2 "##"
### cabecera h3 "###"
#### cabecera h4 "####"
##### cabecera h5 "#####"
###### cabecera h6 "######"

# Subrayados

underline 1 "---"
---

underline 2 "==="
===

# Énfasis
se pueden combinar todas entre si como ***~~aqui~~***

- *letra italica 1* "* t *"
- _letra italica 2_ "_ t _"

- formato **bold o strong** "** a **"
- formato __bold o strong__
"__ a __"

- formato ~~tachado~~ "~~ a ~~"

# Listas
#### lista ordenada (se numera el primero con un punto y se hace automático)
1. item de lista ordenada
2. item de lista ordenada
3. item de lista ordenada

#### lista desordenada "-"
- item de lista desordenada
- item de lista desordenada
- item de lista desordenada

# Links

- <a href="https://google.es">liks uno como html</a> usando las etiquetas como html
- [link en markdown](http://google.com), entre [ ] se pone el texto de link y entre ( ) el enlace o dirección
- [link en markdown al index](index.html) se usa para ir a una parte del documento

# Imagenes

Se pone ! y entre [ ] el texto de la foto que se mostrará en caso de no cargar y entre ( ) la url o ubicación de la foto.

![logo github](https://logos-world.net/wp-content/uploads/2020/11/GitHub-Symbol.png)

# Code Snippets

mirar en [highlight.js](https://highlightjs.org/) para ver más información.

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