<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Supervisión: qué se lee y qué resulta

[English](README.en.md)

Cómo supervisa global-law todos los países: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Esta página hace lo mismo solo para País Vasco: cada vez que se lee una fuente oficial, cuándo y qué resultó (normas añadidas, modificadas y retiradas). La forma legible por máquina está en [data/checks/](../data/checks/) (JSON Lines, esquema `lexifina-check/1`), en `git log` como commits `Kind: check`, y mes a mes en [checks/](checks/).

**Última comprobación:** 2026-11-25 15:07 UTC, Legislación consolidada del BOE, comunidades autónomas (datos abiertos): 17 direcciones leídas; 0 añadidas, 0 modificadas, 0 retiradas; la comprobación falló; 15 sin publicar, 0 de ellas sin motivo. Avisos: `publish-lag`.

## Fuentes

| Fuente | Carpetas | Frecuencia | Última comprobación correcta | Último resultado | Estado |
| --- | --- | --- | --- | --- | --- |
| [Legislación consolidada del BOE, comunidades autónomas (datos abiertos)](https://www.boe.es/datosabiertos/api/api.php) | `estatuto-de-autonomia/`, `ley-*/`, `decreto-ley-*/`, `decreto-legislativo-*/`, `…` | diaria | 2026-11-23 13:50 UTC | la comprobación falló | vigilada |

## Los últimos 30 días

| Inicio (UTC) | Fuente | Leídas | Añadidas | Modificadas | Retiradas | Sin publicar (sin motivo) | Resultado | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 15:05](checks/2026-11.md#es-boe-autonomico-20261125t150534z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 14:05](checks/2026-11.md#es-boe-autonomico-20261125t140540z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 13:05](checks/2026-11.md#es-boe-autonomico-20261125t130537z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 12:05](checks/2026-11.md#es-boe-autonomico-20261125t120535z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 11:05](checks/2026-11.md#es-boe-autonomico-20261125t110535z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 10:22](checks/2026-11.md#es-boe-autonomico-20261125t102209z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 09:05](checks/2026-11.md#es-boe-autonomico-20261125t090533z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 06:15](checks/2026-11.md#es-boe-autonomico-20261125t061559z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 15:09](checks/2026-11.md#es-boe-autonomico-20261124t150940z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 14:20](checks/2026-11.md#es-boe-autonomico-20261124t142005z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 12:56](checks/2026-11.md#es-boe-autonomico-20261124t125635z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 11:14](checks/2026-11.md#es-boe-autonomico-20261124t111454z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 10:11](checks/2026-11.md#es-boe-autonomico-20261124t101120z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 09:10](checks/2026-11.md#es-boe-autonomico-20261124t091003z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 08:10](checks/2026-11.md#es-boe-autonomico-20261124t081003z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 07:16](checks/2026-11.md#es-boe-autonomico-20261124t071601z) | boe-autonomico | 18 | 0 | 0 | 0 | 15 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-23 13:50](checks/2026-11.md#es-boe-autonomico-20261123t135027z) | boe-autonomico | 17 | 0 | 0 | 0 | 15 (0) | sin cambios `publish-lag` | — |
| [2026-11-23 01:08](checks/2026-11.md#es-boe-autonomico-20261123t010805z) | boe-autonomico | 10 | 0 | 0 | 0 | 15 (0) | sin cambios `publish-lag` | — |

## Compruébelo usted mismo

```
python tools/checktrail.py                      # la última comprobación de cada fuente
python tools/checktrail.py --day 2026-11-23     # todas las comprobaciones de un día
python tools/checktrail.py --act <id>           # cuándo se vio y se publicó una norma
git log --grep='^Kind: check' --format='%ci %s'  # las comprobaciones en el historial
```

Solo tiene fuerza jurídica la publicación oficial (el «Boletín Oficial del Estado» y los diarios oficiales autonómicos); los textos de este repositorio son copias para leer y buscar.
