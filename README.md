ConsulMediDB
Objetivo
Gestionar de manera eficiente la información relacionada con pacientes, médicos, consultas y citas médicas.

Problema que Resuelve
Reduce errores administrativos y mejora la organización de la información clínica.

Funcionalidades Principales
Registro de pacientes
Registro de médicos
Gestión de citas
Gestión de consultas
Búsquedas de información
Actualización de registros
Eliminación de registros
Arquitectura
Arquitectura de Tres Capas:

Presentación
Lógica de Negocio
Acceso a Datos
Herramientas Utilizadas
C#
Windows Forms
SQL Server
ADO.NET
Visual Studio Community
Git
GitHub
Visual Paradigm
Estado Actual
Versión inicial funcional desarrollada para fines académicos.

Organización Frontend y Backend
Frontend
La capa Frontend corresponde a la interfaz gráfica desarrollada en Windows Forms. Permite al usuario registrar, consultar, modificar y eliminar información del sistema.

Backend
La capa Backend contiene las reglas de negocio y el acceso a datos. Se encarga de procesar la información y comunicarse con SQL Server.

Comunicación entre capas
La comunicación entre Frontend y Backend se realiza mediante ADO.NET, permitiendo ejecutar consultas y operaciones CRUD en la base de datos.

Registro de Cambios
Creación de la base de datos ConsulMediDB.
Diseño del modelo entidad-relación.
Implementación del módulo de pacientes.
Implementación del módulo de médicos y citas.
Integración de operaciones CRUD mediante ADO.NET.
Estado de la Versión
Versión: 1.0

Características implementadas:

Gestión de pacientes.
Gestión de médicos.
Gestión de citas.
Conexión a SQL Server.
Operaciones CRUD funcionales.
Próximas mejoras:

Generación de reportes PDF.
Sistema de copias de seguridad.
Optimización de consultas SQL.
Mejoras de seguridad.
