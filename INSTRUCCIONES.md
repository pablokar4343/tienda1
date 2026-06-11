# 📱 T'REX — Guía de instalación en Android

## ¿Qué incluye este paquete?

| Archivo | Descripción |
|---|---|
| `index.html` | La aplicación completa |
| `manifest.json` | Configuración de la PWA (nombre, íconos, colores) |
| `sw.js` | Service Worker (permite uso sin internet) |
| `icon-192.png` | Ícono de la app (192×192) |
| `icon-512.png` | Ícono splash screen (512×512) |

---

## 🚀 OPCIÓN 1: Instalar desde internet (más fácil)

### Paso 1 — Sube los archivos a un hosting gratuito

Recomendamos **Netlify** (gratis, 1 minuto):

1. Ve a [netlify.com](https://netlify.com) → "Add new site" → "Deploy manually"
2. Arrastra la carpeta `trex` completa
3. Netlify te dará una URL como: `https://trex-abc123.netlify.app`

Otras opciones gratuitas:
- [GitHub Pages](https://pages.github.com) (sube los archivos a un repositorio)
- [Vercel](https://vercel.com)
- [Cloudflare Pages](https://pages.cloudflare.com)

### Paso 2 — Instalar en Android

1. Abre la URL en **Chrome para Android**
2. Espera 3 segundos — aparecerá un banner azul en la parte inferior:
   **"Instalar T'REX — Úsala sin internet"**
3. Toca **Instalar** → ¡Listo!

La app aparecerá en tu pantalla de inicio como cualquier app nativa.

Si no aparece el banner automáticamente:
- Toca el menú ⋮ (tres puntos) en Chrome
- Selecciona **"Añadir a pantalla de inicio"** o **"Instalar app"**

---

## 💻 OPCIÓN 2: Instalar desde red local (sin internet)

Si tienes una computadora en la misma red Wi-Fi:

1. Instala Node.js en tu PC
2. Abre terminal en la carpeta `trex` y ejecuta:
   ```
   npx serve .
   ```
3. Aparecerá una dirección como `http://192.168.1.X:3000`
4. Escribe esa dirección en Chrome de tu celular (mismo Wi-Fi)
5. Instala desde el menú de Chrome

---

## 🔒 Usuario y contraseña por defecto

- **Usuario:** `admin`
- **Contraseña:** `1234`

Cámbialos en **Ajustes → Cuenta** después de entrar.

---

## ✨ Características

- ✅ Funciona sin internet después de instalada
- ✅ Reportes PDF con diseño profesional (día, mes, inventario)
- ✅ Todo en pesos mexicanos (MXN)
- ✅ Inventario con alertas de stock bajo
- ✅ Historial de ventas del día y del mes
- ✅ Exportar PDF directamente desde el celular
- ✅ Colores personalizables
- ✅ Funciona en Android, iPhone y computadora

---

## 📄 Reportes PDF incluyen

- Encabezado **T'REX** + fecha de generación
- Tarjetas de KPIs (total, transacciones, unidades)
- Tabla de productos con ranking y barras de progreso
- Historial de transacciones detallado
- Diseño con colores corporativos azul/verde

---

*T'REX — Tu punto de venta en el celular*
