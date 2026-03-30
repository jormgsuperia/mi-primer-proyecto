# CLAUDE.md — Reportes Superia Capital

## Descripcion

Proyecto de reportes financieros de **Superia Capital**. Centraliza la generacion, almacenamiento y documentacion de reportes financieros periodicos.

---

## Estructura del proyecto

```
mi-primer-proyecto/
├── data/       # Datos fuente (archivos de entrada, bases de datos, exportaciones)
├── docs/       # Documentacion interna, notas y referencias del proyecto
├── reports/    # Reportes financieros generados, listos para revision o distribucion
└── README.md   # Descripcion general del proyecto
```

### data/
Contiene los datos fuente que alimentan los reportes: exportaciones de sistemas contables, hojas de calculo, archivos CSV o JSON con cifras financieras. Estos archivos son la fuente de verdad del proyecto.

### docs/
Notas de trabajo, instrucciones metodologicas, criterios de analisis y cualquier documentacion de soporte que explique decisiones o contexto del proyecto.

### reports/
Reportes financieros terminados o en elaboracion. Cada reporte debe incluir fecha en el nombre del archivo y un resumen ejecutivo al inicio.

---

## Convenciones

- **Idioma del contenido:** todo el contenido se escribe en espanol.
- **Nombres de archivos:** en ingles, en minusculas, con guiones en lugar de espacios (ej. `monthly-report-2026-03.md`).
- **Formato de fechas:** siempre `YYYY-MM-DD` (ej. `2026-03-30`).

---

## Reglas

- **No modificar archivos en `data/` sin permiso explicito del usuario.** Estos archivos son datos fuente; cualquier cambio debe ser autorizado antes de ejecutarse.
- **Crear una rama (branch) para cambios grandes** — nuevas secciones de reporte, reestructuracion de carpetas, o cualquier cambio que afecte multiples archivos.
- Los reportes deben versionarse con fecha en el nombre del archivo, no sobreescribir versiones anteriores.

---

## Preferencias de colaboracion

- Responder siempre en **espanol**.
- Usar **tablas** para presentar datos comparativos (periodos, categorias, variaciones).
- Incluir un **resumen ejecutivo** al inicio de cada reporte con los puntos clave.
- Mantener el tono formal y orientado a negocio, apropiado para audiencia financiera.

---

## Contexto actual

- Proyecto recien inicializado (2026-03-30).
- Estructura base creada: carpetas `data/`, `docs/`, `reports/` con archivos iniciales.
- 2 commits en GitHub en la rama `master`.
