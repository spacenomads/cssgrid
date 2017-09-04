# Flexbox
Guión para repaso ;)

**Puntos**
* Flexbox
* flex-direction
* flex-wrap
* justify-content
* align-items
* align-content
* align-self
* flex grow/shrink/basis


## Flexbox
* Qué es flexbox
* Por qué (Qué me soluciona)

### Qué necesitamos:
**CSS**
```css
display: flex;
```
**HTML**
```html
<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
</div>
```

## flex-direction
Establece el eje principal del contenedor flex.

```css
flex-direction: row; /*default */
flex-direction: column;
flex-direction: row-reverse;
flex-direction: column-reverse;
```


## flex-wrap
Define si todos los elementos estarán en una línea o si se irán distribuyendo según el ancho.
```css
flex-wrap: no-wrap; /* default*/
flex-wrap: wrap;
flex-wrap: wrap-reverse;
```

## justify-content
Marca cómo se van a alinear los elementos en el eje principal.
```css
justify-content: flex-start; /*default*/
justify-content: flex-end;
justify-content: center;
justify-content: space-between;
justify-content: space-around;
```


## align-items
Marca cómo se van a alinear los elementos en el eje contrario(?).
```css
align-items: flex-start;
align-items: flex-end;
align-items: center;
align-items: stretch; /*default*/
```


## align-content
Define cómo se va a distribuir el espacio extra del eje contrario :)
```css
align-content: flex-start;
align-content: flex-end;
align-content: center;
align-content: space-between;
align-content: space-around;
align-content: stretch; /*default*/
```


## align-self
Es un align-items para 1 elemento.
```css
align-self: flex-start;
align-self: flex-end;
align-self: center;
align-self: stretch; /*default*/
```


## flex grow/shrink/basis
Marca cómo van a adaptarse los elementos al eje principal por defecto, si sobra espacio o si falta.
```css
flex-grow: 0;
flex-shrink: 1;
flex-basis: auto;
flex: 0 1 auto;
```

## Prácticas
- [Flexbox 01 - alineación](https://codepen.io/oneeyedman/pen/yoeRgj)
- [Flexbox 02 - Página](https://codepen.io/oneeyedman/pen/PKNPrX)
- [Flexbox 03 - Menu](https://codepen.io/oneeyedman/pen/jLqWNO)
