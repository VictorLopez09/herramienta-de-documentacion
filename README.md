# 📄 Documentación del Proyecto

## 1️⃣ Definición General del Proyecto de Software

### 1.1. 📌 Planteamiento de la Problemática

El proceso de gestión del mantenimiento de la infraestructura física educativa en la Facultad de Contaduría y Administración, Campus I de la UNACH, actualmente se realiza de manera manual y fragmentada. Esto genera ⚠️ retrasos, ineficiencia en la asignación de recursos y dificultades en el seguimiento de actividades, afectando la calidad del servicio y la optimización del mantenimiento.

Se requiere desarrollar un 🖥️ **Sistema de Gestión de Mantenimiento Asistido por Computadora (CMMS)** que permita centralizar, optimizar y priorizar las tareas de mantenimiento de manera eficiente.

### 1.2. 🎯 Objetivos

#### 🎯 Objetivo General

Desarrollar e implementar un sistema de información para la gestión del mantenimiento de la infraestructura física educativa en la Facultad de Contaduría y Administración, Campus I de la UNACH.

#### ✅ Objetivos Específicos

- 🔍 Identificar requerimientos funcionales y no funcionales.
- 🏗️ Definir los servicios de mantenimiento.
- 📊 Analizar el proceso actual de mantenimiento.
- 🖥️ Diseñar la arquitectura del sistema de información.
- 🔐 Evaluar y garantizar la seguridad del sistema.
- 🚀 Implementar el sistema en un entorno real.
- 🧪 Realizar pruebas de funcionamiento y optimización.
- 📈 Definir métricas para evaluar el rendimiento del sistema.
- 🛡️ Implementar medidas de seguridad y respaldo de datos.

## 2️⃣ Especificación de Requerimientos del Proyecto

### 2.1. 📋 Requisitos Generales

- 📆 Finalización dentro del tiempo estimado.
- 💰 Ajuste al presupuesto definido.
- 📑 Documentación completa y detallada.
- 👥 Participación activa del usuario y los involucrados.
- ⚡ Uso de metodologías ágiles, como **SCRUM**.

### 2.2. 🔧 Requisitos Funcionales

- 📝 Registro y gestión de solicitudes de mantenimiento.
- 🔄 Seguimiento del estado de mantenimiento.
- 👷 Asignación de tareas a personal de mantenimiento.
- 📊 Generación de reportes y análisis de datos.
- 🔔 Notificaciones y alertas sobre mantenimientos programados.

### 2.3. 🔒 Requisitos No Funcionales

- 🔐 Seguridad y acceso restringido por roles.
- ⚙️ Alta disponibilidad y estabilidad del sistema.
- 🎨 Interfaz intuitiva y fácil de usar.
- 📱 Compatibilidad con múltiples dispositivos.
- 📈 Escalabilidad para futuras mejoras.

### 2.4. 🎯 Alcance del Sistema

El sistema permitirá gestionar de manera eficiente el mantenimiento de la infraestructura educativa, asegurando el cumplimiento de normativas y optimización de recursos.

## 3️⃣ Procedimientos de Instalación y Prueba

### 3.1. 🛠️ Instalación

- 📝 Desarrollo de un plan de instalación detallado.
- 💾 Implementación en servidores de la universidad.
- 🔧 Configuración de bases de datos y accesos.

### 3.2. 🧪 Especificaciones de Prueba y Ejecución

- ✅ Pruebas unitarias para cada módulo.
- 🔄 Pruebas de integración para verificar la comunicación entre módulos.
- 🎯 Pruebas de aceptación con usuarios finales.
- 📊 Evaluación del rendimiento y carga del sistema.

## 4️⃣ 🏛️ Arquitectura del Sistema

La arquitectura del software seguirá un modelo **modular y escalable**, permitiendo futuras actualizaciones y mejoras. Se utilizarán tecnologías web modernas para garantizar un sistema robusto y eficiente.

## 5️⃣ 🛠️ Herramientas y Metodología de Desarrollo

### Backend 🖥️

- **Lenguaje de Programación:** Python (Django)
- **Frameworks:** Django, Django REST Framework
- **Base de Datos:** PostgreSQL
- **Autenticación y Seguridad:** Encriptación de datos, autenticación multifactor
- **Plan de respaldo:** Políticas de recuperación ante fallos

### Frontend 🎨

- **Lenguaje de Programación:** JavaScript (React)
- **Frameworks y Librerías:** React, Tailwind CSS
- **Estado de la Aplicación:** React Context API / Redux
- **Diseño Responsivo:** Adaptado a múltiples dispositivos

### Desarrollo y Metodología ⚡

- **Metodología de Desarrollo:** SCRUM
- **Control de Versiones:** GitHub

