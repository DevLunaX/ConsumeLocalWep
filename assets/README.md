# 📁 Assets - Consume Local

Este directorio contiene las imágenes necesarias para el sitio web de Consume Local.

## 📋 Tabla de Imágenes Requeridas

| Archivo | Ruta | Dimensiones | Descripción |
|---------|------|-------------|-------------|
| `logo_consume.png` | `./assets/logo_consume.png` | 150x150px | Logo principal de "Consume Local". Se usa en el Navbar, Hero section y Footer. Se escala automáticamente según el contexto. |
| `hero_phone.png` | `./assets/hero_phone.png` | 400x600px | Mockup de un teléfono mostrando la aplicación. Aparece en la sección Hero principal. |
| `screenshots/login.png` | `./assets/screenshots/login.png` | 720x1280px (9:16) | Captura de la pantalla de login/inicio de sesión con Firebase. |
| `screenshots/home_usuarios.png` | `./assets/screenshots/home_usuarios.png` | 720x1280px (9:16) | Captura de la pantalla principal para usuarios. |
| `screenshots/detalle_producto.png` | `./assets/screenshots/detalle_producto.png` | 720x1280px (9:16) | Captura de la vista de detalle de un producto. |
| `screenshots/perfil_vendedor.png` | `./assets/screenshots/perfil_vendedor.png` | 720x1280px (9:16) | Captura del perfil del vendedor. |
| `screenshots/carrito.png` | `./assets/screenshots/carrito.png` | 720x1280px (9:16) | Captura del carrito de compras. |
| `screenshots/app_en_accion.png` | `./assets/screenshots/app_en_accion.png` | 600x1000px | Imagen promocional de la app en uso. Aparece en la sección "About". |

## 🎨 Especificaciones de Imágenes

### Logo (`logo_consume.png`)
- **Formato:** PNG con fondo transparente
- **Dimensiones:** 150x150px (cuadrado)
- **Uso:** 
  - Navbar (escalado a 40x40px)
  - Hero section (escalado a 112x112px)
  - Footer (escalado a 40x40px)
- **Notas:** Usar colores que contrasten con el fondo oscuro (#0f172a)

### Imagen Hero del Teléfono (`hero_phone.png`)
- **Formato:** PNG con fondo transparente (recomendado)
- **Dimensiones:** 400x600px
- **Uso:** Sección Hero principal, lado derecho
- **Notas:** Mockup de smartphone mostrando la interfaz de la app

### Screenshots de la Aplicación (`screenshots/`)
- **Formato:** PNG o JPG
- **Dimensiones:** 720x1280px (ratio 9:16 vertical)
- **Uso:** Galería de capturas en la sección "Explora la Experiencia"
- **Imágenes requeridas:**
  1. `login.png` - Pantalla de inicio de sesión con Firebase
  2. `home_usuarios.png` - Pantalla principal del usuario
  3. `detalle_producto.png` - Vista detallada de un producto
  4. `perfil_vendedor.png` - Perfil de vendedor
  5. `carrito.png` - Carrito de compras

### Imagen Promocional (`screenshots/app_en_accion.png`)
- **Formato:** PNG o JPG
- **Dimensiones:** 600x1000px
- **Uso:** Sección "About" (Nuestra Misión)
- **Notas:** Imagen promocional mostrando la app en uso real

## ⚠️ Notas Importantes

1. **Fallbacks:** El HTML incluye imágenes de respaldo (placeholder) que se mostrarán automáticamente si los archivos no existen.

2. **Optimización:** Se recomienda comprimir las imágenes antes de subirlas para mejorar el rendimiento del sitio.

3. **Formatos Soportados:** PNG (preferido para transparencia), JPG (para fotografías).

4. **Colores de Marca:**
   - Naranja primario: `#f97316`
   - Ámbar/Amarillo: `#fbbf24`
   - Fondo oscuro: `#0f172a`

## 📂 Estructura de Carpeta

```
assets/
├── README.md                    # Este archivo
├── logo_consume.png             # Logo principal (150x150px)
├── hero_phone.png               # Mockup teléfono hero (400x600px)
└── screenshots/                 # Capturas de pantalla de la app
    ├── login.png                # Login Firebase (720x1280px)
    ├── home_usuarios.png        # Home usuarios (720x1280px)
    ├── detalle_producto.png     # Detalle producto (720x1280px)
    ├── perfil_vendedor.png      # Perfil vendedor (720x1280px)
    ├── carrito.png              # Carrito compras (720x1280px)
    └── app_en_accion.png        # Imagen promocional (600x1000px)
```
