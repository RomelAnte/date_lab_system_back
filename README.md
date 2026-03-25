# Date Lab System - Backend

Sistema backend para la plataforma Date Lab System. API REST construida con Node.js y Express, con soporte para PostgreSQL.

## 📋 Descripción del Proyecto

Este proyecto es el servidor backend de Date Lab System. Proporciona endpoints RESTful para gestionar usuarios, citas y datos relacionados. Utiliza Express como framework web, Objection.js con Knex para ORM/query builder, y PostgreSQL como base de datos.

## 🚀 Características Principales

- API REST con Express.js
- ORM con Objection.js
- Query builder con Knex.js
- Soporte para PostgreSQL
- Reloading automático en desarrollo con Nodemon
- Pool de conexiones optimizado

## 📦 Dependencias Instaladas

### Dependencias Principales

| Paquete | Versión | Descripción |
|---------|---------|-------------|
| **express** | ^5.2.1 | Framework web rápido y flexible para Node.js |
| **pg** | ^8.20.0 | Cliente PostgreSQL para Node.js |
| **objection** | ^3.1.5 | ORM ligero y flexible basado en SQL |
| **knex** | ^3.2.3 | Query builder SQL para Node.js |
| **nodemon** | ^3.1.14 | Herramienta para reiniciar automáticamente la aplicación en desarrollo |

### Dependencias Secundarias

| Paquete | Versión | Descripción |
|---------|---------|-------------|
| **tarn** | ^3.0.2 | Gestor de pool de conexiones |
| **tildify** | ^2.0.0 | Convierte rutas absolutas a rutas con tilde |
| **to-regex-range** | ^5.0.1 | Convierte rangos numéricos a expresiones regulares |
| **toidentifier** | ^1.0.1 | Convierte strings a identificadores CSS válidos |
| **touch** | ^3.1.1 | Implementación de comando touch para Node.js |
| **type-is** | ^2.0.1 | Detecta tipos MIME en headers |
| **undefsafe** | ^2.0.5 | Acceso seguro a propiedades anidadas |
| **unpipe** | ^1.0.0 | Herramienta para desconectar streams |
| **vary** | ^1.1.2 | Manejo del header Vary |
| **wrappy** | ^1.0.2 | Wrapper para funciones |
| **xtend** | ^4.0.2 | Utilidad para extender objetos |

## 🛠️ Configuración y Scripts

### Scripts Disponibles

```json
{
  "test": "echo \"Error: no test specified\" && exit 1"
}
```

> **Nota**: Los scripts de test aún no están configurados.

### Scripts Recomendados

Para ejecutar en desarrollo:
```bash
npm run dev  # (requiere configuración en package.json)
```

Para instalar dependencias:
```bash
npm install
```

## 📁 Estructura del Proyecto

```
date_lab_system_back/
├── package.json          # Configuración del proyecto
├── README.md             # Este archivo
└── [otros archivos...]   # (completar según sea necesario)
```

## 🔧 Requisitos Previos

- Node.js (versión 14 o superior)
- npm (versión 6 o superior)
- PostgreSQL (versión 12 o superior)

## 📥 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/RomelAnte/date_lab_system_back.git
cd date_lab_system_back
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura las variables de entorno (crear archivo `.env`):
```bash
DATABASE_URL=postgresql://usuario:contraseña@localhost:5432/date_lab
PORT=3000
NODE_ENV=development
```

4. Ejecuta la aplicación:
```bash
npm start
# O en desarrollo con reloading automático:
npx nodemon index.js
```

## 🗄️ Base de Datos

Este proyecto utiliza **PostgreSQL** como gestor de base de datos. 

### Herramientas de Base de Datos

- **Knex.js**: Query builder para construcción de consultas SQL
- **Objection.js**: ORM que proporciona modelos de datos con validaciones
- **pg**: Driver nativo de PostgreSQL para Node.js

### Configuración de Conexión

La conexión a la base de datos se gestiona a través de un pool de conexiones configurado con **Tarn** para optimizar el uso de recursos.

## 📝 Información del Repositorio

- **Repositorio**: [GitHub - RomelAnte/date_lab_system_back](https://github.com/RomelAnte/date_lab_system_back)
- **Licencia**: ISC
- **Autor**: RomelAnte
- **Versión**: 1.0.0

## 🐛 Reporte de Problemas

Si encuentras problemas o errores, por favor crea un issue en:
[GitHub Issues](https://github.com/RomelAnte/date_lab_system_back/issues)

## 📚 Documentación Útil

- [Express.js Documentation](https://expressjs.com/)
- [Objection.js Documentation](https://vincit.github.io/objection.js/)
- [Knex.js Documentation](https://knexjs.org/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [node-postgres (pg) Documentation](https://node-postgres.com/)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un PR con tus cambios.

---

**Última actualización**: Marzo 2026