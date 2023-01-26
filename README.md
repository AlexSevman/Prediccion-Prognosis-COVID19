# Prediccion Prognosis COVID19
 Modelo prediccion de la prognosis en pacientes COVID19
 
En el presente trabajo se hace entrega de los siguientes documentos:

1)	Report Sevillano AM. Documento informe donde se puede encontrar la introducción, objetivos, análisis realizados, modelización-I y modelización -II (en esta ultima se elimina la variable ‘days_hosp’ ya que es una variable que no se toma al inicio del studio y se añaden variables sintéticas usando el algoritmo SMAT), conclusiones, direcciones futuras, diccionario de variables y referencias.
2)	Cuatro Python notebooks. 
a.	Loading_checking: Notebook en el que se cargan los datos iniciales y se realiza el primer chequeo sobre la salud de los datos (NaN). Se genera una table (PrettyTable) para la visualización de los datos estadísticos de todas las variables. 
b.	EDA. Notebook donde se realiza el análisis exploratorio de las variables, generación de nuevas variables y creación de un nuevo dataset que incluye solo datos de pacientes COVID19 positivos.
c.	Modelos Clasificación I. Notebook donde se tratan los datos para la modelización, estudio de PCA, y caracterización de los diferentes modelos de clasificación. 
d.	Modelos Clasificación II. Similar al Notebook Modelos Clasificación I, pero en este caso se han generado unos valores artificiales con el algoritmo SMOTE y posterior estudios de modelos de clasificación. 
3)	Dos documentos csv. Documentos generados durante el proceso de ‘Loading_Checking’ (COVID_pos) y tras el EDA (Clinical_EDA)

Alejandro M. Sevillano Mantas

