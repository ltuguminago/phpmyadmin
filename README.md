# PhpMyAdmin - Docker
Desplegar una infraestructura de MySQL + phpMyAdmin usando contenedores, redes y volúmenes.
## Integrantes
| Nombre | Cargo | URL GitHub |
|---|---|---|
| Daniel Alquinga | 🐛 Desarrollador | https://github.com/superdavi/Practica1_Grupo2.git |
| Daniel Baldeon | 🐛 Desarrollador | https://github.com/debpdhs/Practica1_Grupo2 |
| Bryan Miño | 🐺 Desarrollador |https://github.com/bmiomi/tareadocker |
| Wilson Segovia | 🐛 Desarrollador | https://github.com/segoviawilson/Practica1_Grupo2.git|
| Leonardo Tuguminago | 🐛 Desarrollador | https://github.com/Tuguminago/Proyectos.git |

#  Sistema de Gestión de Vehículos con Docker
Este proyecto implementa un sistema de gestión de vehículos utilizando Docker, MySQL y phpMyAdmin. El sistema permite administrar propietarios y sus vehículos mediante una base de datos relacional.

## Arquitectura del Sistema
- **Red en Docker**: Docker no solo aísla procesos en contenedores, también abstrae la red para que los contenedores puedan comunicarse entre sí, con el host y con el exterior.
- **volúmes**: Gestionados por Docker y almacenados en /var/lib/docker/volumes/.
- **MySQL 8.3**: Base de datos para almacenar información de propietarios y vehículos
- **phpMyAdmin 5.2.2**: Interfaz web para administración de la base de datos

## Estructura del Proyecto
