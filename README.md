# DB Reliability Lab

Laboratorio práctico de administración y confiabilidad de bases de datos orientado a formación DBA/DBRE.

## Objetivo

Construir un entorno reproducible para desplegar, administrar, asegurar, respaldar, restaurar, monitorear y diagnosticar distintos motores de bases de datos.

## Tecnologías

- Fedora Linux
- Docker
- Docker Compose
- Oracle Database
- PostgreSQL
- MySQL / MariaDB
- MongoDB
- Redis
- Python
- Bash
- Prometheus
- Grafana
- Git
- GitHub
- GitHub Actions

## Estructura

- `oracle/`: laboratorios Oracle
- `postgresql/`: laboratorios PostgreSQL
- `mysql/`: laboratorios MySQL/MariaDB
- `mongodb/`: laboratorios MongoDB
- `redis/`: laboratorios Redis
- `monitoring/`: Prometheus, Grafana y exporters
- `automation/`: scripts Python
- `scripts/`: utilidades Bash
- `incidents/`: simulaciones y runbooks
- `docs/`: documentación técnica
- `docker/`: configuraciones compartidas
- `backups/`: estructura local para respaldos no versionados

## Estrategia Git

- `main`: versiones estables
- `develop`: integración
- `feature/*`: funcionalidades y laboratorios

## Estado actual

### Módulo 0

- Docker Engine instalado
- Docker Compose instalado
- Docker daemon activo
- Docker habilitado al arranque
- Ejecución de contenedores validada
- Acceso Docker configurado para el usuario de laboratorio
- Repositorio Git inicializado
- Ramas `main` y `develop` creadas
- Repositorio remoto GitHub configurado

## Seguridad

Este repositorio no debe contener:

- contraseñas
- archivos `.env`
- respaldos reales
- dumps sensibles
- volúmenes persistentes
- datos productivos

El laboratorio se utiliza exclusivamente con datos de prueba.
