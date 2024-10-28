<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/blob/main/ic0n%24/logo-rem.svg" width="400" alt="Laravel Logo"></a></p>

# 💸 Sistema de Control de Gastos Personales
Versión Móvil, TV y Watch 📱📺⌚
<!--<a href="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://github.com/Eros-Adrian-Figueroa-Cortes/"><img src="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/blob/main/ic0n%24/00001.svg" alt="User"></a>
<a href="https://github.com/DANYTY-18"><img src="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/blob/main/ic0n%24/00001.svg" alt="User"></a>
<a href="https://github.com/JarethCastells"><img src="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/blob/main/ic0n%24/00001.svg" alt="User"></a>
<a href="https://github.com/Eros-Adrian-Figueroa-Cortes/"><img src="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/blob/main/ic0n%24/00001.svg" alt="User"></a>
<a href="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech"><img src="https://github.com/Eros-Adrian-Figueroa-Cortes/fintech/blob/main/ic0n%24/00002.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>-->
---

## 🎯 Objetivo del Proyecto
Este proyecto es una aplicación multiplataforma diseñada para ayudar a los usuarios a gestionar sus gastos personales de manera eficaz y sencilla. Los objetivos principales incluyen:
- **Reportes detallados** 📊
- **Análisis de presupuestos** 📈
- **Herramientas de administración financiera** 💰

#### Compatible con:
- **Dispositivos Móviles** 📱
- **Televisores Inteligentes** 📺
- **Relojes Inteligentes** ⌚

---

## 🔍 Funcionalidades Principales

### 1. 👥 Gestión de Usuarios
   - Registro e inicio de sesión mediante el sistema de **autenticación de Laravel** 🔐.
   - Cada usuario gestionará sus propios gastos y presupuestos, con reportes personalizados disponibles en móvil, TV y reloj inteligente.

### 2. 💵 Gestión de Gastos
   - Registro de gastos diarios en categorías como **alimentación, transporte y entretenimiento**.
   - Agregar descripciones, fechas y montos de cada gasto, almacenándolos en **PostgreSQL**.
   - Edición y visualización de gastos desde dispositivos móviles, TV y reloj inteligente.

### 3. 💳 Gestión de Presupuestos
   - Establecimiento de **presupuestos mensuales** para diferentes categorías.
   - Alertas automáticas en todos los dispositivos cuando los gastos se acercan o superan el presupuesto.

### 4. 🔒 Seguridad y Autenticación
   - Autenticación segura con Laravel y validaciones en la interfaz de usuario.
   - Protección de datos para todos los dispositivos compatibles.

### 5. 🔌 Soporte Offline
   - Persistencia de datos en la app móvil con **SQLite** para que funcione sin conexión.
   - Sincronización automática con el backend en Laravel al restablecer la conectividad.

### 6. 🖥️ Interfaz Adaptativa
   - Interfaz **responsiva** adaptada para pantallas de móvil, TV y reloj.
   - Experiencia de usuario optimizada para cada tipo de dispositivo.

---

## ⚙️ Requisitos Técnicos

### Backend en Laravel con PostgreSQL
- **Laravel** gestionará la lógica del servidor, la seguridad y el almacenamiento de datos en **PostgreSQL**.
- Utilización de **APIs RESTful** para la comunicación entre Flutter y Laravel.

### Desarrollo en Flutter
- Interfaz de usuario con **Flutter**, compatible con **móviles, televisores y relojes inteligentes**.
- Implementación de la **persistencia de datos local** y sincronización con el backend cuando haya conectividad.

### Categorización y Análisis de Gastos
- Sistema de **categorización y análisis de gastos** basado en PostgreSQL.
- Generación de reportes detallados y visualización de tendencias en todos los dispositivos.

---

## 🚀 Cómo Empezar

1. **Clonar el Repositorio**
   ```bash
   https://github.com/Eros-Adrian-Figueroa-Cortes/fintech
   cd fintech

##  Instalación del Backend (Laravel)

2. **Configuracion Laravel**
cd backend
cp .env.example .env
composer install
php artisan key:generate

3. **Configurar la Base de Datos en .env y Migrar**
php artisan migrate
php artisan serve

4. **Instalación del Frontend (Flutter)**
cd ../frontend
flutter pub get
flutter run
---

### Contributors 

- **[Adrian Cortes](https://vehikl.com/)**
- **[Daniel Mendoza](https://github.com/DANYTY-18)**
- **[Jareth Montalvo](https://github.com/JarethCastells)**
- **[Monserrat Vite]()**

---
#### 🤝 Contribuir
¡Gracias por tu interés en contribuir! Puedes abrir un issue o enviar un pull request para mejoras y correcciones.
---
Nota: Para cualquier problema o sugerencia, no dudes en contactar a los desarrolladores o abrir un issue en el repositorio


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
