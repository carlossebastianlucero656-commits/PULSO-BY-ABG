# Pulso — by ABG

**Prevención real. Cumplimiento garantizado.**

Panel de seguimiento de obra en tiempo real, desarrollado para el proyecto de Reparación y Ampliación de Galpón + Cierre Perimetral (Conosur Drilling S.A.).

## Qué es esto

Un panel de gestión integral de obra: cronograma con camino crítico real (CPM), costos, horas hombre, materiales, evidencia fotográfica, firma digital, informes automáticos, y un repositorio de documentación por carpetas — todo en un único archivo HTML autocontenido, sin necesidad de instalar nada.

## Estado actual

Esta es la **versión esqueleto**: un archivo HTML único con persistencia compartida vía `window.storage`. El control de acceso es por rol + PIN (organizativo, no seguridad criptográfica real).

**Próxima etapa:** migración a una arquitectura con base de datos real (Supabase) y autenticación individual por usuario. Ver la sección "Roadmap" más abajo.

## Cómo usarlo

Abrir `index.html` en cualquier navegador. No requiere build, ni instalación, ni conexión a un servidor propio.

## Documentación

- `Manual_Pulso_ABG.docx` — manual de uso completo, organizado por rol (Director Técnico, Administración, Gerencia).

## Roadmap

- [x] Cronograma con CPM real y dependencias entre frentes
- [x] Línea base fija + fecha real de inicio por tarea
- [x] SPI / CPI (Earned Value)
- [x] Riesgo ponderado
- [x] Vista móvil (tarjetas + ficha con pestañas)
- [x] Repositorio de documentos por carpetas
- [ ] Migración a Supabase (base de datos real, autenticación por usuario)
- [ ] Soporte multi-obra
- [ ] Respaldo automático

## Licencia / Autoría

Desarrollado para ABG — Lic. Carlos Sebastián Lucero, Mat. 11012A.
