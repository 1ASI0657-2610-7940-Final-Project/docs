# Migración de Jira → Notion (GigU)

Estos CSV reproducen lo que vivía en el proyecto Jira `GigU Architecture Design`.
Notion importa cada CSV como una **base de datos**; la primera columna (`Name`) es el título de cada tarjeta.

## Archivos

| Archivo | Reemplaza a | Tarjetas |
| --- | --- | --- |
| `product-backlog.csv` | Product Backlog (§3.4) | **65 ítems**: 52 User Stories (US01–US52) + 13 Technical Stories (SP01–SP13). Columnas `Story ID`, `Epic ID`, `Epic`, `Order`, `Story Points`, `Status` |
| `sprint-1-backlog.csv` | Sprint Backlog 1 (§5.3.1.1) | GIGU-8…61 + T-A1…A6, con su estado al **cierre del Sprint 1** (4 To-do, 5 In-Process, 45 Done) |
| `sprint-2-backlog.csv` | Sprint Backlog 2 (§5.3.2.1) | 9 arrastradas + 10 nuevas, todas **Done** |
| `sprint-3-backlog.csv` | Sprint Backlog 3 (§5.3.3.1) | 11 nuevas (GIGU-74…84). **No cierra al 100%**: 9 Done + 2 In-Process (GIGU-83 velocidad frontend, GIGU-84 contract tests) |

> Los carry-over (GIGU-22…26, 55…59) aparecen en **ambos** sprints 1 y 2 porque su estado cambió entre sprints. Es intencional, para que cada board coincida con la evidencia ya escrita en el informe.
>
> El **product backlog** ya no es solo de User Stories: incluye 13 Technical Stories (SP01–SP13). En Notion, agrupa el board por `Status` o por `Epic` para que coincida con los sprint boards.

## Pasos en Notion (≈5 min)

1. En Notion: **Import** (barra lateral o `Settings → Import`) → **CSV** → selecciona el archivo. Se crea una base de datos nueva.
2. Ajusta los **tipos de propiedad** (Notion los importa como texto):
   - `Status` → tipo **Status** (o **Select**). Crea las opciones `To-do`, `In-Process`, `Done` con colores.
   - `Estimation (h)` y `Story Points` → tipo **Number**.
   - `Assigned To` → tipo **Person** si invitas a tus compañeros, o déjalo **Select**.
   - `Epic` / `Epic ID` / `Origen` → tipo **Select** (agrupa solo).
3. Añade una **vista de tablero (Board)**: `+ Add view → Board`, agrupada por **Status**. Eso recrea el Kanban (columnas Por Hacer / En Curso / Hecho).
   - Para el board del Sprint 1 verás las 3 columnas pobladas; en el Sprint 2 todo cae en *Done*.
4. (Opcional) Para evidencia: cambia el orden de las columnas a `To-do → In-Process → Done` arrastrando los grupos, y toma el screenshot.

## Equivalencias Jira → Notion

| Jira | Notion |
| --- | --- |
| Proyecto / Board | Base de datos + vista Board |
| Columna (To Do / In Progress / Done) | Grupo de la vista Board por `Status` |
| Tarjeta (issue) `GIGU-xx` | Página (fila) — el id va en `Name` y en `Card ID` |
| Epic | Propiedad `Epic` / `Epic ID` (Select) |
| Story Points / Estimación | Propiedad Number |
| Asignado | Propiedad Person/Select |

## Si actualizas el informe con screenshots nuevos

Reemplaza las imágenes de Jira en `imgs/sprint1/` y `imgs/sprint2/` por las capturas equivalentes de Notion, y actualiza las menciones a "Jira" / el URL del board en `README.md` (§4.3.1.7, §4.3.2.7, §5.3.1.1, §5.3.1.8, §5.3.2.1, §5.3.2.8). Avísame y te hago ese reemplazo de texto.
