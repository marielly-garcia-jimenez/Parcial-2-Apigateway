# 🛡️ API Gateway - La Puerta de Entrada Centralizada

El **API Gateway** es el único punto de contacto exterior para los clientes del sistema. Todas las peticiones HTTP pasan por aquí antes de ser dirigidas a su servicio correspondiente.

---

## 🚦 Funciones Clave
- **Enrutamiento Inteligente:** Dirige el tráfico a `/productos`, `/ordenes` y `/pagos`.
- **Filtros de Red:** Capaz de añadir lógica de seguridad o transformación de peticiones.
- **Tolerancia a Fallos:** Integrado con Eureka para obtener las instancias de servicio.

---

## 🧭 Puertos y Rutas Principales
El Gateway corre en el puerto **`8080`**.

- **Productos:** `http://localhost:8080/productos/**`
- **Órdenes:** `http://localhost:8080/ordenes/**`
- **Pagos:** `http://localhost:8080/pagos/**`

---

## 📜 Logs y Trazabilidad
Este servicio envía logs detallados de cada petición a CloudWatch (LocalStack), lo que permite auditar el tráfico entrante de forma centralizada.

---

## 🔗 Ecosistema Completo
Consulta el repositorio de [Infraestructura y Guías](https://github.com/marielly-garcia-jimenez/Infraestructura-Examen) para más detalles del sistema global.

---
<p align="center"> Parte del Sistema de Microservicios - 2026 </p>
