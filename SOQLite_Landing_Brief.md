# Brief de la Landing Page: SOQLite ⚡️

Este documento contiene toda la información necesaria para que un agente de IA genere una landing page de clase mundial para **SOQLite**.

## 🚀 Propuesta de Valor
**SOQLite** es el sucesor natural y privado de las extensiones web tradicionales o Workbench para Salesforce. Es un cliente SOQL nativo, ultrarrápido y multiplataforma diseñado para consultores y desarrolladores que exigen rendimiento y elegancia.

- **Privacidad Total**: No hay servidores intermedios. Todo sucede en tu máquina.
- **Velocidad Extrema**: Escrito en Rust y React 19 para una respuesta instantánea.
- **Diseño Premium**: Estética estilo Linear/Raycast con modo oscuro impecable.

---

## ✨ Características Principales ("The Wow Factors")

### 1. Conexión Directa y Segura
Interactúa directamente con tu `sf cli` oficial local. No necesitas configurar proxies ni dar tus credenciales a nubes de terceros. Si el CLI está autenticado, SOQLite está listo.

### 2. Tabla de Datos Avanzada (Virtualized Grid)
Utiliza un motor de renderizado vía Canvas (Glide Data Grid). Puedes desplazar miles de filas sin lagm consumiendo menos de 40MB de RAM.
- **Copy-Paste Inteligente**: Copia celdas o filas y pégalas directamente en Excel/Sheets.
- **Filtros Locales**: Filtra y ordena registros ya descargados en microsegundos sin nuevas llamadas a la API.

### 3. Editor de Código Inteligente (Monaco)
El mismo motor que VS Code, pero optimizado para SOQL:
- **Snippets Proactivos**: Escribe `sc` para contar registros, `sq` para una query rápida o `sl` para los últimos modificados.
- **Autocompletado Real**: Deduce el esquema de objetos y campos en tiempo real mientras escribes.
- **Preprocesador**: Corrige typos automáticos (`FRM` -> `FROM`) y normaliza la sintaxis.

### 4. Multitasking y Split View
Abre múltiples pestañas para diferentes entornos simultáneamente. Usa el **Split Viewer** para comparar resultados de PREPROD y PROD lado a lado en una sola ventana.

### 5. Módulo de Importación (Data Loader)
Carga archivos CSV, JSON o Excel. Mapeo automático de campos basado en similitud de nombres y ejecución masiva optimizada.

### 6. Ejecución de Apex y Logs
Ejecuta código Apex anónimo y visualiza los logs de depuración con resaltado de sintaxis y filtros de ruido (mostrar solo `USER_DEBUG`).

---

## 🛠 Stack Tecnológico (Garantía de Rendimiento)
- **Backend Core**: Rust + Tauri v2 (Seguridad y ligereza nativa).
- **Frontend**: React 19 + TypeScript + Vite.
- **Estilos**: Tailwind CSS v4 + Shadcn UI (Diseño moderno y consistente).
- **Almacenamiento**: SQLite local para persistencia de historial y favoritos.

---

## 🎨 Guía de Estilo Visual
- **Colores**: Dark Mode por defecto (Mauve, Peach, Lavender - Paleta inspirada en Catppuccin).
- **Tipografía**: JetBrains Mono para código, Inter/Outfit para UI.
- **Interacciones**: Transiciones suaves con Framer Motion, micro-animaciones en estados de carga.
- **Filosofía**: Menos es más. Espacios limpios, bordes sutiles y transparencias elegantes (Glassmorphism).

---

## 🗺️ Roadmap de Próximas Versiones
- **Monitorización Bulk API**: Gestión visual de jobs masivos en curso.
- **Navegador de Metadatos**: Explorador de objetos para inyección rápida de campos.
- **Execution Profiling**: Análisis visual del plan de ejecución de queries para detectar cuellos de botella.

---

Este documento es la única fuente de verdad para el diseño y contenido de la landing page oficial de **SOQLite**.
