# Sistema de Gestión de Eventos Culturales – Valdivia

Integrantes: Sebastian Ahumada y Agustin Fernandez

## Descripción del proyecto

Sistema web orientado a mejorar la planificación, administración y seguimiento de los eventos culturales de la Municipalidad de Valdivia, específicamente del Área de Cultura.

La propuesta busca centralizar la información de eventos, recintos, participantes, inscripciones y proveedores, facilitando la coordinación de actividades y la generación de reportes.

El proyecto se desarrolla progresivamente, considerando las etapas de planificación, análisis, diseño, implementación y seguimiento.

## Objetivo

Desarrollar una plataforma web que permita organizar los eventos culturales, administrar recintos, controlar cupos e inscripciones y facilitar el acceso a información para la toma de decisiones.

## Funcionalidades del prototipo

- **Panel principal:** visualización de indicadores, calendario, eventos y tareas administrativas.
- **Gestión de eventos:** creación, consulta, modificación y eliminación de eventos de demostración.
- **Gestión de recintos:** consulta de espacios, capacidades y disponibilidad.
- **Inscripciones:** registro de participantes y control de cupos.
- **Proveedores:** administración de proveedores de ejemplo.
- **Reportes:** visualización de indicadores y exportación de información a Excel.
- **Usuarios y roles:** visualización de los perfiles y permisos propuestos.
- **Cartelera ciudadana:** consulta de actividades e inscripción de demostración.

El prototipo incorpora validaciones para evitar conflictos de horarios, sobrepasar capacidades y registrar inscripciones duplicadas.

## Tecnologías utilizadas

| Tecnología | Utilización |
|---|---|
| HTML5 | Estructura de las páginas |
| CSS3 | Diseño visual y adaptación a dispositivos |
| JavaScript | Funcionalidades e interacciones |
| LocalStorage | Almacenamiento local de datos de prueba |
| SheetJS | Exportación de reportes Excel |
| GitHub Pages | Publicación del prototipo web |

## Diseño y arquitectura

El proyecto cuenta con una propuesta de arquitectura lógica y un modelo entidad-relación para la futura implementación de la base de datos.

El modelo contempla nueve entidades principales: Usuario, Rol, Evento, Recinto, Participante, Inscripción, Entrada, Proveedor y Evento_Proveedor.

Actualmente se encuentra desarrollado el prototipo frontend. La implementación del backend, la base de datos centralizada, la autenticación y las integraciones externas forman parte de las siguientes etapas.
