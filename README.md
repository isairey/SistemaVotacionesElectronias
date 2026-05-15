<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" />

# 🗳️ VotaMX

### Sistema de votaciones electrónicas y gestión electoral 🚀

<p align="center">
  <b>VotaMX</b> es una plataforma web diseñada para la administración de procesos electorales, votaciones electrónicas y control de jornadas electorales mediante una interfaz moderna, segura y organizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Sistema-Votaciones-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Security-Electoral-blue?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**VotaMX** es un sistema web enfocado en la realización de votaciones electrónicas y administración de procesos electorales digitales.

La plataforma permite:

- 🗳️ Registro de votaciones
- 👥 Gestión de votantes
- 🏢 Administración de casillas
- 🧑‍💼 Gestión de funcionarios
- 🏛️ Administración de partidos políticos
- 📊 Reportes electorales
- 🔐 Control de acceso y autenticación
- 📋 Gestión de jornadas electorales

El proyecto fue desarrollado para practicar:

- Desarrollo web con Laravel
- Bases de datos relacionales
- Arquitectura MVC
- Sistemas de autenticación
- Seguridad informática
- Procesos electorales digitales

---

# ✨ Características

## 🗳️ Sistema de votaciones

- 🧾 Registro electrónico de votos
- 🔐 Validación de votantes
- ⚡ Proceso rápido de votación
- 📊 Conteo automatizado
- 🏛️ Gestión electoral

---

## 👥 Gestión de usuarios

- 👨‍💼 Administradores
- 🧑 Funcionarios de casilla
- 🗳️ Votantes
- 🔑 Inicio de sesión
- 🛡️ Control de permisos

---

## 🏛️ Administración electoral

- 📅 Jornadas electorales
- 📍 Lugares de votación
- 🏢 Casillas
- 🧑‍💼 Funcionarios
- 🏷️ Partidos políticos
- 👤 Candidatos

---

## 📊 Reportes

- 📈 Estadísticas electorales
- 📋 Resultados de votación
- 🧾 Reportes administrativos
- 🗂️ Gestión de información
- 📄 Exportación de datos

---

## 🔒 Seguridad

- 🔑 Autenticación de usuarios
- 🛡️ Protección de sesiones
- 🔐 Validación de acceso
- 📄 Integridad de información
- 👨‍💻 Gestión de privilegios

---

# 🛠️ Tecnologías utilizadas

## 🌐 Backend

<p>
  <img src="https://skillicons.dev/icons?i=php,laravel" />
</p>

- PHP
- Laravel
- Blade Templates
- MVC

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- SQL
- Gestión relacional

---

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap" />
</p>

- HTML5
- CSS3
- JavaScript
- Bootstrap

---

## 🐳 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- VS Code

---

# 📂 Estructura del proyecto

```bash
SistemaVotacionesElectronias/
│
├── app/
│   ├── views/
│   │   ├── administrador/
│   │   ├── votante/
│   │   ├── funcionariosdecasilla/
│   │   ├── reportes/
│   │   └── layouts/
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── database/
│   └── DBSistema.sql
│
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP
- Laravel
- MySQL
- Composer
- Apache o Nginx

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/SistemaVotacionesElectronias.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd SistemaVotacionesElectronias
```

---

## 3️⃣ Configurar base de datos

```bash
mysql -u root -p < DBSistema.sql
```

---

## 4️⃣ Crear usuario de base de datos

```sql
CREATE USER 'seguridad'@'localhost' IDENTIFIED BY 'seguridad';

GRANT ALL PRIVILEGES ON DBSistema.* TO 'seguridad'@'localhost';
```

---

## 5️⃣ Ejecutar proyecto

```bash
php artisan serve
```

---

# 👨‍💻 Usuario administrador

## 🔑 Credenciales por defecto

```bash
Usuario: administrador
Password: 123456
```

---

# 🗳️ Módulos principales

## 👨‍💼 Administrador

- 📅 Crear jornadas
- 📍 Registrar lugares
- 🏢 Crear casillas
- 🧑‍💼 Gestionar funcionarios
- 🏛️ Registrar partidos
- 👤 Registrar candidatos

---

## 🧑‍💼 Funcionarios de casilla

- 🔑 Login de funcionarios
- 📋 Validación de votantes
- 🗳️ Supervisión electoral

---

## 🗳️ Votante

- 🔑 Validación con clave electoral
- 👤 Visualización de candidatos
- ✅ Confirmación de voto
- 📄 Agradecimiento de participación

---

# 🎨 Layouts y vistas

## 📂 Sistema de layouts Blade

Para reutilizar plantillas:

```php
@extends('layouts.layoutbase')

@section('body')
    <!-- HTML -->
@endsection
```

---

## ⚡ Secciones disponibles

```php
@section('css')
@endsection

@section('javascript')
@endsection
```

---

# 🔄 Flujo Git recomendado

## 📥 Descargar cambios

```bash
git pull
```

---

## 📤 Subir cambios

```bash
git status
git add *
git commit -m "mensaje"
git push
```

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://images.unsplash.com/photo-1529107386315-e1a2ed48a620?q=80&w=1200&auto=format&fit=crop" />

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Laravel
- Sistemas electorales
- Seguridad web
- MySQL
- Blade Templates
- Arquitectura MVC
- Gestión de usuarios

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- 🔐 Doble autenticación
- ☁️ Deploy cloud
- 📊 Dashboard avanzado
- 🧠 IA para análisis electoral
- 📄 Reportes PDF
- 🌎 Multi-región

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Autor

<div align="center">

## Isai Reyes — Plataforma de votaciones electrónicas

Sistema desarrollado para la administración moderna de procesos electorales digitales 🇲🇽

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto educativo desarrollado para prácticas de sistemas electorales, seguridad informática y plataformas de votación electrónica.

---

<div align="center">

### 🗳️ VotaMX — tecnología aplicada a procesos electorales modernos 🚀

</div>
