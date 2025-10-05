# 🌌 Portafolio Interactivo de Cristian Querol Alves

[![Banner del Portafolio](./assets/images/banner-modified.png)](https://cristianquerolalves.com)

---

## 📖 Descripción
Este es mi **portafolio interactivo**, diseñado para mostrar mis proyectos, habilidades y trabajos de manera profesional y moderna. Incluye un **estilo futurista Glassmorphism**, animaciones suaves y efectos visuales atractivos.

El portafolio cuenta con:

- Sección **Sobre mí** y disponibilidad para contratación.
- **Proyectos y trabajos** realizados.
- Tecnologías y herramientas que utilizo.
- **Formulario de contacto funcional** integrado con Formspree.
- Alternancia de **temas claro/oscuro** con persistencia.
- Sección de **clientes y logos interactivos**.

---

## 🛠 Tecnologías utilizadas
- **Frontend:** HTML5, CSS3 (Flexbox, Grid, Glassmorphism), JavaScript (Vanilla JS)  
- **Animaciones y efectos:** Intersection Observer, transformaciones CSS, transiciones suaves  
- **Formularios:** Integración con Formspree para enviar mensajes  
- **Temas:** Modo claro/oscuro con persistencia en LocalStorage  
- **Iconografía:** Ionicons  

---

## 🗂 Estructura del proyecto
```text
portfolio/
├─ index.html
├─ assets/
│   ├─ images/
│   ├─ fonts/
│   └─ icons/
├─ css/
│   └─ style.css
├─ js/
│   └─ main.js
└─ README.md
```

---

## 🚀 Cómo Usarlo

1. Clona el repositorio:
```bash
git clone https://github.com/cristianquerolalves1/portfolio.git
```

2. Abre `index.html` en cualquier navegador moderno para visualizarlo localmente.

3. Para desplegarlo en **GitHub Pages**:
   - Ve a la configuración del repositorio → Pages
   - Selecciona la rama `main` y la carpeta raíz `/`
   - Haz clic en `Save` y tu portafolio estará disponible online.

---

## 📬 Formulario de Contacto
El portafolio incluye un formulario de contacto funcional con **Formspree**:

1. Regístrate en [Formspree](https://formspree.io/) y crea un endpoint.
2. Reemplaza la URL en el atributo `action` del formulario:

```html
<form action="https://formspree.io/f/tu-endpoint" method="POST">
```

3. Asegúrate de que los campos tengan los atributos `name` correctos:

```html
<input type="text" name="name" required>
<input type="email" name="email" required>
<textarea name="message" required></textarea>
```

4. Cuando alguien envíe un formulario, recibirás los mensajes en el correo asociado a tu cuenta de **Formspree**.

---

## ⚖️ Licencia
Este portafolio es **propiedad personal** y **no es open-source**. Todos los derechos reservados a Cristian Querol Alves.
