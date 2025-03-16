# 🎮 Mania Orbital Spin

**Mania Orbital Spin** es una animación de anillos giratorios inspirada en el menú principal de *Sonic Mania Plus*. Mientras disfrutaba del juego, su estilo artístico me fascinó, especialmente el diseño del fondo, y decidí recrearlo como un proyecto web. Este diseño no solo es adaptable y personalizable, sino que también está disponible como un recurso abierto para que cualquiera lo utilice o modifique según sus necesidades.

## 🌀 Características

✔️ Animación fluida de anillos en rotación.  
✔️ Diseño responsivo adaptable a diferentes tamaños de pantalla.  
✔️ Personalización sencilla mediante variables CSS.  
✔️ Código limpio y modular para fácil integración.  

## 🌐 Demo en vivo

🔗 [Ver animación en acción](https://andev-000.github.io/Mania-Orbital-Spin/)

## 🚀 Cómo usarlo

1. Clona este repositorio en tu máquina local:  
   ```bash
   git clone https://github.com/AnDev-000/Mania-Orbital-Spin.git
   ```
2. Abre `index.html` en tu navegador o intégralo en tu proyecto web.  

## 🎨 Personalización

Puedes modificar fácilmente el diseño editando las variables en el archivo `style.css`.

### 🔹 Tamaño de los anillos
Para ajustar el tamaño general de la animación, modifica la variable:  
```css
--ring-size: 50vmin; /* Aumenta o reduce el valor según necesites */
```

### 🎨 Colores
Puedes cambiar los colores de los anillos editando las siguientes variables:  
```css
--red-color: #fe3522;    /* Color del anillo rojo */
--blue-color: #6ad7b9;   /* Color del anillo azul */
--orange-color: #fe8616; /* Color del círculo interno naranja */
```

### ⏳ Velocidad de rotación
Para cambiar la velocidad de los anillos, edita las animaciones en `style.css`:  
```css
.red-ring { animation-duration: 17s; } /* Ajusta la velocidad del anillo rojo */
.blue-ring { animation-duration: 58s; } /* Ajusta la velocidad del anillo azul */
```

## 📄 Licencia

Este proyecto está disponible bajo la [Licencia MIT](https://opensource.org/licenses/MIT), lo que significa que puedes usarlo, modificarlo y compartirlo libremente.

## ✨ Autor

Creado por [Andres (AnDev-000)](https://github.com/AnDev-000).  
Si te gusta este proyecto, ¡no dudes en darle una estrella ⭐ en GitHub!