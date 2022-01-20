# Google Apps Script - Respuestas automáticas
Proceso la inscripción eventos a través de Google Forms.

Eventos cubiertos:
Clases semanales
Curso
Retiro
Actividades para niños
Iniciaciones
Celebración del Dharma
Festival del Dharma

El script calcula el monto de la inscripción de acuerdo al valor del evento y los descuentos que se aplican 
por tipo de membresía (tres tipos), si se toma el evento completo o por día y si hay un descuento por pago antes de una determinada fecha.
Envía un mail de respuesta a la persona inscripta informando los datos de su inscripción, detalles del evento (lugar, fecha, hora, online o presencial)
detalles sobre protocolo de covid dentro del espacio, link de pago (metodo elegido TodoPago) y Links de youtube a las sesiones si es que el evento
está incluído sin costo dentro de su membresía.
Informa en la planilla de inscripción vinculada al formulario si se envió el mail y si debe abonar.
Toma todos los datos de 3 planillas en las que trabajan las personas de backoffice para cargar datos (se prefiere este método)
Se chequea que la membresía esté paga y activa, de lo contrario se cobra el valor al público general.
Una vez registrado el pago por tesorería se puede correr una función que envía otro mail con la confirmación, información extra a tener en cuenta y links
de youtube a las sesiones. Para algunos eventos se envía link a Zoom.

ID de Biblioteca del script
1emJz1uP4IdL8xzO9FENwqcMT_eV3yVn8VO23f8AwxANJKdNQqY2iejSx

Planilla que carga el EPC con los datos de los eventos: Información de Cursos
