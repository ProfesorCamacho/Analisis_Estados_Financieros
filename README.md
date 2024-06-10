# Analisis_Estados_Financieros
Muchas veces cuando queremos invertir nos damos cuenta que existen una infinidad de empresas, ¿cómo saber cuál es "la buena"? Aquí se suguiere hacer un análisis que nos permite saber en que empresa confiar, basado en los resultado de sus estados financieros. 




En este repositorio se ejemplifica el analisis de estados financieros para evaluar la posibilidad de inversión en empresas en la bolsa de valores de Estados Unidos.
Se agrega la base de datos en archivo db, debido a que se obtuvo en SQLite para manejar la base de datos.
La base de datos contiene el estado de resultados trimestral de los ultimos quince años para muchas empresas, en formato estandarizado como exige la SEC (Security Exchange Comission) a las empresas.
La base de datos es fácil de leer. Se puede configurar para que se lea algunos valores de acuerdo a su tipo (fecha, int, char), sin embargo en este caso yo opte por hacer esa cuestión en Jupyter Notebook. 
Existen algunas columnas que aportan poca información y parece repetitivas, pueden ser borradas sin ningun problema ya que no se usan en el análisis. Yo no lo hago porque me interesa preservar la información en caso de ser requerida.
