# A2.2-LDA-y-Arboles-de-Decision

El porposito de este codigo es analizar la base de datos de la INEGI sobre la cantidad de vehiculos, ya sean autos, motos, camiones o trailers dependiendo del estado en el año 2024

Nos centraremos en hacer una regresion logistica, Linear Discriminant Analysis (LDA) y un Árbol de desiciones, todo esto para realizar fierentes clasificacion de la variable AUTOS_PARTICULARES que sera convertida a CANTIDAD_AUTOS clasificandolos con sus promedio. 

Todo esto para analizar que metodologia es mejor para esta base de datos calsificar, principalmente entre LDA y Árbol de desiciones.

Se cuenta con los siguientes datos
- ID_ENTIDAD: Clave de la entidad federativa de México, va del 1 al 32 respresentando cada estado de México.
- AUTO_OFICIAL: Autos que cuantan con hasta 7 asientos son utilizados por los organismos gubernamentales en el municipio.
- AUTO_PUBLICO: Autos que cuantan con hasta 7 asientos son utilizados como servicios para el traslado de personas, bienes o mercancia en el municipio.
- AUTO_PARTICULAR: Autos que cuantan con hasta 7 asientos son de la propiedad de cada persona en el municipio.
- CAM_PAS_OFICIAL: autobuses urbanos y suburbanos, microbuses, camiones escolares, camionetas pick-up (utilizadas para el transporte de trabajadores), los vehiculos con más de 7 asientos, cuyas unidades son utilizadas por los organismos gubernamentales para satisfacer sus propios requerimientos y/o atender las necesidades de la población.
- CAM_PAS_PUBLICO: Autobuses urbanos y suburbanos, microbuses, camiones escolares, camionetas pick-up (utilizadas para el transporte de trabajadores), los vehiculos con más de 7 asientos, cuyas unidades son utilizadas por el publico en general como un servicio.
- CAM_PAS_PARTICULAR: Autobuses urbanos, microbuses, camiones escolares, camionetas pick-up (utilizadas para el transporte de trabajadores), los vehiculos con más de 7 asientos. Las unidades son destinadas al autotransporte de pasajeros o bienes por cuenta propia.
- CYC_CARGA_OFICIAL: Camiones de carga diseñados para el remolque que son utilizadas por los organismos gubernamentales.
- CYC_CARGA_PUBLICO: Camiones de carga diseñados para el remolque que son utilizadas como servicio para el traslado de bienes o mercancías.
- CYC_CARGA_PARTICULAR: Camiones de carga diseñados para el remolque que son destinadas al autotransporte de bienes o mercancías por cuenta propia.
- MOTO_OFICIAL: Vehiculos automotor de dos, tres o cuatro ruedas, utlizadas por los organmismos gubernamentales.
- MOTO_DE_ALQUILER: Vehiculos automotor de dos, tres o cuatro ruedas, que son utilizadas por el público en general como un servicio. 
- MOTO_PARTICULAR: Vehiculos automotor de dos, tres o cuatro ruedas, destinadas al autotransporte de pasajeros o bienes.

Los documentos son:
- [Reporte en formato html](./A2_2_LDA_y_Arboles_de_Decision.html)
- [Reporte en formato ipynb](./A2_2_LDA_y_Arboles_de_Decision.ipynb)
- [Base de datos](./P1-Vehiculos-en-Circulacion-Limpiada.csv)
- [Diccionario de los datos](./diccionario_datos_vmrc_anual_1980_2024.csv)
