# 🎮 Mania Orbital Spin

**Mania Orbital Spin** es una animación de anillos giratorios inspirada en el menú principal de *Sonic Mania Plus*. Surgió como un experimento por entretenimiento y terminó siendo un diseño adaptable que puede usarse como fondo animado para páginas web u otros proyectos. Además, está disponible como un recurso abierto para que cualquiera lo utilice o modifique según sus necesidades.

## 💠 Características

✔️ Animación fluida de anillos en rotación.  
✔️ Diseño responsivo adaptable a diferentes tamaños de pantalla.  
✔️ Personalización sencilla mediante variables CSS.  
✔️ Código limpio y modular para fácil integración.  

## 🌐 Vista previa

🔍 ![Vista previa de la animación](assets/gifs/Mania-Orbital-Spin.gif)

## 🖱️ Ver en acción

🔗 [Ver animación en acción](https://andev-000.github.io/Mania-Orbital-Spin/)

## 🚀 Cómo usarlo

1. Clona este repositorio en tu máquina local:  
   ```bash
   git clone https://github.com/AnDev-000/Mania-Orbital-Spin.git
   ```
2. Abre `index.html` en tu navegador o intégralo en tu proyecto web.  

## 🎨 Personalización

Puedes modificar fácilmente el diseño y el comportamiento de la animación editando las variables en el archivo `style.css`. Esto te permite ajustar tamaños, colores y velocidades sin necesidad de modificar directamente las clases CSS.

### 🔹 Tamaño de los anillos y órbitas
Para cambiar el tamaño general de la animación, ajusta la siguiente variable:

```css
:root {
  --ring-size: 50vmin; /* Ajusta este valor para aumentar o reducir la escala general */
}
```

Si deseas modificar los grosores de los anillos, puedes hacerlo aquí:

```css
:root {
  --red-ring-thickness: calc(var(--ring-size) * 0.019); /* Grosor del anillo rojo */
  --blue-ring-thickness: calc(var(--ring-size) * 0.026); /* Grosor del anillo azul */
  --orange-circle-thickness: calc(var(--ring-size) * 0.08); /* Grosor del círculo central */
}
```

### 🎨 Colores
Los colores de los anillos y el fondo se pueden personalizar fácilmente cambiando estas variables:

```css
:root {
  --background-color: #fddb00; /* Color de fondo */
  --red-color: #e43c2f; /* Color del anillo y planeta rojo */
  --blue-color: #69cdb3; /* Color del anillo y planeta azul */
  --orange-color: #fe8616; /* Color del círculo interno naranja */
}
```

### 🪐 Tamaño de los planetas
Si quieres cambiar el tamaño de los planetas que orbitan alrededor de los anillos:

```css
:root {
  --small-red-circle-size: calc(var(--ring-size) * 0.12); /* Tamaño del planeta rojo */
  --small-blue-circle-size: calc(var(--ring-size) * 0.09); /* Tamaño del planeta azul */
}
```

### ⏳ Velocidad y dirección de rotación
Para cambiar la velocidad de los anillos, edita las siguientes propiedades:

```css
.red-ring {
  animation-duration: 17s; /* Ajusta la velocidad del anillo rojo */
}

.blue-ring {
  animation-duration: 58s; /* Ajusta la velocidad del anillo azul */
  animation-direction: reverse; /* Cambia la dirección de giro si lo deseas */
}
```

Si deseas modificar el efecto de escala que hace que los anillos aumenten y disminuyan de tamaño ligeramente:

```css
@keyframes scale {
  0%, 100% { transform: scale(1); } /* Escala normal */
  50% { transform: scale(1.3); } /* Expansión máxima */
}
```
Si prefieres eliminar este efecto, simplemente comenta o elimina la línea `animation: scale 5s ease-in-out infinite;` en las clases `.orbit`.

---

Con estas configuraciones puedes personalizar la animación según tu estilo y necesidades. Si tienes alguna duda o sugerencia, no dudes en abrir un *issue* o *pull request* en el repositorio. 🚀

## 📝 Licencia

Este proyecto está disponible bajo la [Licencia MIT](https://opensource.org/licenses/MIT), lo que significa que puedes usarlo, modificarlo y compartirlo libremente.

## ✨ Autor

Creado por [Andres (AnDev-000)](https://github.com/AnDev-000).  
Si te gusta este proyecto, ¡no dudes en darle una estrella ⭐ en GitHub!.