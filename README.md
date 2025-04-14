# adjustnetwork.co.in
# Posible inyector de malware o adware

## Descripción
Se ha encontrado una página maliciosa que muestra notificaciones de alerta sobre un supuesto virus instalado en el sistema Windows. Estas alertas buscan engañar a los usuarios para que crean que su equipo está infectado y posiblemente los redirigen a sitios peligrosos.

## Evidencia Recopilada
Se adjuntan los siguientes archivos y registros como parte del análisis:

- **Capturas de pantalla** de la página maliciosa.
- **Logs de escaneo con Nmap**.
- **Resultados de escaneo con Nikto**.
- **Información del dominio** asociado.
- **Datos del servidor** donde está alojada la página.
- **Archivos descargados** de las páginas maliciosas utilizando `wget` para su posterior análisis.

## Hipótesis de Análisis
Se sospecha que la página analizada forma parte de una red de sitios fraudulentos que trabajan en conjunto para propagar este tipo de alertas falsas. Es probable que:

1. Se utilicen **terceros dominios** para distribuir estas notificaciones.
2. Haya una estrategia coordinada para generar **redirecciones engañosas**.
3. Se busque obtener información del usuario o inducirlo a descargar software malicioso.

## Procedimiento de Análisis
1. **Escaneo inicial** de la página y sus conexiones utilizando herramientas de seguridad como Nmap y Nikto.
2. **Recopilación de información del dominio** para identificar servidores y posibles vinculaciones con otras páginas sospechosas.
3. **Descarga de archivos sospechosos** para un análisis forense.
4. **Evaluación del comportamiento de la página**, revisando redirecciones y conexiones con terceros.

## Conclusiones y Recomendaciones
- No interactuar con alertas emergentes sospechosas.
- Evitar descargar software desde fuentes desconocidas.
- Realizar verificaciones de seguridad antes de ingresar credenciales en sitios web.
- Usar herramientas de monitoreo para detectar conexiones no autorizadas.

---
## VER CARPETA DE IMAGENES PARA REFERENCIA DE EVIDENCIA
