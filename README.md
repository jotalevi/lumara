# 🌅 Lumara Festival 2026 - Sitio Web Oficial

Sitio web oficial para el **Lumara Festival 2026**, un festival de trance frente al Pacífico en la Costa Central de Chile.

## 🎯 Características

- **Diseño moderno y responsive** - Se adapta a todos los dispositivos
- **Countdown en tiempo real** - Cuenta regresiva hasta el festival
- **Navegación suave** - Scroll suave entre secciones
- **Formulario de inscripción** - Para Lumara Insiders
- **Sección de merch** - Integración con tienda externa
- **Galería de fotos** - Muestra la vibra del festival
- **Información útil** - Todo lo que necesitan saber los asistentes

## 🚀 Cómo usar

### Instalación local

1. **Descarga los archivos**
   ```bash
   # Clona o descarga los archivos en tu computadora
   ```

2. **Abre el sitio**
   - Abre `index.html` en tu navegador
   - O usa un servidor local como Live Server en VS Code

3. **Personaliza el contenido**
   - Edita `index.html` para cambiar textos
   - Modifica `styles.css` para cambiar colores y estilos
   - Ajusta `script.js` para funcionalidad personalizada

## 🎨 Personalización

### Colores principales

Los colores están definidos en CSS variables en `styles.css`:

```css
:root {
    --lumara-gold: #FF6B35;      /* Dorado principal */
    --lumara-orange: #F7931E;    /* Naranja */
    --lumara-blue: #1E3A8A;      /* Azul noche */
    --lumara-dark: #0F172A;      /* Azul oscuro */
}
```

### Cambiar fechas

En `script.js`, actualiza las fechas:

```javascript
// Fecha del festival
const festivalDate = new Date('2026-01-23T16:00:00').getTime();

// Fecha del reveal del lineup
const revealDate = new Date('2026-01-09T00:00:00').getTime();
```

### Integrar tienda externa

1. **Reemplaza los enlaces de merch** en `index.html`:
   ```html
   <a href="TU_URL_DE_TIENDA" class="btn btn-merch">Comprar Ahora</a>
   ```

2. **Actualiza el JavaScript** en `script.js`:
   ```javascript
   // Reemplaza con tu URL real
   window.open('TU_URL_DE_TIENDA', '_blank');
   ```

### Agregar fotos reales

1. **Reemplaza las imágenes placeholder** en `index.html`:
   ```html
   <img src="ruta/a/tu/foto.jpg" alt="Descripción de la foto">
   ```

2. **Ajusta el CSS** si es necesario para diferentes tamaños

## 📱 Responsive Design

El sitio está optimizado para:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (320px - 767px)

## 🔧 Funcionalidades

### Countdown Timer
- Cuenta regresiva en tiempo real hasta el festival
- Se actualiza cada segundo
- Formato: días, horas, minutos, segundos

### Navegación
- Menú fijo en la parte superior
- Navegación móvil con hamburger menu
- Scroll suave entre secciones

### Formulario de Inscripción
- Validación de campos obligatorios
- Validación de email
- Simulación de envío (personalizar para tu backend)

### Animaciones
- Fade-in al hacer scroll
- Hover effects en cards
- Parallax en hero section

## 🎯 Secciones del Sitio

1. **Hero** - Banner principal con countdown
2. **El Festival** - Historia, ubicación, horarios
3. **Merch** - Productos oficiales
4. **Lineup** - DJs (se revela progresivamente)
5. **Inscripción** - Formulario para Lumara Insiders
6. **Info Útil** - Qué traer, servicios, seguridad
7. **Galería** - Fotos del festival
8. **Contacto** - Información de contacto y redes

## 🔗 Integraciones Recomendadas

### Email Marketing
- **Mailchimp** - Para la lista de Lumara Insiders
- **Brevo** - Alternativa gratuita

### E-commerce
- **BigCartel** - Simple y económico
- **Shopify** - Más completo
- **Instagram Shop** - Para ventas directas

### Redes Sociales
- Instagram
- TikTok
- Telegram (grupo de Insiders)

## 📊 SEO

El sitio incluye:
- Meta tags optimizados
- Estructura semántica HTML5
- URLs amigables
- Contenido relevante para festivales de trance

## 🚀 Deploy

### Opciones gratuitas:
- **GitHub Pages** - Sube a un repositorio
- **Netlify** - Drag & drop de archivos
- **Vercel** - Integración con Git

### Opciones pagas:
- **Hostinger** - Hosting económico
- **GoDaddy** - Dominio + hosting
- **AWS S3** - Para sitios estáticos

## 🎨 Personalización Avanzada

### Cambiar fuentes
En `index.html`, actualiza los links de Google Fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=TU_FUENTE:wght@400;500;600;700&display=swap" rel="stylesheet">
```

### Agregar más animaciones
En `styles.css`, puedes agregar más keyframes:
```css
@keyframes tuAnimacion {
    /* Define tu animación */
}
```

### Integrar analytics
Agrega Google Analytics o similar en el `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU_ID"></script>
```

## 📞 Soporte

Para personalizaciones específicas o dudas:
- Revisa los comentarios en el código
- Modifica los archivos según tus necesidades
- Prueba en diferentes navegadores

## 🎉 ¡Listo!

Tu sitio web de Lumara Festival está listo para usar. Solo necesitas:
1. Personalizar el contenido
2. Integrar tu tienda
3. Agregar fotos reales
4. Configurar el dominio
5. ¡Publicar!

---

**¡Que disfrutes el festival! 🌅🎵**
