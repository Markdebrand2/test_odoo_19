# Odoo 19 Dockerizado para Producción

Entorno modular y seguro para desplegar Odoo 19 con monitoreo , persistencia, y configuración multi-worker.

## 📦 Servicios
- Odoo 19
- PostgreSQL 15
- NGINX externo

## 📁 Estructura
Ver `docker-compose.yml`, `Dockerfile`, `config/`, `addons2/`.

## 🛡 Seguridad
- Redis y PostgreSQL en red interna
- `.env` para credenciales
- `.gitignore` excluye secretos y logs

## 🔍 Pendientes
- Redis
- Prometheus + cAdvisor
- Grafana


