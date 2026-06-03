# Handl Landing Page

Landing page oficial de **Handl** — plataforma open-source multi-tenant para desplegar recepcionistas con IA en WhatsApp.

Construida con [Astro](https://astro.build) y [Tailwind CSS](https://tailwindcss.com).

## 🚀 Secciones

- **Hero** — Recepcionistas con IA en WhatsApp para tu negocio
- **Features** — Aislamiento multi-tenant, billing preciso, Google Calendar OAuth, cifrado AES-256-GCM, onboarding sin fricción, control asíncrono con BullMQ/Redis
- **Arquitectura** — Pipeline de 6 pasos: Webhook Meta → HMAC Router → BullMQ Queue → OpenAI LLM → Actions → WhatsApp Response
- **Chat Demo** — Simulador interactivo para ver el bot en acción
- **Use Cases** — Clínicas, restaurantes, inmobiliarias
- **Policy Compliance** — Diseñado bajo la normativa oficial de Meta 2026

## 🧞 Comandos

| Comando                   | Acción                                        |
| :------------------------ | :-------------------------------------------- |
| `npm install`             | Instalar dependencias                         |
| `npm run dev`             | Iniciar servidor local en `localhost:4321`    |
| `npm run build`           | Construir sitio producción en `./dist/`       |
| `npm run preview`         | Vista previa del build local                  |
| `npm run astro ...`       | Ejecutar comandos CLI de Astro                |

## 🌐 Despliegue

El sitio se despliega desde la rama `main`.
