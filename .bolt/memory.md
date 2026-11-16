# Project memory

## Product intent & audience

- "daisyx" / "Daisy Ly": bot de Discord con panel/dashboard web de administración.
- Dashboard muestra módulos de gestión y seguridad para servidores de Discord.
- Datos de demo: saludo "Welcome back, Luna", 11/13 módulos activos.
- Módulos detectados: Tickets, Auto-Roles, AutoMod, Anti-Raid, Anti-Nuke, Verification, Logs, Levels, Backups, Honeypot (pendiente), Custom Commands (pendiente), y otros sin nombrar.
- Bloque "Safety overview" y sección de cambios de configuración recientes (3 entradas).
- El usuario está explorando sub-configuraciones dentro de módulos; primero Tickets (Reclamaciones, Valoraciones).

## Brand personality & voice

- No inferido aún.

## Visual design & UX direction

- Layout tipo dashboard con tarjetas de módulos, estado activo/inactivo por módulo.
- Estados: "activo" y "listo para configurar" (pendiente).
- Sección de resumen de seguridad ("Safety overview").
- Lista de cambios recientes de configuración.
- Sub-pantallas de configuración por módulo con secciones internas.
- Tickets → "Reclamaciones": campos de texto (botón), selector de color (azul/verde/rojo/gris), emoji, roles con acceso, plantillas de renombrado ({user}, {ticket}), interruptores (reclamación obligatoria, desactivar botón, reclamación automática).
- Tickets → "Valoraciones": activa calificación al cerrar ticket (opciones internas aún no exploradas).
- No se han inferido colores globales, tipografía ni tokens de diseño.

## Decisions, constraints & rationale

- No hay código fuente editable; solo build compilado.
- Cualquier cambio requiere recrear la página desde la demo.
- El entorno no tiene navegador ni capacidad de renderizar pantallas.
- El usuario revisa config interna módulo por módulo; se documenta lo encontrado para recrearlo.

## Open questions & assumptions

- ¿El usuario tiene el proyecto original con código fuente, o se recrea desde la demo?
- ¿Qué cambios quiere el usuario: textos, módulos, colores, comportamiento?
- ¿Cuáles son los 2 módulos restantes no identificados?
- ¿Diseño/branding específico o se mantiene el estilo actual de la demo?
- Opciones internas de Valoraciones aún no exploradas.
- ¿Se documentarán sub-configs de otros módulos además de Tickets?