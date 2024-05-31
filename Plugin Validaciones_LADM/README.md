# Descripción.
El plugin Validaciones_LADM fue creado para facilitar la identificación de inconsistencias en la estructuración de la información almacenada dentro de una base de datos de PostgreSQL que almacene el modelo LADM Col Lev. Catastral 1.2. garantizando la consistencia lógica y temática de la misma.
El plugin realiza 43 validaciones de calidad de la información generando reportes en formato Excel con cada uno de los registros que presentan inconsistencias dentro de la base de datos. Permitiendo reducir los tiempos y procesos de revisión de calidad.
# Pasos para la instalación
1.	Instalar la librería XlsxWriter dentro del entorno Python de QGIS
1.1.	Desde la barra de navegación del pc buscar ‘OSGeo4W Shell’ y escribir el comando pip install xlsxwrite
1.2.	Abrir QGIS y desde la ventana de Python importar la librería, si no marca error quiere decir que se instalo correctamente
Nota.  Si tiene mas de una versión de QGIS verifique que este instalando la librería en la versión en la que va utilizar el plugin.
Para esto antes de abrir ‘OSGeo4W Shell’ de clic derecho y escoja ‘abrir ubicación del archivo’, verifique que la carpeta corresponda con la versión de QGIS que va utilizar
2.	Instalar el plugin dentro de QGIS a partir del ZIP 
2.1.	Desde la ventana de complementos escoja la opción ‘Instalar a partir de ZIP’ seleccione el archivo y escoja la opción ‘Instalar complemento’
Nota. Recuerde habilitar el complemento si este no se visualiza.
