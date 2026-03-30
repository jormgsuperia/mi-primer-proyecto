# Guía para Nuevos Miembros — Reportes Superia Capital

**Última actualización:** 2026-03-30

---

## ¿De qué trata este proyecto?

Este repositorio centraliza la generación, almacenamiento y documentación de los **reportes financieros periódicos de Superia Capital**. Aquí se producen y versionan los reportes trimestrales y mensuales que el equipo utiliza para el seguimiento del portafolio, la comunicación interna y el análisis de desempeño.

El proyecto no contiene código de automatización por el momento; su función principal es ser la fuente de verdad para los reportes y los datos que los respaldan.

---

## Estructura del repositorio

```
mi-primer-proyecto/
├── data/       # Datos fuente: exportaciones, CSVs, hojas de cálculo
├── docs/       # Documentación interna, notas y guías de trabajo
├── reports/    # Reportes financieros terminados o en elaboración
├── CLAUDE.md   # Instrucciones de colaboración para el asistente IA
└── README.md   # Descripción general del proyecto
```

### `data/`
Archivos de entrada que alimentan los reportes: exportaciones de sistemas contables, bases de datos, archivos CSV o JSON con cifras financieras. Son la fuente de verdad del proyecto. **No modificar sin autorización explícita.**

### `docs/`
Documentación de soporte: notas del equipo, criterios metodológicos, instrucciones de proceso y guías como esta. Todo lo que ayude a entender el contexto o las decisiones detrás del trabajo.

### `reports/`
Reportes financieros listos o en elaboración. Cada archivo sigue la convención de nombre `quarterly-report-YYYY-qN.md` (trimestral) o `monthly-report-YYYY-MM.md` (mensual). Ver el índice completo en [reports/README.md](../reports/README.md).

---

## Convenciones que debes conocer

| Aspecto | Convención |
|---|---|
| Idioma del contenido | Español |
| Nombres de archivos | Inglés, minúsculas, guiones (`monthly-report-2026-03.md`) |
| Formato de fechas | `YYYY-MM-DD` (ej. `2026-03-30`) |
| Formato de cifras | Millones de pesos MXN abreviados como `$000 M MXN` |
| Inicio de cada reporte | Resumen ejecutivo con los puntos clave |
| Datos comparativos | Siempre en tabla con columna de variación |

---

## Cómo empezar a contribuir

### 1. Clona el repositorio

```bash
git clone https://github.com/jormgsuperia/mi-primer-proyecto.git
cd mi-primer-proyecto
```

### 2. Familiarízate con los reportes existentes

Revisa el índice en [`reports/README.md`](../reports/README.md) y lee al menos un reporte trimestral para entender el formato y el tono esperado.

### 3. Para crear un nuevo reporte

- Usa un reporte existente como plantilla (por ejemplo, `quarterly-report-2025-q4.md`).
- Nombra el archivo siguiendo la convención: `quarterly-report-YYYY-qN.md` o `monthly-report-YYYY-MM.md`.
- Incluye siempre: encabezado con fecha y periodo, resumen ejecutivo, métricas en tabla, y perspectiva para el siguiente periodo.
- Nunca sobreescribas un reporte anterior; cada periodo tiene su propio archivo.

### 4. Para cambios grandes

Si tu contribución afecta múltiples archivos o introduce una nueva sección o estructura, **crea una rama** antes de empezar:

```bash
git checkout -b nombre-descriptivo-del-cambio
```

Abre un Pull Request para revisión antes de fusionar a `master`.

### 5. Para actualizar datos fuente

Los archivos en `data/` solo se modifican con **autorización explícita** del coordinador del proyecto. Si necesitas actualizar o agregar datos, consulta primero con Diego Villarreal.

---

## Equipo

| Nombre | Rol |
|---|---|
| Diego Villarreal | Coordinador |
| Jose Ramon Madero | Participante |

---

## ¿Dudas?

Revisa [`CLAUDE.md`](../CLAUDE.md) para las instrucciones completas de colaboración, o consulta directamente con el coordinador del proyecto.
