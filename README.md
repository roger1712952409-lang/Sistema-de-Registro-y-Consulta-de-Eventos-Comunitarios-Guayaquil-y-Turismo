# Sistema de Registro y Consulta de Eventos Comunitarios Guayaquil y Turismo

![Status](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow?style=flat-square)
![Version](https://img.shields.io/badge/Versión-0.1-blue?style=flat-square)
![License](https://img.shields.io/badge/Licencia-Académico-green?style=flat-square)

## 📋 Descripción

Una aplicación web innovadora diseñada para facilitar el registro, administración y consulta de eventos comunitarios, culturales, deportivos y turísticos de la ciudad de Guayaquil. 

La plataforma proporciona a ciudadanos y turistas acceso centralizado a información actualizada sobre eventos, incluyendo ubicación, fecha, horario, organizador y descripción completa. **Nuestro objetivo es promover la participación ciudadana y el turismo local en Guayaquil.**

---

## 🎯 Objetivo General

Desarrollar una aplicación web intuitiva para registrar y consultar eventos comunitarios y turísticos de la ciudad de Guayaquil, facilitando el acceso a información actualizada, organizada y confiable.

---

## 🎪 Objetivos Específicos

- ✅ Registrar nuevos eventos comunitarios y turísticos
- ✅ Consultar eventos por categoría, fecha o ubicación
- ✅ Administrar la información de los eventos de forma centralizada
- ✅ Promover las actividades culturales y turísticas de Guayaquil
- ✅ Facilitar el acceso a información confiable para ciudadanos y visitantes

---

## ⚙️ Funcionalidades Principales

| Funcionalidad | Descripción |
|---|---|
| 📝 Registro de Eventos | Crear nuevos eventos con información completa |
| 🔍 Búsqueda Avanzada | Filtrar por categoría, fecha, ubicación |
| 📍 Visualización de Detalles | Información detallada de cada evento |
| 👨‍💼 Administración | Panel de control para gestionar eventos |
| 🗺️ Mapa Interactivo | Localización geográfica de eventos |

---

## 💻 Tecnologías Utilizadas

```
Frontend:
  • HTML5
  • CSS3
  • JavaScript

Backend:
  • PHP 7.4+
  • MySQL 5.7+

Control de Versiones:
  • Git
  • GitHub
```

---

## 📁 Estructura del Proyecto

```
proyecto/
├── index.php                 # Página principal
├── css/                      # Estilos del proyecto
│   └── styles.css
├── js/                       # Scripts de JavaScript
│   └── main.js
├── php/                      # Lógica del backend
│   ├── conexion.php
│   ├── registro.php
│   └── consulta.php
├── database/                 # Archivos de base de datos
│   └── eventos.sql
└── README.md
```

---

## 🚀 Instalación y Configuración

### Requisitos Previos
- PHP 7.4 o superior
- MySQL 5.7 o superior
- Servidor web (Apache, Nginx)
- Git

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/roger1712952409-lang/Sistema-de-Registro-y-Consulta-de-Eventos-Comunitarios-Guayaquil-y-Turismo.git
cd Sistema-de-Registro-y-Consulta-de-Eventos-Comunitarios-Guayaquil-y-Turismo
```

2. **Crear la base de datos**
```bash
mysql -u root -p < database/eventos.sql
```

3. **Configurar conexión**
- Editar `php/conexion.php` con tus credenciales de MySQL

4. **Ejecutar en servidor local**
```bash
php -S localhost:8000
```

Acceder a: `http://localhost:8000`

---

## 📖 Guía de Uso

### Para Ciudadanos y Turistas
1. Ingresar a la plataforma
2. Ver eventos disponibles en el calendario
3. Filtrar por categoría, fecha o ubicación
4. Ver detalles completos del evento de interés

### Para Administradores
1. Acceder con credenciales
2. Crear nuevos eventos
3. Editar información de eventos existentes
4. Gestionar categorías y ubicaciones

---

## 👥 Integrantes del Equipo

| Nombre | Rol |
|--------|-----|
| Alisson Jurado Zea | Developer |
| Carlos Brito Guaman | Developer |
| Karla Ramos Pimentel | Developer |
| María Rivera | Diseño |
| María Lema Casco | QA |
| Roger Beltrán Palma | Líder de Proyecto |

---

## 📊 Estado del Proyecto

**Versión 0.1 - 25% de avance**

### Completado ✅
- ✓ Creación del repositorio en GitHub
- ✓ Elaboración del README
- ✓ Definición del tema y objetivos
- ✓ Organización inicial del proyecto
- ✓ Inicio del desarrollo del sistema
- ✓ Primeros commits de los integrantes

### En Progreso 🔄
- ⏳ Desarrollo del frontend
- ⏳ Desarrollo del backend
- ⏳ Base de datos

### Próximas Tareas 📋
- Base de datos completamente funcional
- Sistema de autenticación
- Pruebas unitarias
- Deployment

---

## 🤝 Contribuir

Para contribuir al proyecto:

1. Crear una rama para tu feature (`git checkout -b feature/AmazingFeature`)
2. Hacer commit de tus cambios (`git commit -m 'Add AmazingFeature'`)
3. Push a la rama (`git push origin feature/AmazingFeature`)
4. Abrir un Pull Request

**Por favor, asegurate de:**
- Seguir las convenciones de código del equipo
- Documentar los cambios significativos
- Probar tu código localmente antes de hacer push

---

## 📝 Licencia

Proyecto académico desarrollado para la asignatura **Ingeniería de Software I**

**Universidad Agraria del Ecuador**  
Carrera: Ciencias de la Computación

---

## 📧 Contacto y Soporte

Para preguntas o reportar problemas:
- Abrir un [Issue](https://github.com/roger1712952409-lang/Sistema-de-Registro-y-Consulta-de-Eventos-Comunitarios-Guayaquil-y-Turismo/issues)
- Contactar al líder del proyecto

---

**Última actualización:** Julio 2026
