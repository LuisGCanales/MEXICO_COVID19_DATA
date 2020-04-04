


# Base de datos de casos positivos a COVID-19 en México / Database of positive cases of COVID-19 in Mexico.

```Última actualización/Last update: 2020-04-03 T 20:30:00-06:00```

<br>

___

![image](https://github.com/LuisGCanales/MEXICO_COVID19_DATA/blob/master/acumulativo_03_04_2020.png)


## Español

### Descripción
Compendio de los datos oficiales sobre casos positivos a *SARS-COV-2* (**COVID-19**), emitidos por la Secretaría de Salud (**SSA**) del Gobierno de México. Los datos son obtenidos a partir del Comunicado Técnico diario, publicado por la Dirección General de Epidemiología, de la SSA. 

• El dataset se encuentra para descargar en formato ``.CSV``, a partir del 4 de Abril del 2020 se encontrará también los formato ``.ODS`` y ``.JSON``.

**Nota :**  La base de datos cuenta con registros a partir del 28 de Febrero del 2020, fecha en que se reportaron los primeros casos positivos en México.

<br>

### Glosario de variables

•```No_caso```:  Originalmente ésta variable era un identificador único para cada caso. Lamentablemente a partir del 13 de Marzo del 2020 los encargados de elaborar los Comunicados Técnicos Diarios han modificado en varias ocasiones los formatos de los mismos y dentro de las modificaciones empezaron a re-indexar arbitrariamente los casos presentados diariamente. Dado lo anterior, ésta columna debe tomar únicamente como un índice auxiliar.

• ```Estado```:  Estado de la república mexicana en donde radica la persona diagnosticada como positivo. En el caso de personas extranjeras, estado de la república en el que se encuentran en aislamiento.

• ```Sexo```:  Masculino (**M**) ó Femenino (**F**).

• ```Edad```:  Edad, expresada en años.

• ```Inicio_sintomas```:  Fecha en que la persona diagnosticada como positivo presentó los primeros síntomas asociados a enfermedad por **COVID-19** en formato ``DD/MM/AAAA``.

• ``Procedencia``:  Aquí se identifican dos tipos de casos:

1) Importados: Casos diagnosticados como positivos después de haber estado presentes en algún otro país con casos vigentes de **COVID-19** en un tiempo no mayor a 14 días. Para este tipo de casos la variable ``Procedencia`` indica el país inmediato anterior a su ingreso a México.
 2) Locales: Casos diagnosticados positivos sin antecedentes de viaje al extranjero en un periodo menor a 14 días. Para este tipo de casos la variable ``Procedencia`` toma el valor '**Contacto**'.

• ``Llegada_a_Mex``:  Para casos importados indica la fecha de ingreso a México inmediata anterior a ser diagnosticados como positivos. Para casos locales ésta variable originalmente permanecía en blanco, sin embargo, a partir del informe emitido el 22 de Marzo del 2020 para algunos casos locales empezaron a reportar una fecha en ella, sin definir el significado de la misma. Estoy en proceso de investigación para esclarecer éste detalle, por lo pronto aconsejo no se tome en cuenta dicha fecha en casos locales.

• ``Diagnostico``: Fecha de la primera aparición en las *Tablas de casos positivos* del caso en cuestión, que corresponde con la fecha en que el caso se considera oficialmente como *positivo*.

<br>

**Nota:** A partir del 4 de Abril del 2020 estarán disponibles también los archivos origniales con los que se construyó la base de datos.

**Nota:** A partir del 6 de Abril del 2020 se encontrarán en otro repositorio de ésta misma cuenta todos los Scripts involucrados en la búsqueda, y procesamiento de los archivos originales, así como los dedicados a la construccción de la base de datos.

<br>

Con mucho gusto atenderé cualquier duda, comentario o contribución, a través de mi correo electrónico.

Contacto: lgco.canales@gmail.com

¡Por una cultura de **#DatosAbiertos**!
____


## English

### Description

Compendium of official data on positive cases for *SARS-COV-2* (**COVID-19**), published by the Mexico's Secretariat of Health (**SSA**). The data is obtained from the daily Technical Communication, published by the General Directorate of Epidemiology, Secretariat of Health.

**Note:** The database has records since February 28, 2020, date when the first positive cases were reported in Mexico.

## Glossary of variables (UNDER CONSTRUCTION)

<br>
If you have any questions, comments or contributions, please feel free to contact me.

Contact: lgco.canales@gmail.com

For an **#OpenData** culture!
____


