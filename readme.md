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

#SMACSS

Arquitectura en la organizamos los estilos y componentes por carpetas

1. base: Para estilos generales
2. layout: Para regiones, secciones area de la página.
3. Modules: estructura para los componentes.
4. state: para los estados de los componentes.
5. theme: almacena las variables de colores, tipografías y tamaños.

