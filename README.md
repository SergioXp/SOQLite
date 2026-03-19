<div align="center">
  <h1>⚡️ SOQLite Landing Page</h1>
  <p><strong>El motor SOQL privado y más rápido para profesionales de Salesforce.</strong></p>
  <p>Esta es la página de presentación (Landing Page) oficial de <a href="https://github.com/SergioXp/SOQLite">SOQLite</a>, construida para ser ultrarrápida, accesible internacionalmente y altamente optimizada para conversión y SEO.</p>
</div>

<br />

## 🚀 Características del Proyecto

- **[Astro v5](https://astro.build/)**: Generación de sitios estáticos (SSG) de alto rendimiento.
- **[Tailwind CSS v4](https://tailwindcss.com/)**: Estilizado moderno, responsivo y basado en utilidades con diseño de *glassmorphism* premium (colores Mauve, Peach y Lavender).
- **Internacionalización (i18n)**: Soporte nativo para múltiples idiomas. Por defecto en inglés (`/`), con versión completa en español (`/es`).
- **SEO Optimizado**: Etiquetas dinámicas, meta descripciones, OpenGraph y Twitter cards configurados de forma nativa.
- **Sincronización Dinámica de GitHub**: La versión del software y los enlaces de descarga directa hacia macOS, Windows y Linux se actualizan automáticamente consultando la [GitHub API](https://docs.github.com/en/rest) en tiempo real, obteniendo siempre el `latest release`.
- **Analíticas Nativas**: Integración completa con `@vercel/analytics` para métricas web instantáneas y respetuosas con la privacidad.

## 🛠 Instalación y Trabajo Local

Sigue estos pasos para arrancar el entorno de desarrollo local de la landing page en tu propia máquina:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/SergioXp/SOQLite.git
   cd SOQLite
   ```

2. **Instala las dependencias necesarias** (Asegúrate de tener Node.js instalado):
   ```bash
   npm install
   ```

3. **Arranca el servidor de desarrollo:**
   ```bash
   npm run dev
   ```

Una vez ejecutado, abre [http://localhost:4321](http://localhost:4321) en tu navegador preferido. Las ediciones realizadas en `src/` se reflejarán instantáneamente gracias al Hot Module Replacement (HMR).

## 📦 Listado de Comandos

Todos estos comandos se ejecutan desde la raíz del proyecto usando tu terminal:

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala todas las dependencias del proyecto definidas en `package.json`. |
| `npm run dev` | Inicia el servidor de desarrollo local para ver tus cambios en vivo. |
| `npm run build` | Construye y compila el proyecto completo y lo prepara para subir a producción (genera la carpeta `/dist`). |
| `npm run preview` | Inicia un servidor local que sirve los archivos compilados en `/dist` para que pruebes el entorno real de producción. |

## 🌐 Tecnologías Involucradas

- Astro (Framework)
- React 19 / Rust / Tauri 2 (Descritos en los atributos del software)
- Tailwind CSS v4 (Estilos)
- Vercel Analytics Módulo Integrado
- Vercel (Hosting Recomendado)

## 👤 Autoría

Diseño, desarrollo y copy concebidos para acompañar al cliente de base de datos **SOQLite**. 
Creado y mantenido por **[SergioXp](https://github.com/SergioXp)** (Sergio González).

<div align="center">
  <sub>Construido con ❤️ para la comunidad de desarrolladores y consultores de Salesforce.</sub>
</div>
