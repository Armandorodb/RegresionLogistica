# Regresion Logistica

Realizaremos un análisis de diferentes vehículos para poder realizar la prediccion sobre si la cantidad de cilindros de un auto es mayor a 4 cilindros(1) o menor o igual a 4 cilindros(0) a través de una regresión logistica multiple.

Para realizar dicho estudio obtuvimos información del [UCI Machine Learning Repository](https://archive.ics.uci.edu/) específicamente de [Auto MPG](https://archive.ics.uci.edu/dataset/9/auto+mpg) de un estudio de Quinlan, R. (1993).

Dicha información cuenta con las siguientes variables:

MPG: Miles per galon, millas por galón, nuestra variable de interés.    
Cylinders: La cantidad de cilindros del auto.   
Displacement: Volumen total de aire y combustible que un auto puede desplazar en un ciclo de combustión.   
Horsepower: Caballos de fuerza, es una medida de potencia.   
Weight: Peso en libras.   
Acceleration: Aceleración.     
Model year: Año del modelo de auto.   
Origin: País de origen del auto. 1: America, 2: Europa, 3: Asia   
Car Name: Modelo del auto.   
  
La base de datos tenía algunos valores de la variable de interés como NaN, se eliminaron esas filas ya que considero que cualquier manera de conseguir ese valor añadiría incertidumbre a nuestro modelo. Estaríamos construyendo nuestro modelo en terreno que no es firme.

Ajustaremos los datos para poder realizar nuestro objetivo.
