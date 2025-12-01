
****REQUERIMIENTOS FUNCIONALES (RF)****

**RF-01: Registro de solicitudes**

El sistema debe permitir que cualquier usuario (estudiante, docente o administrativo) cree una solicitud describiendo su problema y asignándole una prioridad.

**RF-02. Consulta del estado de solicitudes**

El sistema debe permitir que cada usuario vea únicamente sus propias solicitudes con información como estado, fecha, prioridad y técnico asignado.

**RF-03. Asignación y gestión de solicitudes**

El sistema debe permitir que un técnico tome una solicitud, cambie su estado (Pendiente -> En proceso -> Cerrada) y deje registro de cada cambio (una especie de auditoria).

**RF-04. Notificaciones de cambios**

El sistema debe enviar una notificación (correo o interna) al usuario cada vez que su solicitud cambie de estado o sea asignada a un técnico.

**RF-05. Generación de reportes**

El sistema debe permitir generar reportes simples (cantidad de solicitudes por fecha, estado, prioridad) con la opción de exportar la información.

****REQUERIMIENTOS NO FUNCIONALES (RNF)****


**RNF-01. Rendimiento**

El sistema debe mostrar las vistas principales (dashboard, consulta de solicitudes) en un tiempo máximo de 2 segundos bajo condiciones normales de carga.

**RNF-02. Seguridad de acceso**

El sistema debe incluir autenticación obligatoria y roles de usuario (usuario común / técnico) para restringir funciones.

**RNF-03. Usabilidad**

La interfaz debe ser clara, intuitiva y accesible desde computador y celular sin perder legibilidad.

**RNF-04. Disponibilidad**

El sistema debe estar disponible al menos el 90% del tiempo, evitando caídas prolongadas que afecten la atención del servicio.

**RNF-05. Integridad de datos**

Toda la información registrada (solicitudes, estados, notificaciones) debe almacenarse de manera consistente, evitando pérdida o duplicidad.
