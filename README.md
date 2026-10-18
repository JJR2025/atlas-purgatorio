# Atlas de la tesis «Cuando el Rey vendió el Purgatorio»

Atlas interactivos que acompañan a la tesis doctoral de José Juan Ruiz Gómez (Universidad Carlos III de Madrid, dir. Carlos Álvarez Nogal). Cada uno es un fichero HTML autónomo: se abre sin conexión y no carga recursos externos.

| Atlas | Dirección estable (QR) | Versión publicada | Huella de los datos |
|---|---|---|---|
| Atlas de la Tesorería General | https://jjruiz.org/atlas-tesoreria | `tesoreria/v1/` | `32113e78cdfb` |
| Atlas del AHPM | https://jjruiz.org/atlas-ahpm | `ahpm/v1/` | `e2e7db176442` |
| Atlas del Banco de San Carlos | https://jjruiz.org/atlas-san-carlos | `san-carlos/v1/` | `a0d1a9b89f9a` |
| Atlas de las sesiones con IA | https://jjruiz.org/atlas-sesiones | `sesiones/v1/` | `83339288f875` |

## Anexo técnico

| Documento | Dirección estable (QR) | Versión publicada | Contenido |
|---|---|---|---|
| Anexo técnico I · Las doce hipótesis | https://jjruiz.org/hipotesis | `anexo/hipotesis/v1/` | Fichas H1-H12 (capítulo 8) |
| Anexo técnico II · El modelo del capítulo 9 | https://jjruiz.org/modelo | `anexo/modelo/v1/` | Club religioso, SPI y juego de Stackelberg (capítulo 9) |

Cada página es un HTML autónomo, con las ecuaciones en MathML, y lleva junto a ella su versión en PDF. Las cifras corresponden a la ejecución de referencia de 13 de octubre de 2026 de las cadenas `HIPOTESIS` y `MODELOS`. Como los Atlas, las versiones no se sobrescriben: una revisión se publica en `v2/` y solo cambia la redirección.

## Cómo se garantiza que cada Atlas es la versión correcta

1. **Se genera, no se edita.** Cada Atlas sale de un cuaderno de la cadena de la tesis (`02_ATLAS_TESORERIA`, `21__EXPLORADOR`, `ATLAS_SAN_CARLOS`, `ATLAS_SESIONES`) a partir de su fuente canónica.
2. **Se valida antes de publicarse.** El cuaderno `22__VALIDACION_ATLAS` compara cada Atlas con su fuente (recuentos, totales, geografía, categorías, huellas) y comprueba que no exporta datos, que es autónomo y que lleva sello. Solo se publica si todos los controles salen en verde. El Atlas de la Tesorería General pasó en su publicación nueve controles equivalentes (29 de 29 series idénticas a `AGS_SERIES.json`, años 1780–1805, autonomía, ausencia de exportación, sello y declaración); se incorporará al cuaderno `22__VALIDACION_ATLAS` en la próxima ejecución de la cadena.
3. **Lleva sello.** El pie de cada Atlas indica su versión, su fecha y la *huella* de los datos (12 primeras cifras del SHA-256 de las filas embebidas). Si cambia un solo dato, cambia la huella.
4. **Las versiones no se sobrescriben.** Cada versión vive en su carpeta (`v1/`, `v2/`…). Los QR apuntan a direcciones estables de jjruiz.org que redirigen a la versión aprobada; publicar una versión nueva solo exige cambiar la redirección.

## Tesorería General

El Atlas se genera con la cadena `TESORERIA` de la tesis: `01_AGS_CARGO_DATA` construye las series a partir de la base de las Cuentas de Cargo y Data y del clasificador de epígrafes, y `02_ATLAS_TESORERIA` las vuelca en la página. Las series de remesas y de vales que figuraban en la bitácora de trabajo se retiraron por carecer de tabla de origen; el esfuerzo fiscal-militar comparado con Inglaterra se detiene en 1793, último año de las cifras de Torres Sánchez. El pie del Atlas da, además de la huella de los datos, la de los ficheros de entrada (`08b6dc7f9f05`).

## Sesiones con IA

Las conversaciones completas no se publican: están a disposición del tribunal previa solicitud. `sesiones/v1/MANIFIESTO_HUELLAS.csv` recoge la huella SHA-256 de cada una, que permite comprobar que la conversación entregada es exactamente la registrada. Por prudencia, 13 títulos figuran como «título reservado»; esas conversaciones siguen contando en todas las cifras.

---
*En la elaboración de este documento se ha empleado asistencia de inteligencia artificial (Claude, de Anthropic) para tareas de estructura, procesamiento de datos y formalización. La tesis central, las conclusiones y las aportaciones intelectuales son íntegramente del autor, que ha dirigido, verificado y validado todo el contenido.*
