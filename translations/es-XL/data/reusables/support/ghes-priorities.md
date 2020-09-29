|                             Prioridad                              | Descripción                                                                                                                                                                                                                                   | Ejemplos                  |
|:------------------------------------------------------------------:| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| {{ site.data.variables.product.support_ticket_priority_urgent }} | {{ site.data.variables.product.prodname_ghe_server }} está fallando en un ambiente productivo, y dicha falla impacta en la operación de tu negocio.<br/><br/>_{{ site.data.reusables.support.priority-urgent-english-only }}_ | <ul><li>Errores o suspensiones que afectan la funcionalidad central de Git o de la aplicación web para todos los usuarios</li><li>Degradación grave de rendimiento para la mayoría de los usuarios</li><li>Almacenamiento agotado, o que se llena muy rápidamente</li><li>Incapacidad para instalar un archivo de licencia renovado</li><li>Incidente de seguridad</li><li>Pérdida de acceso administrativo para la instancia sin solución alternativa conocida</li><li>Falla para restaurar un respaldo en un ambiente productivo</li></ul> |
|  {{ site.data.variables.product.support_ticket_priority_high }}  | {{ site.data.variables.product.prodname_ghe_server }} está fallando en un ambiente productivo, pero el impacto a tu negocio es limitado.                                                                                                    | <ul><li>Degradación del rendimiento que reduce la productividad para muchos usuarios</li><li>Redundancia reducida por fallo en la Alta Disponibilidad (HA) o nodos de agrupación</li><li>Fallo en respaldar la instancia</li><li>Fallo para restaurar un respaldo en un ambiente de prueba o de montaje que podría poner en riesgo la restauración exitosa a un ambiente productivo</li></ul> |
| {{ site.data.variables.product.support_ticket_priority_normal }} | Estás experimentando problemas limitados o moderados con {{ site.data.variables.product.prodname_ghe_server }}, o tienes preocupaciones o dudas generales sobre la operación de tu instancia.                                               | <ul><li>Problemas en un ambiente de pruebas o de montaje</li><li>Consejo sobre utilizar las características y APIS de {{ site.data.variables.product.prodname_dotcom }}, o dudas sobre configurar las integraciones de terceros desde tu instancia</li><li>Problemas con las herramientas para la migración de datos de usuario que proporciona {{ site.data.variables.product.company_short }}</li><li>Mejoras</li><li>Reporte de errores</li><li>Características que no funcionan como se espera</li><li>Preguntas generales sobre seguridad</li></ul> |
|  {{ site.data.variables.product.support_ticket_priority_low }}   | Tienes una pregunta o sugerencia acerca de {{ site.data.variables.product.prodname_ghe_server }} que no es urgente o que no bloquea la productividad de tu equipo de otra forma.                                                            | <ul><li>Solicitudes de características</li><li>Retroalimentación de producto</li><li>Solicitudes de verificación de estado (por el momento, únicamente disponible para clientes con un {{ site.data.variables.product.premium_support_plan }})</li><li>Notificar a {{ site.data.variables.product.company_short }} sobre mantenimiento planeado para tu instancia</li></ul> |