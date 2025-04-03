# 💵 MyFinance

**MyFinance** es una plataforma de gestión financiera personal que permite a los usuarios administrar sus ingresos, egresos y metas financieras de manera sencilla y segura.

## 🚀 Características Principales

✅ **Autenticación Segura**: Sistema de autenticación con JWT y recuperación de contraseña.  
✅ **Panel de Control**: Gráficos interactivos con resumen financiero mensual.  
✅ **Gestión de Movimientos**: Registro de ingresos, egresos y metas financieras.  
✅ **Planificación Financiera**: Calendario para programar eventos financieros.  
✅ **Personalización**: Configuración de etiquetas y temas de colores.

## 📂 Estructura del Proyecto

El proyecto está dividido en varios microservicios independientes:

| Módulo                | Descripción                                     |
| --------------------- | ----------------------------------------------- |
| `myfinance-front`     | Interfaz de usuario y panel de control.         |
| `myfinance-user`      | Gestión de usuarios y autenticación.            |
| `myfinance-movements` | Registro y manejo de transacciones financieras. |
| `myfinance-planning`  | Planificación financiera y metas de ahorro.     |
| `myfinance-config`    | Personalización de la interfaz y ajustes.       |

## 📥 Instalación

Para clonar el proyecto con todos los módulos:

```bash
git clone --recurse-submodules https://github.com/MONTESDANIEL/myfinance.git
cd myfinance
git submodule update --init --recursive
```

## 🔧 Instalación del Backend

Para cada uno de los módulos:

```bash
cd myfinance-module_name
npm install
npm start
```

## 🎨 Instalación del Frontend

Unicamente para el módulo myfinance-front:

```bash
cd myfinance-front
npm install
npm run dev
```

## 📱 Pantallas de la Aplicación

| **Pantalla**          | **Descripción**                                 |
| --------------------- | ----------------------------------------------- |
| **Welcome**           | Pantalla de bienvenida con información inicial. |
| **Login**             | Formulario de inicio de sesión.                 |
| **Create Account**    | Registro de nuevos usuarios.                    |
| **Password Recovery** | Recuperación de contraseña vía email.           |
| **Home**              | Panel con estadísticas y gráficos.              |
| **Management**        | Gestión de movimientos financieros.             |
| **User**              | Perfil del usuario con opciones de edición.     |
| **Config**            | Personalización de etiquetas y colores.         |

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo LICENSE.

## 📬 Contacto

📧 Email: danielamayamontes8@gmail.com

🔗 GitHub: [MONTESDANIEL](https://github.com/MONTESDANIEL)
