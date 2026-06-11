# Política de Seguridad

Marval O'Farrell Mairal valora la participación de colaboradores internos, proveedores y auditores autorizados
en la identificación y el reporte responsable de vulnerabilidades de
seguridad. Este documento describe cómo reportar un problema de seguridad en los
repositorios de esta organización y qué esperar durante el proceso.

## Alcance

Esta política aplica a:

- Los repositorios alojados bajo la organización de GitHub de Marval O'Farrell Mairal.
- El código, las configuraciones y las dependencias mantenidas por los equipos internos.

Quedan **fuera de alcance**:

- Servicios o productos de terceros no desarrollados ni mantenidos por Marval.
- Hallazgos de calidad de código que no representen un riesgo de seguridad.
- Reportes generados automáticamente sin evidencia de explotabilidad real.

## Versiones / ramas soportadas

Se brinda soporte de seguridad sobre branch activas en mantenimiento de cada
repositorio. Los reportes deben referirse, siempre que sea posible, a la versión
o branch vigente.

| Estado | Soporte de seguridad |
| ------ | -------------------- |
| Branch principal / producción (`main` / `master`) | ✅ Sí |
| Branch de desarrollo activo (`develop`, `release/*`) | ✅ Sí |
| Branch o versiones discontinuadas | ❌ No |

## Cómo reportar una vulnerabilidad

**No abras un Issue público ni un Pull Request** para reportar una vulnerabilidad
de seguridad, ya que esto podría exponer el problema antes de su remediación.

Para realizar un reporte responsable, utilizá uno de los siguientes canales:

- **Azure DevOps:** crear workItem y compartir a `ciberseguridad@marval.com` mediante la opción `Email work item`
- **GitHub Private Vulnerability Reporting:** a través de la pestaña *Security* del
  repositorio afectado, si la funcionalidad se encuentra habilitada.

Por favor, incluí en tu reporte la mayor cantidad de información posible:

- Descripción de la vulnerabilidad y su posible impacto.
- Repositorio, rama y/o componente afectado.
- Pasos detallados para reproducir el problema (prueba de concepto, si aplica).
- Versión, configuración o entorno donde se detectó.
- Cualquier mitigación o recomendación que consideres pertinente.

## Tiempos de respuesta (SLA)

Los siguientes plazos son orientativos y se miden en días hábiles:

| Etapa | Plazo objetivo |
| ----- | -------------- |
| Acuse de recibo del reporte | 2 días hábiles |
| Evaluación inicial y clasificación de severidad | 5 días hábiles |
| Definición del plan de remediación | Según severidad (ver abajo) |

Los plazos se alinean con el proceso corporativo de gestión de
vulnerabilidades:

| Severidad | SLA objetivo |
| --------- | ----------------------- |
| Crítica | `14 días` |
| Alta | `30 días` |
| Media | `90 días` |
| Baja | `Próximo ciclo de mantenimiento` |

## Qué podés esperar

- Confirmaremos la recepción de tu reporte dentro del plazo indicado.
- Evaluaremos y clasificaremos la vulnerabilidad según su severidad e impacto.
- Te mantendremos informado sobre el avance de la remediación.
- Te notificaremos una vez resuelto el problema.

## Divulgación responsable

Solicitamos no divulgar públicamente la vulnerabilidad hasta que haya sido
remediada y se haya coordinado una comunicación con el equipo de SecOps.
Agradecemos el reporte responsable y el tiempo dedicado a mejorar la seguridad de
nuestros sistemas.

## Normativa

Los procesos internos de gestión de vulnerabilidades se encuentran definidos
en la normativa corporativa vigente del Sistema de Gestión de Seguridad de la Información (SGSI):

- *NETC04_Norma de Gestión de Vulnerabilidades*
- *PTECXX_Procedimiento de Gestión de Vulnerabilidades*


---

*Documento mantenido por el equipo de SecOps de Marval O'Farrell Mairal.*
*Última actualización: 06/2026.*