- **🖥️ Lenguajes de Programación:** Python (Django) para el backend, JavaScript (React) para el frontend.
- **💾 Base de Datos:** PostgreSQL.
- **🛠️ Frameworks y Tecnologías:** Django, Django REST Framework, React, Tailwind CSS.
- **⚡ Metodología de Desarrollo:** SCRUM.
- **📂 Control de Versiones:** GitHub.
- **🛡️ Estrategias de seguridad:** Encriptación de datos, autenticación multifactor.
- **🗄️ Plan de respaldo:** Políticas de recuperación ante fallos.

## 6️⃣ 📊 Monitoreo y Mantenimiento del Sistema

- 📡 Implementación de herramientas de monitoreo en tiempo real.
- 🔄 Actualización y mantenimiento periódico del sistema.
- 📋 Evaluación y mejora continua basada en métricas y feedback de usuarios.

# 📂 Estructura del Proyecto 

## 📁 Estructura del Proyecto SMIFE - Frontend (React + Vite + TypeScript)

```plaintext
SMIFE/
├── public/                # Archivos públicos como íconos y favicon
├── src/
│   ├── assets/            # Archivos estáticos como imágenes, fuentes y estilos
│   ├── components/        # Componentes reutilizables como botones, formularios, etc.
│   ├── pages/             # Vistas principales del sistema
│   ├── lib/               # Lógica para APIs y manejo de datos
│   └── main.tsx           # Archivo de entrada principal de la app
├── package.json           # Dependencias y scripts de npm
├── vite.config.ts         # Configuración de Vite
└── tsconfig.json          # Configuración de TypeScript
```

---

## 🚀 Instalación del Frontend

Sigue estos pasos para instalar y ejecutar el proyecto localmente.

### 📋 Prerrequisitos

Asegúrate de tener instalados:

- Node.js (versión 20 o superior)
- npm (incluido con Node.js)

Verifica las versiones ejecutando en la terminal:

```bash
node -v    # Versión de Node.js
npm -v     # Versión de npm
```

### 🔧 Pasos de Instalación

1. Navega al directorio del proyecto:

```bash
cd smife
```

2. Instala las dependencias:

```bash
npm install
```

3. Inicia el servidor de desarrollo:

```bash
npm run dev -- --open
```

Esto abrirá la aplicación en tu navegador predeterminado.

4. Compilar para producción:

Para crear una versión optimizada para producción, usa:

```bash
npm run build
```

---

## 📁 Estructura del Proyecto SMIFE_API - Backend (Python + FastAPI)

```plaintext
SMIFE_API/
├── app/
│   ├── __init__.py         # Indicador de paquete Python
│   ├── auth.py             # Módulo de autenticación
│   ├── repositories/       # Funciones CRUD para la base de datos
│   ├── router/             # Rutas de la API
│   ├── database.py         # Configuración de conexión a la BD
│   ├── main.py             # Punto de entrada de FastAPI
│   ├── models.py           # Modelos de datos para la BD
│   └── schemas.py          # Validación y serialización de datos
├── uploads/                # Carpeta de archivos subidos por usuarios
└── requirements.txt        # Dependencias de Python
```

---

## 🚀 Instalación del Backend

### 📋 Prerrequisitos Python

Asegúrate de tener instalados:

- Python (versión 3.12.4 o superior)
- pip (incluido con Python)

Verifica la instalación:

```bash
python --version   # Versión de Python
pip --version      # Versión de pip
```

### 🔧 Pasos de Instalación

1. Navega al directorio del proyecto:

```bash
cd smife_api
```

2. (Opcional) Crea un entorno virtual:

```bash
# En Windows
python -m venv venv
venv\Scripts\activate

# En macOS y Linux
python3 -m venv venv
source venv/bin/activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Inicia el servidor de desarrollo:

```bash
uvicorn app.main:app --reload
```

Esto ejecutará la API en modo de desarrollo en http://127.0.0.1:8000.

#### Documentacion

- http://127.0.0.1:8000/docs

---

## 🧩 Tecnologías Utilizadas

- **Frontend**: React, Vite, TypeScript, TailwindCSS, react-router-dom
- **Backend**: FastAPI, Python 3.12.4
- **Base de Datos**: PostgreSQL 16
- **Autenticación**: JWT
- **Dependencias Adicionales**: react-toastify para notificaciones, react-icons para íconos

## 💡 Funcionalidades Clave

- **Gestión de Infraestructura**: Manejo eficiente del inventario de infraestructura educativa.
- **Mantenimiento Preventivo y Correctivo**: Programación de mantenimientos.
- **Cargar y Almacenar Imágenes**: Guardado seguro de archivos subidos por usuarios.
- **Roles y Permisos**: Gestión de accesos y permisos.

---

## 7️⃣ 🏷️ Información de Autoría y Legacy del Proyecto

Este proyecto forma parte de una iniciativa académica para mejorar la gestión del mantenimiento en la Facultad de Contaduría y Administración, Campus I de la UNACH. La implementación se basará en estudios previos y mejores prácticas en sistemas de mantenimiento asistidos por computadora (**CMMS**).

✅ **Este documento proporciona un marco estructurado para el desarrollo del sistema de mantenimiento, asegurando claridad en los objetivos, requisitos y metodología.** 🚀
