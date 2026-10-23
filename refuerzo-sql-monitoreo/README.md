# Refuerzo - SQL y monitoreo

Bloque de mediano plazo (1-2 semanas) para cerrar brechas que aparecen en entrevistas:
SQL intermedio, Log Analytics (KQL) y Application Insights. Origen: brechas detectadas en entrevistas
para roles de Azure Application Support.

No es trabajo extra: adelanta el SQL de la practica 1 y la observabilidad de la practica 4.

## Carpetas
| Carpeta | Contenido | Donde se practica |
|---|---|---|
| `sql` | Scripts .sql sobre AdventureWorksLT: consultas (JOIN, GROUP BY, CTE, ROW_NUMBER) y diagnostico (bloqueos, planes, indices) | PC: SQL Server 2022 Developer + SSMS |
| `kql` | Consultas .kql: series de tiempo, top fallas, percentiles, joins | Navegador: workspace demo de Log Analytics |
| `app-insights` | Notas y consultas sobre AppRequests, AppDependencies, AppExceptions; caso "errores 500 intermitentes" | Navegador: workspace demo |

## Pendientes
- [ ] Instalar SQL Server 2022 Developer, SSMS y restaurar AdventureWorksLT
- [ ] Microsoft Learn: Get Started Querying with Transact-SQL
- [ ] Laboratorio de bloqueo con dos sesiones de SSMS
- [ ] Microsoft Learn: Analyze monitoring data with KQL
- [ ] Microsoft Learn: Monitor app performance (Application Insights)
- [ ] Guardar cada consulta que funcione en su carpeta, con un comentario de que resuelve

## Regla
Nombres de archivo en minusculas, con guiones, sin tildes ni enes. Ejemplo: `top-fallas-ultima-hora.kql`.
