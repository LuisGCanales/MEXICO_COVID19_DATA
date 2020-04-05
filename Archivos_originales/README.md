



# Archivos Originales

```Última actualización/Last update: 2020-04-04 T 23:00:00-06:00```

<br>

___


Las *Tablas de casos positivos*, junto con los *Comunicados Técnicos Diarios* y las *Tablas de casos Sospechosos* son publicadas y actualizadas diariamente en la siguiente liga: [clic aquí](https://www.gob.mx/salud/documentos/coronavirus-covid-19-comunicado-tecnico-diario-238449). Lamentablemente no se conserva un histórico de las *Tablas de casos positivos*, y en ellas no se incluye la fecha en que cada caso fue reportado oficialmente como positivo, únicamente la fecha de inicio de síntomas y la fecha de ingreso al país, en el caso de los casos importados. Para construir la columna de fecha de confirmación oficial como casos positivos se procedío a buscar las tablas de días anteriores mediante técnicas de **crawling** directamente en la web de gob(punto)mx, y mediante el uso de las **API's** de [Google Caché](https://developers.google.com/web/fundamentals/instant-and-offline/web-storage/cache-api) y de [Wayback Machine](https://archive.org/).  La colección de archivos a partir de los que se construyó ésta base de datos se encuentran en ésta [sección](https://github.com/LuisGCanales/MEXICO_COVID19_DATA/tree/master/Archivos_originales/Tablas%20de%20casos%20positivos) del repositorio. Para descargar y  extraer la información de los archivos actuales, se utilizó la técnica de **scrapping**. Todo lo anterior, junto con la actualización de la base de datos se automatizó a través de scripts de **Python 3**, los cuáles estarán disponibles en otro repositorio de ésta misma cuenta a partir del 7 de Abril del 2020. 

**Nota:** Todos los archivos originales se encuentran en formato **.PDF**, a excepción de las tablas que corresponden a las siguientes fechas:

- 29/02/2020
- 13/03/2020

Los registros originales para este par de días se encuentran en formato **.HTML**, debido a que fueron obtenidos a través de la API de *Google Caché*, y únicamente los tenían almacenados en ese formato.

<br>


Con mucho gusto atenderé cualquier duda, comentario o contribución, a través de mi correo electrónico.

Contacto: lgco.canales@gmail.com

¡Por una cultura de **#DatosAbiertos**!
