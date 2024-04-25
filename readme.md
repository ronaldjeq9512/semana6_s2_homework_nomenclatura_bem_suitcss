#BEM
 1. Block(bloque): Componente y/o módulo independiente UI
 2. Element(elemento): Cada elemento que conforma el bloque
 3. Modifier(modificador): Una variante del bloque que cambia una propiedad del elemento


---

.bloque {...}

.bloque__elemento {...}

.bloque--modificador{...}

---



---

.menu {...}

.menu__item {...}

.menu__item--active {...}

---

#SUITCSS

1. Nomenclatura que inicia con el bloque en Pascal case y usa como separador el - entre el elemento y -- con el modifier

---

.MyComponent {...} 

.MyComponent-element {...}

.MyComponent--modifier {...}

---

---

.Menu {...}

.Menu-item {...}

.Menu-link {...}

.Menu--isLiked {...}

---