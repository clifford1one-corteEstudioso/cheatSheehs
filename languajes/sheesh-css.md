# CSS

## posibles propiedades de una clase :p

### position

static, relative, absolute, fixed, sticky, fixed

- static: es cmo el default, se pocisiones segun elementos anteriores. Con este no funciona usar top, bottom, right, left.

### display

flex, block, inline, grid, none

### overflow 

este es sobre lo que se asoma fuera del contenedor

hidden, visible, scroll, auto

### top, bottom, right, left

funciona cuando esta fixed creo(?), añade una separación con el borde.

auto, px, %, vh/vw, rem

es util usar valor 0 para pegarlo al borde

### width, height

sin comentarios

%, px, vw/vh, auto, fit-content


## ejemplos del mundo real

```css
.top-bar-right {
    margin-left: auto;
    margin-right: 15vw;
    display: flex;
    /* separacion entre elementos */
    gap: 70px;
    /* alinear en el eje Y */
    align-items: center;
}

.top-link {
    color: #e8e1d6;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
    transition: color 0.3s ease;
    /* margin:20px; */
}
```

en est ecaso, el gap en la clase top-bar, cumple la misma función que el margin en la clase top-link. Gap se usa para las clases que definene contenedores, y margin para el objeto en sí.
