# Te Amo 3D - Mensuario 03

Este proyecto es una animación interactiva y romántica diseñada para celebrar un mensuario. Utiliza tecnologías web modernas para crear una experiencia visual impactante con efectos de partículas, fuegos artificiales y una secuencia de introducción dinámica.

## ✨ Características Principales

- **Introducción Dinámica**: Un corazón central con efectos de latido y expansión que da paso al contenido principal.
- **Secuencia de Estrellas**: Las letras del mensaje principal ("BUENOS DIAS MI PRINCESITA") se forman a partir de estrellas fugaces interactuando en pantalla.
- **Efectos de Partículas (Fuegos Artificiales)**: Un sistema de partículas en el fondo que simula fuegos artificiales de colores aleatorios.
- **Lluvia de Corazones**: Una lluvia de corazones flotantes que aparece tras la formación del mensaje.
- **Interactividad**: Las letras del mensaje reaccionan al pasar el mouse (hover), cambiando de color, rotando y pulsando suavemente.
- **Diseño Responsivo**: Totalmente optimizado para dispositivos móviles, tablets y escritorio, con tipografía adaptable (`clamp`) que asegura que el mensaje quepa en pantallas como 450x950.

## 🛠️ Tecnologías Utilizadas

- **HTML5 / CSS3**: Estructura de layout fluida y estilos premium con gradientes y sombras dinámicas.
- **JavaScript (Vanilla)**: Lógica para el sistema de partículas y el manejo del canvas de fondo.
- **GSAP (GreenSock Animation Platform)**: Motor de animaciones utilizado para las transiciones complejas y el movimiento de las estrellas/letras.
- **Canvas API**: Para renderizar los fuegos artificiales y los corazones flotantes con alto rendimiento.
- **SVG**: Para el corazón central de la introducción.

## 🚀 Instalación y Uso

No requiere compilación ni dependencias externas locales. Simplemente clona el repositorio y abre el archivo `index.html` en cualquier navegador moderno.

```bash
git clone https://github.com/GandalfTheGit1/mensuario-03.git
cd mensuario-03
open index.html
```

## 📂 Estructura del Proyecto

- `index.html`: Archivo principal con la animación y toda la lógica integrada.
- `teamo3d.html`: Copia sincronizada del archivo principal para redundancia/testeo.
- `README.md`: Documentación del proyecto.

## ⚙️ Personalización

Para cambiar el mensaje principal, busca la sección con la clase `.mensaje` en el código HTML:

```html
<div class="mensaje">
    <div class="line">
        <div class="word"><span>N</span><span>U</span><span>E</span>...</div>
    </div>
</div>
```

Para ajustar la velocidad o densidad de los fuegos artificiales, puedes modificar la variable `fireworkMode` en el script.

---
Hecho con ❤️ para celebrar momentos especiales.
