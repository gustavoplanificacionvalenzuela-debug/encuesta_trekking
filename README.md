# Interfaz de encuesta de trekking

Formulario web móvil para relevamiento de demanda en circuitos de trekking de las siete regiones turísticas provinciales.

## Prueba local

Abrir `index.html`. Si no se configura un destino remoto, las respuestas se guardan en el almacenamiento local del dispositivo y el contador superior indica cuántas quedan pendientes.

## Conexión con Google Sheets

Asignar en `config.js` la URL `/exec` de una aplicación web de Google Apps Script compatible con recepción de JSON. La hoja prevista se denomina `Respuestas_Trekking`. Hasta completar esa configuración, la interfaz funciona en modo demostración y no transmite datos.

## Estructura territorial

Los selectores funcionan de forma dependiente: región turística, destino y circuito. El catálogo contempla Alto Neuquén, Vaca Muerta, Del Pehuén, De la Comarca, Confluencia, Del Limay y Lagos del Sur.
