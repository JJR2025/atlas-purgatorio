# Atlas de la tesis «Cuando el Rey vendió el Purgatorio»

Atlas interactivos que acompañan a la tesis doctoral de José Juan Ruiz Gómez (Universidad Carlos III de Madrid, dir. Carlos Álvarez Nogal). Cada uno es un fichero HTML autónomo: se abre sin conexión y no carga recursos externos.

| Atlas | Dirección estable (QR) | Versión publicada | Huella de los datos |
|---|---|---|---|
| Atlas del AHPM | https://jjruiz.org/atlas-ahpm | `ahpm/v1/` | `e2e7db176442` |
| Atlas del Banco de San Carlos | https://jjruiz.org/atlas-san-carlos | `san-carlos/v1/` | `a0d1a9b89f9a` |
| Atlas de las sesiones con IA | https://jjruiz.org/atlas-sesiones | `sesiones/v1/` | `83339288f875` |

## Cómo se garantiza que cada Atlas es la versión correcta

1. **Se genera, no se edita.** Cada Atlas sale de un cuaderno de la cadena de la tesis (`21__EXPLORADOR`, `ATLAS_SAN_CARLOS`, `ATLAS_SESIONES`) a partir de su fuente canónica.
2. **Se valida antes de publicarse.** El cuaderno `22__VALIDACION_ATLAS` compara cada Atlas con su fuente (recuentos, totales, geografía, categorías, huellas) y comprueba que no exporta datos, que es autónomo y que lleva sello. Solo se publica si todos los controles salen en verde.
3. **Lleva sello.** El pie de cada Atlas indica su versión, su fecha y la *huella* de los datos (12 primeras cifras del SHA-256 de las filas embebidas). Si cambia un solo dato, cambia la huella.
4. **Las versiones no se sobrescriben.** Cada versión vive en su carpeta (`v1/`, `v2/`…). Los QR apuntan a direcciones estables de jjruiz.org que redirigen a la versión aprobada; publicar una versión nueva solo exige cambiar la redirección.

## Sesiones con IA

Las conversaciones completas no se publican: están a disposición del tribunal previa solicitud. `sesiones/v1/MANIFIESTO_HUELLAS.csv` recoge la huella SHA-256 de cada una, que permite comprobar que la conversación entregada es exactamente la registrada. Por prudencia, 13 títulos figuran como «título reservado»; esas conversaciones siguen contando en todas las cifras.

---
*En la elaboración de este documento se ha empleado asistencia de inteligencia artificial (Claude, de Anthropic) para tareas de estructura, procesamiento de datos y formalización. La tesis central, las conclusiones y las aportaciones intelectuales son íntegramente del autor, que ha dirigido, verificado y validado todo el contenido.*
