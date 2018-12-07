# 17 Registro de Servidores Públicos de la Administración Pública Federal que intervienen en procedimientos de contrataciones públicas, el otorgamiento de licencias, permisos, concesiones y autorizaciones, así como en la enajenación de bienes muebles de la administración pública federal y en la asignación y emisión de dictámenes en materia de avalúos y justipreciación de rentas (RENIRESP)
Registro de los servidores públicos de la Administración Pública Federal que interviene en procedimientos de contrataciones públicas, el otorgamiento de licencias, etc.

## ¿Dónde están los datos?
+ [csv] Servidores públicos que intervienen en contrataciones en la Administración Pública Federal al mes de septiembre de 2015: http://datosabiertos.funcionpublica.gob.mx/datosabiertos/reniresp/reniresphistorico.csv



## ¿Qué campos contiene?
Siglas | Observaciones 
------------ | -------------
FOLIO | Clave que la Secretaría de Hacienda y Crédito Público (SHCP) asigna de manera única a cada programa o proyecto de inversión registrado por los ejecutores del gasto de los gobiernos locales en el sistema a través del cual se da seguimiento al ejercicio, destino y resultados de los recursos que la Federación transfiere a los gobiernos locales - SFU - (para conocer la definición completa consultar en el buscador "Sistema de Formato Único" del glosario que se encuentra en el Portal de Transparencia Presupuestaria: http://www.transparenciapresupuestaria.gob.mx/es/PTP/Glosario). El folio es exclusivo para dar seguimiento a los proyectos dentro de dicho sistema, por lo que no puede ser utilizado para comparar proyectos con otros sistemas de la SHCP.
NOMBRE_PROYECTO | Nombre del proyecto registrado por los ejecutores del gasto de los gobiernos locales
NUMERO_PROYECTO | Número del proyecto que es registrado por los usuarios de captura al momento de dar de alta un nuevo programa o proyecto de inversión en el SFU, a través del cual dan seguimiento a los mismos. Dicho número es asignado de acuerdo con los registros internos de las dependencias ejecutoras, por lo que no necesariamente se relaciona con el folio asignado por la SHCP en el SFU.
ID_ENTIDAD_FEDERATIVA | Clave de la entidad federativa, de acuerdo con el catálogo de entidades federativas, municipios y localidades del Instituto Nacional de Estadística y Geografía (INEGI)
ENTIDAD | Nombre de la entidad federativa, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
ID_MUNICIPIO | Clave del Municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
MUNICIPIO | Nombre del municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
ID_LOCALIDAD | Clave de localidad, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
LOCALIDAD | Nombre de la localidad, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
LATITUD | Coordenada geográfica en la que se ubica la localidad, de acuerdo con los catálogos del INEGI
LONGITUD | Coordenada geográfica en la que se ubica la localidad, de acuerdo con los catálogos del INEGI
AMBITO | Clasificación del INEGI para determinar si la localidad es rural (menos de 2,500 habitantes) o urbana (más de 2,500 habitantes)
ID_RECURSO | Clave de recurso: 1=Subsidios, 2= Aportaciones Federales; 3 = Convenios; 4=Fideicomisos
RECURSO | Identificador que permite conocer si el proyecto fue financiado a través de subsidios, Fondos de Aportaciones Federales, convenios o fideicomisos, los cuales constituyen los recursos que la Federación transfiere a los gobiernos locales para su ejecución. Se excluyen las participaciones dado que son recursos que se asignan a los gobiernos locales, en virtud de algunos de los ingresos que recauda la Federación, por lo que no cuentan con objetivos específicos definidos para su ejercicio y no deben ser reportados por los gobiernos locales a la Federación.
CLAVE_PROGRAMA_PRESUPUESTARIO | Clave con la cual se identifica a los programas presupuestarios federales. Está compuesta por 4 dígitos, el primero de los cuales señala la modalidad a la que pertenece el programa de acuerdo con sus características y los 3 dígitos restantes representan el número del programa presupuestario, el cual se asigna por las dependencias y entidades a partir del criterio de numeración consecutiva al interior de la modalidad de que se trate. Para mayor información sobre las modalidades que existen para los programas presupuestarios, se puede consultar el Anexo 2 del Manual de Programación y Presupuesto 2015: http://www.hacienda.gob.mx/EGRESOS/PEF/programacion/programacion_15/anexo_2_pyp2015.pdf
PROGRAMA_PRESUPUESTARIO | Nombre del programa presupuestario federal con el que se está financiando el programa o proyecto de inversión, de acuerdo con la estructura programática del PEF vigente. Por programa presupuestario se entiende a la categoría que permite organizar, en forma representativa y homogénea, las asignaciones de recursos de los programas federales y del gasto federalizado a cargo de los ejecutores del mismo, para el cumplimiento de sus objetivos y metas.
ID_RAMO | Clave del Ramo, de acuerdo con la estructura programática del PEF vigente
RAMO | Categoría administrativa a la que pertenece el programa presupuestario, de acuerdo con la estructura programática del PEF vigente
INSTITUCION_EJECUTORA | Ejecutores del gasto de los gobiernos locales, es decir, las dependencias, organismos o entidades de la entidad federativa, municipio o demarcación territorial del Distrito Federal que se encargarán de llevar a cabo el programa o proyecto de inversión
ID_CLASIFICACION | Clave que indica el sector al cual el programa o proyecto de inversión busca impactar de manera positiva:<br>0 = Otros Proyectos<br>1 = Salud<br>2 = Educación<br>3 = Transportes y vialidades<br>4 = Agua y saneamiento<br>5 = Urbanización<br>6 = Cultura y turismo<br>7 = Asistencia Social<br>8 = Deporte<br>9 = Seguridad<br>10 = Vivienda<br>11 = Comunicaciones
CLASIFICACION | Clasificación del programa o proyecto de inversión que realizan los ejecutores de los recursos para identificar categorías generales de atención, por ejemplo, educación, salud, seguridad, etc.
ID_TIPOPPI | Clave que indica el tipo de programa o proyecto de inversión, de acuerdo con la Guía de Criterios para el reporte del ejercicio, destino y resultados de los recursos federales transferidos:<br>0 = Sin tipo de proyecto o programa<br>1 = Proyecto de Inversión de Infraestructura Económica<br>2 = Proyecto de Inversión de Infraestructura Social<br>3 = Proyecto de Inversión de Infraestructura Gubernamental<br>4 = Proyecto de Inversión de Inmuebles<br>5 = Otros proyectos de Inversión<br>6 = Programa de Inversión de Adquisiciones<br>7 = Programa de Inversión de Mantenimiento<br>10 = Otros Programas de Inversión<br>11 = Programa de Estudios de Preinversión<br>Para mayor información, consultar la Guía de Criterios disponible en: http://transparenciapresupuestaria.gob.mx/work/models/PTP/Entidades_Federativas/SFU/Guia%20_de%20criterios%20_SFU%20VF_2.pdf
TIPOPPI | Nombre del tipo de programa o proyecto de inversión de acuerdo con la Guía de Criterios para el reporte del ejercicio, destino y resultados de los recursos federales transferidos, disponible en: http://transparenciapresupuestaria.gob.mx/work/models/PTP/Entidades_Federativas/SFU/Guia%20_de%20criterios%20_SFU%20VF_2.pdf
BENEFICIARIOS | Campo en donde los ejecutores del recursos describen los beneficios esperados del programa o proyecto de inversión.
INICIO | Fecha de inicio del programa o proyecto de inversión que es registrada por los ejecutores de los recursos al momento de dar de alta un programa o proyecto de inversión.
TERMINO | Fecha de término del programa o proyecto de inversión estimada por los ejecutores del gasto de los gobiernos locales.
DIRECCION | Dirección completa en la que, de acuerdo con el ejecutor del recurso, tendrá lugar el programa o proyecto de inversión.
ID_CONCURRENCIA_DE_RECURSOS | Clave que se utiliza para identificar si existen recursos de distintos órdenes de gobierno además del federal (estatal o municipal), éstas pueden ser:<br>Vacías = No se capturó información<br>0 = No existe concurrencia de recursos<br>1 = Coparticipación Federal-Estatal<br>2 = Coparticipación Federal-Estatal-Municipal<br>3 = Coparticipación Federal-Municipal
CICLO | Año en que los ejecutores del gasto crearon y/o modificaron por última vez la información del programa o proyecto de inversión.
MES | Mes en que los ejecutores del gasto crearon y/o modificaron por última vez la información del programa o proyecto de inversión.
KA_PROYECTO | Clave que al interior del Sistema de Formato Único (SFU) de la Secretaría de Hacienda y Crédito Público (SHCP) asigna de manera única a cada programa o proyecto de inversión registrado por los ejecutores del gasto de los gobiernos locales en el sistema a través del cual se da seguimiento al ejercicio, destino y resultados de los recursos que la Federación transfiere a los gobiernos locales.
FOLIO | Identificador que la SHCP asigna de manera única a cada programa o proyecto de inversión registrado por los ejecutores del gasto de los gobiernos locales en el sistema a través del cual se da seguimiento al ejercicio, destino y resultados de los recursos que la Federación transfiere a los gobiernos locales - SFU - (para conocer la definición completa consultar en el buscador "Sistema de Formato Único" del glosario que se encuentra en el Portal de Transparencia Presupuestaria: http://www.transparenciapresupuestaria.gob.mx/es/PTP/Glosario). El folio es exclusivo para dar seguimiento a los proyectos dentro de dicho sistema, por lo que no puede ser utilizado para comparar proyectos con otros sistemas de la SHCP.
NOMBRE_PROYECTO | Nombre del proyecto registrado por los ejecutores del gasto de los gobiernos locales.
NUMERO_PROYECTO | Número del proyecto que es registrado por los usuarios de captura al momento de dar de alta un nuevo programa o proyecto de inversión en el SFU, a través del cual dan seguimiento a los mismos. Dicho número es asignado de acuerdo con los registros internos de las dependencias ejecutoras, por lo que no necesariamente se relaciona con el folio asignado por la SHCP en el SFU.
KA_ESTATUS | Clave que indica el estatus en el que se encuentra la ejecución del programa o proyecto de inversión:<br>1 = En Ejecución<br>2 = Terminado <br>3= Suspendido<br>4= Cancelado
DESC_ESTATUS | Clave que indica el estatus en el que se encuentra la ejecución del programa o proyecto de inversión:<br>1 = En Ejecución<br>2 = Terminado <br>3= Suspendido<br>4= Cancelado
ID_ENTIDAD_FEDERATIVA | Clave de la entidad federativa, de acuerdo con el catálogo de entidades federativas, municipios y localidades del Instituto Nacional de Estadística y Geografía (INEGI).
ENTIDAD_FEDERATIVA | Nombre del municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI.
KA_MUNICIPIO | Clavedentro del SFU del Municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI.
ID_MUNICIPIO | Municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI.
MUNICIPIO | Nombre del municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI.
Ejercicio | Periodo al que corresponde la información
Id_ramo | Elemento identificador del Ramo
Id_ur | Elemento identificador de la Unidad Responsable
Ramo | Identifica y clasifica los recursos en el presupuesto de egresos a las Dependencias y en su caso Entidades, a la Presidencia de la República, a la Procuraduría General de la República y a los Tribunales Administrativos.
Institucion | Institución de la Administración Pública Federal
Ur | Se identifica con las unidades administrativas de los ejecutores de gasto del sector público federal y que para tales efectos se constituyen al contar con clave y que son sujetas a la programación, presupuestación, ejercicio, control y evaluación del gasto público federal que administran para contribuir al cumplimiento de la estructura programática autorizada al Ramo o entidad.
Primer_apellido | Primer apellido del servidor público
Segundo_apellido | Segundo apellido del servidor público
Nombre | Nombre del servidor público
Id_procedimiento | Identificador del procedimiento:<br>1- CONTRATACIONES PÚBLICAS<br>Se contemplan aquwellas sujetas a la Ley de Adquisiciones, Arrendamientos y Servicios del Sector Público (LAASSP), la Ley de Obras Públicas y Servicios Relacionados con las Mismas (LOPSRM) y la Ley de Asociaciones Público Privadas (LAPP)<br>2- CONCESIONES, LICENCIAS, PERMISOS, AUTORIZACIONES Y PRÓRROGAS<br>Comprende los regulados por las diversas disposiciones juídicas de carácter federal que otorgan las dependencias de la Administración Pública Federal (APF)<br>3- ENAJENACIÓN DE BIENES MUEBLES<br>Que incluyen los actos traslativos de propiedad de los bienes muebles de la federación y de las entidades paraestatales conforme a la Ley General de Bienes Nacionales (LGBN)<br> 4- ASIGNACIÓN Y EMISÓN DE DICTÁMENES DE AVALÚOS NACIONALES<br> Comprende únicamente los que son competencia del Instituto de Administración y Avalúos de Bienes Nacionales (INDAABIN)
Area_requiriente | Si el tipo de área es requiriente será 1, caso contrario 0.
Area_contratante | Si el tipo de área es contratante será 1, caso contrario 0.
Area_tecnica | Si el tipo de área es ténica será 1, caso contrario 0.
Area_responsable | Si el tipo de área es responsable será 1, caso contrario 0.
Area_otra | Si el tipo de área es otra será 1, caso contrario 0.
Id_nivel | Es el identificador del nivel de responsabilidad: 1 Atención o tramitación<br>2 Resolución<br>3 Atención o tramitación y Resolución
Ene | El servidor público fue reportado por la Institución como participante en los procesos descritos durante enero. 0 no fue reportado.
Feb | El servidor público fue reportado por la Institución como participante en los procesos descritos durante febrero. 0 no fue reportado.
Mar | El servidor público fue reportado por la Institución como participante en los procesos descritos durante marzo. 0 no fue reportado.
Abr | El servidor público fue reportado por la Institución como participante en los procesos descritos durante abril. 0 no fue reportado.
May | El servidor público fue reportado por la Institución como participante en los procesos descritos durante mayo. 0 no fue reportado.
Jun | El servidor público fue reportado por la Institución como participante en los procesos descritos durante junio. 0 no fue reportado.
Jul | El servidor público fue reportado por la Institución como participante en los procesos descritos durante julio. 0 no fue reportado.
Ago | El servidor público fue reportado por la Institución como participante en los procesos descritos durante agosto. 0 no fue reportado.
Sep | El servidor público fue reportado por la Institución como participante en los procesos descritos duranteseptiembre. 0 no fue reportado.
Oct | El servidor público fue reportado por la Institución como participante en los procesos descritos durante octubre. 0 no fue reportado.
Nov | El servidor público fue reportado por la Institución como participante en los procesos descritos durante noviembre. 0 no fue reportado.
Dic | El servidor público fue reportado por la Institución como participante en los procesos descritos durante diciembre. 0 no fue reportado.

Diccionario de Datos: http://datosabiertos.funcionpublica.gob.mx/datosabiertos/reniresp/diccionario_reniresp.xlsx

## ¿Quién otorga el dataset?
Secretaría de la Función Pública
