
# Córdoba Envíos

Sistema de gestión y seguimiento de encomiendas.

## Descripción

Proyecto de documentación técnica para organizar la recepción, registro, distribución y entrega de encomiendas de Córdoba Envíos, una empresa ficticia de encomiendas y mensajería.

Trabajo Práctico Integrador de Organización Empresarial (Tecnicatura Universitaria en Programación a Distancia, UTN).

## Integrante

Francisco Barandiarán (trabajo individual).

## Enlaces

- **Repositorio:** https://github.com/setox0p/cordoba-envios
- **Tablero de gestión (GitHub Projects):** https://github.com/users/setox0p/projects/1/views/1

## Estructura del repositorio

| Ruta | Contenido |
|---|---|
| `docs/entregas/` | Entregas 1, 2 y 3 en PDF |
| `docs/bpmn/` | Diagrama BPMN del proceso de envío |
| `docs/datos/diccionario-de-datos.md` | Entidades ENCOMIENDA, CLIENTE y REGISTRO_OPERACION |
| `docs/backlog/historias-de-usuario.md` | Historias de usuario con criterios de aceptación |
| `docs/control/indicadores.md` | Indicadores y estándares de desempeño |
| `docs/declaracion-ia.md` | Declaración de uso de IA |

## Historias de usuario

| ID | Historia | Issue |
|---|---|---|
| HU-01 | Como operador de recepción, quiero registrar una encomienda con los datos del cliente, para que quede identificada con un código único y estado «recibido». | [#9](https://github.com/setox0p/cordoba-envios/issues/9) |
| HU-02 | Como chofer de distribución, quiero actualizar el estado de una encomienda a «en distribución» o «entregado», para mantener la información al día y habilitar la facturación. | [#10](https://github.com/setox0p/cordoba-envios/issues/10) |
| HU-03 | Como agente de atención al cliente, quiero consultar el estado de una encomienda por su código, para responder al cliente sin consultar a otras áreas. | [#11](https://github.com/setox0p/cordoba-envios/issues/11) |

Los criterios de aceptación están en `docs/backlog/historias-de-usuario.md` y en cada Issue.

## Indicadores de control

| N.º | Indicador | Estándar | Frecuencia |
|---|---|---|---|
| 1 | Integridad de datos | 1.000 envíos con 0 pérdidas | Por iteración |
| 2 | Tiempo de respuesta de consultas | Máximo 3 segundos | En cada fase de pruebas |
| 3 | Cumplimiento del cronograma | Primera versión en 8 semanas | Semanal |
| 4 | Casos de prueba aprobados | Al menos 95 % | Antes de la implementación |
| 5 | Entregas exitosas al primer intento | Al menos 90 % (propuesto) | Mensual |
| 6 | Coherencia de estados | 100 % | Semanal |
| 7 | Avance del backlog | Según cronograma | Semanal |

El detalle de cada indicador, su medición y las acciones correctivas está en `docs/control/indicadores.md`.

## Declaración de Uso de IA

Se utilizaron asistentes de Inteligencia Artificial generativa como apoyo para organizar el TPI, resolver dudas y revisar el trabajo. La IA no reemplazó el análisis: el contenido corresponde al caso Córdoba Envíos y a los conceptos de la asignatura, y las decisiones finales fueron mías.

| Uso | Prompt (resumido) | Corrección o decisión humana |
|---|---|---|
| Organización del trabajo | ¿Cómo ordeno la documentación y presento las distintas partes de la Entrega 4 junto con las Entregas 1, 2 y 3? | Puse los enlaces en la primera página, incluí las entregas anteriores como anexos sin modificar y definí yo la estructura de carpetas del repositorio. |
| Modelado BPMN | ¿Cómo represento las actividades, los responsables y las decisiones del proceso de envío con pools y lanes? | Definí los lanes según mi organigrama (Entrega 3), agregué el lane del sistema, limité las compuertas a dos excepciones y alineé los estados con mi diccionario de datos. |
| Historias de usuario | Revisá la redacción y los criterios de aceptación de estas historias de usuario. | Ajusté los criterios para usar los campos del diccionario de datos y la meta de 3 segundos de la Entrega 2. |
| Revisión final | Revisá esta consigna y decime si mi TP está bien para entregar. | Contrasté las observaciones con las capturas del repositorio y corregí las inconsistencias detectadas. |

### Control de errores y revisión

Las sugerencias de la IA se aceptaron solo cuando coincidían con los conceptos de la materia y con lo efectivamente realizado en el proyecto. Las demás se descartaron o modificaron según mi propio criterio.
