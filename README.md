# 🤖 MantisNexo

**MantisNexo** es un chatbot desarrollado en PHP para integrarse con el sistema de gestión de incidencias [Mantis Bug Tracker (MantisBT)](https://www.mantisbt.org/). Este proyecto busca mejorar la experiencia de usuario, centralizando solicitudes de soporte técnico a través de Telegram.

Este bot permite a los clientes enviar incidencias directamente desde Telegram, las cuales son automáticamente cargadas en MantisBT, evitando la necesidad de acceder al sistema vía web.

---

## 🧠 Objetivos del Proyecto

- Automatizar la recepción de pedidos de soporte técnico.
- Mejorar la accesibilidad para clientes mediante el uso de Telegram.
- Disminuir la carga operativa del equipo técnico.
- Centralizar la información dispersa (WhatsApp, llamadas, emails).

---

## ⚙️ Funcionalidades

- Registro de usuarios mediante `chat_id` y enlace de autoregistro.
- Recepción y procesamiento de mensajes estructurados.
- Carga automática de incidencias en MantisBT vía su API.
- Respuestas automáticas y bidireccionales para guiar al usuario.
- Filtros para recuperar issues existentes y notificar estado.

---

## 🛠️ Tecnologías utilizadas

- PHP (versión recomendada: 7.4+)
- MySQL
- API de Telegram
- API REST de MantisBT
- Webhooks

---
