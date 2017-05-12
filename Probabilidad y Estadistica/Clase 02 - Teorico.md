# **Estadistica Descriptiva**

Datos: 

* Cualitativos: * Tablas
		* Graficos

* Cuantitativos * Tablas
		* Graficos
			* Discretas: Barras
			* Continuas: Histograma

## **Medidas de Posicion**

#### **Media Aritmetica**
	
* Es el valor promedio de las muestras  y es independiente de las amplitudes de los intervalos

La media estadistica es util para conocer la tendencia de los valores analizados, pero tiene una contra
que es que, dado un conjunto de datos parecidos, cercanos a la media; cuando haya alguna excepcion (o dato atipico), el
valor de la media puede cambiar, la cual no es representativa a la tendencia de los valores.

*Por este caso, la media siempre es buena para conocer la tendencia de los valores analizados, siempre y cuando
no haya valores atipicos.*

#### **Mediana**

*Es el valor central de los datos agrupados y ordenados. Ejemplo: (X1, X2, X3, X4, X5); mediana = X3. Puede no ser el valor promedio.*
Si la cantidad de datos fuera par, la mediana es el promedio de los dos centrales.

*Si la media es parecida o igual a la mediana, el conjunto de datos tiene una dispersion simetrica*
*Mientras mas parecidos sean estos dos valores, mas simetricos son los datos*

El diagrama de cajas es util solo para variables discretas. Cuando son continuas quedan graficos dificiles de analizar.

#### **Cuartiles

*Son los tres valores que dividen al conjunto de datos en partes porcentuales iguales (de igual cantidad).*
El cuartil 2 es igual a la media.

#### **Moda**
Es el valor mas repetido de un conjunto de datos. Para eso necesito tener frecuencia; osea, muchos datos.


## Medidas de dispersion

#### **Rango** 

*Es el valor mayor menos el valor menor.*

Ventaja, muestra entre que valores estan los datos. Desventaja, no tiene en cuenta que pasa en el medio de los datos,
osea no analiza la homogeneidad de los datos pues solo se concentra en dos valores, los extremos.

#### **Rango intercuartil**
es el cuartil 3 menos el cuartil 1. Elimina los valores atipicos. Muestra en que rango los datos estan mas concentrados.

#### **Varianza**

Es el promedio de las distancias respecto a la media. Muestra la concentracion de los datos. 
Usa todos los datos (ventaja). Como desventaja, es mas influenciable por valores atipicos al elevarse al cuadrado.

De todas formas, la varianza es muy dificil de interpretar, ya que un numero por si solo no nos dice nada (si es
mucho o poco); para esto necesitamos un punto de comparacion.

#### **Coeficiente de variacion**

Representa el porcentaje de la media respecto desvio. A mayor porcentaje, mayor variacion; y visceversa.
El desvio estandar es un porcentaje de la media. 

### **Teorema de desigualdad de Chebyshev**

Dado cun conjunto de datos con cierto valor medio; si se toma dos desvios a la derecha y dos desvios a la izquiera de la media
todos los valores comprendidos en ese rango es, como minimo, el 75% de la distribucion. y Si se toma un desvio mas por
lado, dichos valores son el 90% de la distribucion o mas.

Sirve para obtener un rango de valores, concentrada en 2 cuartiles, los cuales contienen la gran mayoria de valores (>90%)
A este rango se lo conoce como *rango de variacion natural*. Aquellos valores que esten fuera del rango de variacion natural
se los considera datos atipicos.

#### **Coeficiente de asimetria** 
Puede tener signo positivo o negativo. 

* Si me da cercano a 0, la distribucion es practicamente simetrica. Media similar a la moda.
* Si el signo es positivo, la distribucion es asimetrica con sesgo hacia la derecha. Media mayor a la moda
* Si el signo es negativo, la distribucion es asimetrica con sesgo hacia la izquierda. Media menor a la moda

Para calcular se pueden usar aproximaciones.

Si el coeficiente de simetria esta entre -0.5 y 0.5, la distribucion es aproximadamente simetrica. 

Si el coeficiente de simetria es > 0.5 o < 0.5, la distribucion es asimetrica. 

Es muy raro encontrar valores > |2|. 

# 
#

# **Unidad 2 - Probabilidad y Variables aleatorias**

### **Experimento Aleatorio**

1) Caracteristicas
* Tienen varios resultados, como minimo dos. 
* No se puede anticipar el resultado antes de hacer el experimento

Ejemplos: juegos de azar (dados, ruleta, lanzar una moneda, elegir una carta).

Pero no nos interesa realizar analisis en juegos de azar, sino en casos de la vida que acaten a la ingenieria.

Ejemplos: Comprobar la cantidad de lluvia en una zona especifica, verificar el nº de errores de un programa.


#### **Espacio muestreal de un experimento aleatorio**

Conjunto de todos los valores obtenidos por ese experimento aleatorio.

se usa la letra Omega. *Ejemplo:* 
* Tirar un dado: {1,2,3,4,5,6}
* Tirar una moneda: {Cara, cruz}
* Cantiadad de lluvia: {P \ P>= 0}
* Cantidad de errores de un programa: { 0,1,2,3,4 .... infinito}

#### **Evento**

Cualquier subconjunto de un espacio muestral.
A: tirar el dado y que salga el 3: {3}.
B: tirar el dado y que salga un numero par: {2,4,6}
C: tirar el dado y que salga un numero negativo: {}


**Eventos excluyentes** Son los que definen conjuntos los cuales no tienen elementos en comun.

**Eventos no excluyentes** Definen conjuntos los cuales tienen elementos en comun.

**Union de un conjunto A U B**: Es la suma de los elementos de A mas los elementos de B, sin repetir.

**Interseccion de un conjunto A n B:** Es la suma de los elementos comunes de A con los de B.

**Complemento de un conjunto A:** Aquellos elementos que estan en un conjunto que incluye a A, pero sin los elementos de A.

#### **Probabilidad** 

Es un numero que mide la posibilidad de que ocurra un evento. 

*p(A)*= probabilidad del evento A.

###### **Propiedades**

* 0 <= p(A) <= 1

p(Tirar dado y salga numero entre 1 y 6) = 1

P(A u B) = P(A) + P(B), si A n B son excluyentes.

### **Asignacion de probabilidades**

#### **Asignacion clasica**

p(A) = nº de caos favorables / nº de casos posibles.

Esto analiza casos en donde la probabilidad de un evento sea azar puro; osea la probabilidad de que ocurra cada uno de los eventos
posibles es la misma.

#### **Asignacion frecuencial** 

**p(A) = lim**    nº de casos favorables / nº de experimentos.
         n->∞




