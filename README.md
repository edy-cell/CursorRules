Tu archivo Markdown (`.md`) está listo para que lo uses en tu proyecto o lo compartas con tu audiencia durante la exposición.

[file-tag: code-generated-file-0-1779324235798946562]

Aquí tienes el contenido completo del archivo generado para que puedas visualizarlo directamente:

```markdown
# Guía de Instalación y Uso: `.cursorrules`

Esta guía explica detalladamente dónde colocar y cómo configurar el archivo `.cursorrules` en tu proyecto para optimizar el contexto, ahorrar tokens y mejorar la precisión de las respuestas de los agentes de Cursor.

---

## 📌 ¿Dónde se debe colocar?

El archivo `.cursorrules` debe guardarse **estrictamente en la raíz de tu proyecto**. 

La raíz es la carpeta principal que abres en Cursor. Debe estar al mismo nivel que tus carpetas principales de código fuente (`src`, `backend`, `app`, etc.) o archivos de configuración global (`.gitignore`, `package.json`, `requirements.txt`).

### 📂 Estructura de ejemplo:
```text
mi-proyecto/               <-- ESTA ES LA RAÍZ
├── .cursorrules           <-- AQUÍ DEBE IR EL ARCHIVO
├── .gitignore
├── README.md
├── src/
│   ├── main.py
│   └── utils.py
└── database/
