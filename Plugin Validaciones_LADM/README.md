# Descripción.
El plugin Validaciones_LADM fue creado para facilitar la identificación de inconsistencias en la estructuración de la información almacenada dentro de una base de datos de PostgreSQL que almacene el modelo LADM Col Lev. Catastral 1.2. garantizando la consistencia lógica y temática de la misma.<br>
El plugin realiza 43 validaciones de calidad de la información generando reportes en formato Excel con cada uno de los registros que presentan inconsistencias dentro de la base de datos. Permitiendo reducir los tiempos y procesos de revisión de calidad.
<p align="center">  <img src="https://github.com/WilliamFelipeHuertasGarcia/Herramientas_LADM_COL_y_MAG_ANLA/blob/main/Plugin%20Validaciones_LADM/img/Plugin01.PNG" width="500"/> </p>

# Pasos para la instalación
1.	Instalar la librería XlsxWriter dentro del entorno Python de QGIS <br>
1.1.	Desde la barra de navegación del pc buscar ‘OSGeo4W Shell’ y escribir el comando 4w_env  
<p align="center">  <img src="https://github.com/WilliamFelipeHuertasGarcia/Herramientas_LADM_COL_y_MAG_ANLA/blob/main/Plugin%20Validaciones_LADM/img/Libreria01.PNG" width="250"/> </p>
1.2.	Posteriormente escribir el comando pip install xlsxwriter
<p align="center">  <img src="https://github.com/WilliamFelipeHuertasGarcia/Herramientas_LADM_COL_y_MAG_ANLA/blob/main/Plugin%20Validaciones_LADM/img/Libreria02.PNG" width="250"/> </p>
1.3.	Abrir QGIS y desde la ventana de Python importar la librería, si no marca error quiere decir que se instalo correctamente
<br>
Nota.  Si tiene mas de una versión de QGIS verifique que este instalando la librería en la versión en la que va utilizar el plugin.
Para esto antes de abrir ‘OSGeo4W Shell’ de clic derecho y escoja ‘abrir ubicación del archivo’, verifique que la carpeta corresponda con la versión de QGIS que va utilizar
<p align="center">  <img src="https://github.com/WilliamFelipeHuertasGarcia/Herramientas_LADM_COL_y_MAG_ANLA/blob/main/Plugin%20Validaciones_LADM/img/Nota01.PNG" width="200"/> </p>
2.	Instalar el plugin dentro de QGIS a partir del ZIP 
2.1.	Desde la ventana de complementos escoja la opción ‘Instalar a partir de ZIP’ seleccione el archivo y escoja la opción ‘Instalar complemento’
Nota. Recuerde habilitar el complemento si este no se visualiza.
<p align="center">  <img src="https://github.com/WilliamFelipeHuertasGarcia/Herramientas_LADM_COL_y_MAG_ANLA/blob/main/Plugin%20Validaciones_LADM/img/Instala01.PNG" width="300"/> </p>
