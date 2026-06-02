# Política de Privacidad — Control de Rutinas y Recordatorios Personales
Última actualización: 16 de mayo de 2026

### 1. Responsable
Esta aplicación es desarrollada, administrada y mantenida por su autor de forma individual. Es un proyecto de carácter personal; no existe ninguna empresa, corporación, institución de salud ni organización de ningún tipo detrás de ella.

### 2. Qué datos almacena la aplicación
La aplicación almacena la información única y exclusivamente de forma local en el almacenamiento interno del dispositivo del usuario. Los datos que el usuario puede registrar opcionalmente son:

* **Datos de perfil personal:** Nombre, apellidos, fecha de nacimiento, peso, estatura, anotaciones de control y metas personales.
* **Gestión de artículos y recordatorios:** Nombres de los productos de uso diario, cantidades, dosis o porciones asignadas, horarios de consumo, alarmas de aviso y control de existencias en el inventario doméstico.
* **Registro de parámetros de bienestar:** Anotaciones manuales de métricas cotidianas como presión habitual, pulsaciones, estimaciones físicas, niveles generales de bienestar y temperatura corporal.
* **Agenda de eventos y contactos:** Títulos de citas, fechas, recordatorios de reuniones con profesionales o asesores, y datos de contacto de dichos especialistas.
* **Historial de cronogramas y aplicaciones:** Registro de planes programados, fechas de cumplimiento, dosis aplicadas y recordatorios de próximos eventos de la agenda personal.
* **Documentación de soporte:** Título, descripción y archivos adjuntos (imágenes o documentos PDF almacenados localmente) que el usuario decida vincular a sus notas de seguimiento.
* **Actividad física y rendimiento:** Tipo de actividad, conteo de pasos, distancia recorrida, estimación de calorías, duración del ejercicio y ruta mediante posicionamiento satelital (GPS).
* **Control de solicitudes e inventario:** Historial de artículos planificados y lista de compras pendientes de confirmar en el carrito local.

### 3. Dónde se almacenan los datos
Todos los datos se guardan estrictamente de forma local en el dispositivo del usuario, utilizando una base de datos interna cifrada. La aplicación **no envía, no recopila, ni transmite ningún tipo de dato** a servidores externos, bases de datos en la nube ni a terceras personas.

Las copias de seguridad que el usuario decida generar de manera manual se guardan exclusivamente en el destino que el propio usuario elija de forma independiente (tales como el almacenamiento físico del dispositivo, su cuenta de almacenamiento personal en Google Drive, etc.). El resguardo, la seguridad y el contenido de esas copias archivadas son responsabilidad exclusiva del usuario.

### 4. Uso de la ubicación (GPS)
La aplicación solicita acceso a los servicios de ubicación del dispositivo únicamente durante las funciones de seguimiento de actividad física o recreativa (como caminatas, carreras o ciclismo) y solo mientras la sesión de registro esté activa por orden del usuario. Estos datos de trayecto se procesan y almacenan localmente y jamás son transmitidos fuera del terminal.

### 5. Integración con plataformas de actividad (Health Connect)
La aplicación puede leer información relacionada con la actividad física desde el servicio Google Health Connect (conteo de pasos, distancias y sesiones de ejercicio físico), siempre y cuando el usuario conceda explícitamente el permiso correspondiente. Estos datos se utilizan con la única finalidad de unificar y mostrar el historial de actividad en las pantallas de la aplicación y nunca se comparten con terceros.

### 6. Notificaciones y alarmas del sistema
La aplicación utiliza los servicios de notificación locales del propio sistema operativo del dispositivo para activar los recordatorios de horarios, agenda de citas, avisos programados y alertas de bajo stock en el inventario local. No se hace uso de servicios de mensajería o notificaciones push en la nube (como Firebase Cloud Messaging u otros) para el envío de alertas.

### 7. Gestión de suscripciones y pagos
El procesamiento y gestión de las suscripciones dentro de la aplicación se realiza por medio del sistema oficial de facturación de la tienda (Google Play Billing). El desarrollador de la aplicación no recibe, no procesa y no almacena datos de tarjetas de crédito, cuentas bancarias ni información de transacciones financieras. Las políticas y condiciones de facturación de Google aplican para todas las operaciones de pago.

### 8. Permisos solicitados al dispositivo

| Permiso | Motivo de uso exclusivo |
| :--- | :--- |
| `POST_NOTIFICATIONS` | Mostrar las alertas locales de recordatorios de horarios y citas programadas en la agenda. |
| `SCHEDULE_EXACT_ALARM` | Configurar el temporizador del sistema para emitir avisos con precisión horaria absoluta. |
| `USE_FULL_SCREEN_INTENT` | Permitir el despliegue de alertas críticas a pantalla completa incluso con el dispositivo bloqueado. |
| `ACCESS_FINE_LOCATION` | Registrar la ruta mediante coordenadas satelitales durante el seguimiento activo de ejercicio. |
| `FOREGROUND_SERVICE` | Mantener el servicio de seguimiento de actividad en funcionamiento continuo en segundo plano mientras se ejercita. |
| `READ_MEDIA_IMAGES` | Permitir al usuario seleccionar y adjuntar imágenes o fotografías de soporte a sus notas y reportes locales. |
| `RECEIVE_BOOT_COMPLETED` | Reprogramar de manera automática los recordatorios y alarmas locales tras reiniciar el teléfono. |
| `health.READ_STEPS` / `READ_EXERCISE` | Leer las métricas de rendimiento y caminata provenientes del panel de Health Connect. |

### 9. Protección de menores de edad
Esta aplicación ha sido diseñada y estructurada como una herramienta de gestión organizativa general. No está dirigida de forma específica a menores de 13 años y no recopila ni solicita información de menores de edad de forma consciente ni automatizada.

### 10. Derechos del usuario sobre el control de su información
El usuario cuenta con el dominio absoluto y total de cada uno de los datos ingresados en el sistema:
* Puede extraer y exportar de forma íntegra toda su información mediante la herramienta nativa de copia de seguridad local.
* Puede eliminar permanentemente toda la información registrada con tan solo desinstalar la aplicación o bien limpiando la memoria caché y datos de la app desde los ajustes generales del sistema operativo de su dispositivo.
* Dado que no existen registros de cuentas de usuario, perfiles de inicio de sesión ni servidores centralizados controlados por el desarrollador, no existe almacenamiento externo al que se pueda solicitar acceso, rectificación o eliminación.

### 11. Cláusula de exención de responsabilidad profesional
Esta aplicación es únicamente un organizador, agenda y bitácora de uso personal y de productividad. **No es una aplicación médica, no está diseñada para el diagnóstico de dolencias, no prescribe tratamientos de salud ni ofrece asesoramiento clínico o profesional de ningún tipo.** La información contenida o registrada en ella es meramente informativa para el control cotidiano del usuario y no sustituye en ningún caso las indicaciones de profesionales certificados. El desarrollador de la aplicación no tiene afiliación alguna con entidades de salud, laboratorios, farmacias u organismos gubernamentales.

### 12. Modificaciones en el documento de privacidad
Cualquier cambio o actualización relevante en las directrices de esta política se verá reflejado directamente a través del lanzamiento de una nueva versión actualizada de la aplicación en la plataforma Google Play.

### 13. Canales de contacto
Para resolver cualquier duda o aclaración sobre la gestión local de la privacidad en el dispositivo, el usuario tiene la facultad de comunicarse con el desarrollador por medio de los canales de soporte habilitados en la ficha oficial de la aplicación dentro de Google Play.
