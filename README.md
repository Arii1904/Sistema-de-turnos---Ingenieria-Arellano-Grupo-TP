🚗 Sistema de Gestión de Turnos para Lavadero de Autos

Sistema web desarrollado para la administración y reserva de turnos de un lavadero de autos. Permite gestionar clientes, reservas y disponibilidad de horarios de manera simple y eficiente.

📋 Descripción

Esta aplicación facilita la organización de turnos para un lavadero de autos, evitando superposiciones y permitiendo una mejor administración de los servicios ofrecidos.

✨ Funcionalidades
Inicio de sesión de usuarios.
Generación y gestión de turnos.
Visualización de turnos registrados.
Control de disponibilidad horaria.
Persistencia de datos mediante base de datos SQLite.
Interfaz web sencilla e intuitiva.

🛠️ Tecnologías Utilizadas
Node.js
Express.js
SQLite
HTML
JavaScript
📂 Estructura del Proyecto
├── login.html               # Pantalla de inicio de sesión
├── server.js                # Servidor principal
├── lavadero.db              # Base de datos SQLite
├── package.json             # Dependencias y configuración
├── package-lock.json
├── INICIAR_LAVADERO.bat     # Script para iniciar la aplicación
└── .gitignore
🚀 Instalación
Clonar el repositorio:
git clone https://github.com/Arii1904/nombre-del-repositorio.git
Ingresar al directorio:
cd nombre-del-repositorio
Instalar dependencias:
npm install
Ejecutar la aplicación:
node server.js

O bien ejecutar:

INICIAR_LAVADERO.bat
💾 Base de Datos

La aplicación utiliza SQLite como motor de base de datos local mediante el archivo:

lavadero.db
📖 Uso
Iniciar la aplicación.
Acceder desde el navegador.
Iniciar sesión.
Gestionar turnos y reservas del lavadero.
🎯 Objetivo del Proyecto

Este proyecto fue desarrollado con fines de aprendizaje y práctica en el desarrollo de aplicaciones web, aplicando conceptos de:

Desarrollo Backend con Node.js.
Manejo de bases de datos SQLite.
Gestión de reservas y turnos.
Diseño de interfaces web.
Control de persistencia de datos.
# 🚗✨ INSTRUCCIONES PARA ABRIR LA APP DEL LAVADERO

## 🛠️ PASO 1 — Instalar Node.js (solo la primera vez)

1. Ingresá a **https://nodejs.org**
2. Descargá la versión **LTS** (recomendada).
3. Instalala como cualquier programa:

   * Siguiente ➜ Siguiente ➜ Finalizar.

✅ Este paso se realiza **una sola vez**.

---

## 📥 PASO 2 — Descargar la carpeta del proyecto

1. Descargá la carpeta **"lavadero"** completa desde Drive.
2. Guardala en una ubicación fácil de encontrar (por ejemplo, el Escritorio).

---

## 📦 PASO 3 — Instalar las dependencias (solo la primera vez)

1. Abrí la carpeta **lavadero**.
2. Hacé clic en la barra superior donde aparece la ruta de la carpeta.
3. Borrá el contenido y escribí:

```cmd
cmd
```

4. Presioná **Enter**.
5. Se abrirá una ventana de comandos.
6. Escribí:

```cmd
npm install
```

7. Presioná **Enter** y esperá a que finalice la instalación.

✅ Este paso también se realiza **una sola vez**.

---

## ▶️ PASO 4 — Abrir la aplicación

1. Hacé doble clic en:

```text
INICIAR_LAVADERO.bat
```

2. Automáticamente se iniciará el sistema y se abrirá el navegador con la aplicación lista para usar. 🎉

---

# 👤 Usuarios de prueba

| Rol              | Usuario                                               | Contraseña |
| ---------------- | ----------------------------------------------------- | ---------- |
| 👑 Administrador | [admin@lavadero.com](mailto:admin@lavadero.com)       | admin      |
| 👨‍🔧 Empleado   | [empleado@lavadero.com](mailto:empleado@lavadero.com) | empleado   |
| 💰 Cajero        | [cajero@lavadero.com](mailto:cajero@lavadero.com)     | cajero     |
| 🚗 Cliente       | [cliente@lavadero.com](mailto:cliente@lavadero.com)   | cliente    |

---

# ⚠️ Importante

🔹 Los pasos **1** y **3** se realizan **solo la primera vez**.

🔹 Después de la instalación inicial, para usar el sistema únicamente tenés que ejecutar:

```
INICIAR_LAVADERO.bat
```

✨ ¡Y listo! El sistema se abrirá automáticamente en tu navegador.


👩‍💻 Autores de desarrollo:Bettina Gomez y Leandro Serrudo
Autora de readme: Ariadna Villagra
Autor de revisión: Roberto Villca
