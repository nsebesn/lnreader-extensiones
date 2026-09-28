# Extensiones corregidas para LNReader

Versiones corregidas de extensiones de LNReader para webs que cambiaron y cuya
extensión oficial aún no se ha actualizado. Las publica y mantiene Brandon
(nsebesn) para su lector, y funcionan con cualquier app compatible con el
formato de LNReader.

Cada archivo es **la extensión oficial de LNReader sin tocar**, más una
corrección al final, separada y comentada, para que se vea exactamente qué
cambió. Las extensiones oficiales son de github.com/LNReader/lnreader-plugins,
con licencia MIT (ver `LICENSE-LNReader.txt`).

Catálogo para añadir en la app:

    https://raw.githubusercontent.com/nsebesn/lnreader-extensiones/main/plugins.json

| Extensión | Versión | Qué corrige |
|---|---|---|
| SkyNovels | 1.1.1 | Filtros de orden, estado y origen que la API admite |
| MVLempyr | 1.0.15 | La lista va de 20 en 20 y la búsqueda por tandas pequeñas, en vez de bajar el catálogo entero (~22 MB) cada vez |

## Cómo se prueba

Las extensiones se escriben y se prueban en el proyecto del lector antes de
publicarse: cada una tiene que dar la misma lista, ficha y capítulo que las
respuestas grabadas de su web, sin ayuda del motor.
