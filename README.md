# Monitor de Ataques DDoS Global en Tiempo Real con AbuseIPDB

Este proyecto proporciona una visualización en tiempo real de los ataques DDoS utilizando datos de IPs abusivas obtenidos a través de la API gratuita de AbuseIPDB. La aplicación muestra un mapa mundial con los reportes de IPs abusivas y actualiza la visualización cada minuto.

## Requisitos

- **Navegador Web**: La aplicación se ejecuta en cualquier navegador moderno que soporte HTML5 y JavaScript.
- **API Key de AbuseIPDB**: Necesitarás una clave API para acceder a los datos en tiempo real de AbuseIPDB.

## Configuración

1. **Clona el repositorio o descarga el archivo HTML**:
   - Si estás descargando desde un repositorio, usa `git clone <URL_DEL_REPOSITORIO>`.
   - Si estás descargando el archivo HTML, guárdalo en tu sistema local.

2. **Obtén una clave API de AbuseIPDB**:
   - Regístrate en [AbuseIPDB](https://www.abuseipdb.com/) para obtener una clave API gratuita.

3. **Reemplaza la clave API en el código**:
   - Abre el archivo HTML en un editor de texto.
   - Busca la línea que dice `const apiKey = 'YOUR_ABUSEIPDB_API_KEY';` y reemplázala con tu clave API de AbuseIPDB.

## Cómo Ejecutar

1. **Abre el archivo HTML**:
   - Abre el archivo HTML en tu navegador web. Esto debería mostrar el mapa global y comenzar a recibir datos de AbuseIPDB.

2. **Visualiza los ataques**:
   - El mapa mostrará las IPs abusivas en tiempo real como puntos rojos y líneas que indican ataques.
   - La sección de "Top 10 Países con IPs Abusivas" se actualizará con los países que más reportes tienen.

3. **Manejo de errores**:
   - Si hay problemas para conectar con la API de AbuseIPDB, se mostrará un mensaje de error en la pantalla. Asegúrate de que tu conexión a Internet esté funcionando y que la clave API sea correcta.

## Personalización

- **Intervalo de Actualización**:
  - Puedes ajustar el intervalo de actualización de los datos cambiando el valor en `setTimeout(fetchReports, 60000);` (el valor está en milisegundos).

- **Estilos**:
  - Modifica el CSS en el bloque `<style>` para cambiar la apariencia del mapa y los elementos de la interfaz.

## Contribuciones

Si deseas contribuir a este proyecto, puedes hacer un fork del repositorio, realizar tus cambios y enviar un pull request. También puedes reportar errores o sugerencias abriendo un problema en el repositorio.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para preguntas o soporte, por favor contacta a [tu_email@example.com](mailto:tu_email@example.com).

