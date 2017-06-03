# Unidad 4: Inferencia estadistica

Poblacion Posee parametros(caracteristicas) como la media y la varianza.

Muestra Posee estimadores (caracteristicas) como el promedio o el desvio.

Se desea aproximar el comportamiento de una poblacion a partir de una muestra, ya que no es posible analizar a la poblacion en su totalidad, debido a su tamaño y complejidad. Para ello se utiliza la inferencia estadistica, que permite deducir en base a casos particulares, conceptos generales.

Para ello se recurre a metodos de muestreos para producir muestras representativas y significativas:

### Para muestras:

* No aleatorias: No se puede evaluar el error.

* Aleatorios:

    -Muestreo aleatorio simple (sorteo).

    -Muestreo sistematico.

### Propiedades de una buena muestra
    
**Homogeneidad:** En una muestra homogenea, todos los elementos son extraidos de la misma poblacion. Ejemplo (hacer una encuesta del padron electoral y encuestar a gente que no corresponde al mismo).

**Independencia:** Para que la muestra sea valida, los datos deben ser independientes unos de otros.

**Representatividad:** Para que una muestra sirva, tiene que ser suficientemente representativa. Esto quiere decir que los datos deben reflejar todas las variaciones posibles que hay en la poblacion. (Distintos sectores sociales, raza, genero, ocupacion, etc).

`
    Notacion (O -> Parametro; Ô -> estimador).
`

### Parametros y estimadores

1) **Parametro:** 
* Caracteriza a la poblacion. 
* Por lo general no conozco los datos o parametros (ya que necesito informacion respecto a toda la poblacion y justamente eso estamos tratando de inferir). 
* Valores fijos (no aleatorios).

2) **Estimador:** 
* Caracteriza a la muestra. 
* Si conozco los valores de la muestra. 
* Son variables aleatorias, tienen una distribucion de probabilidades.


## Distribuciones de muestreo

*Es la distribucion de los estimadores muestrales*

De todos los estimadores que conocemos, el que mas se utiliza en la practica es la media aritmetica. Entonces: 

#### **Distribucion de la media aritmetica:** 

**Sea x1, x2, x3, ... xn; una muestra aleatoria de tamaño n de una variable aleatoria X con distribucion Normal(mu,signa-cuadrado):** -> Podemos considerar a las observaciones como variables aleatorias con distribuciones iguales a la poblacion. 

Sea X=(x1+x2+x3...+xn)/n

Si X es la sumatoria de variables aleatorias, X es tambien una variable aleatoria con la misma distribucion que las variables aleatorias.
La varianza de la media es igual a signa-cuadrado/n.

*Que pasa si la variable que estamos analizando no tiene distribucion normal o si distribucion es desconocida?* Si sumamos muchas variables aleatorias (mas de 30) identicamente distribuidas , por el **Teorema del Limite Central**, la sumatoria va a tener distribucion aproximadamente normal. Por ende, todo lo anterior es valido.


**Cuanto mas grande sea el tamaño de una muestra, menos dispersion y menos error voy a obtener en los valores de una muestra (media); respecto al valor real**

## Herramientas de inferencia

### Estimacion de parametros y pruebas de hipotesis

1) **Estimacion de parametros:** Busca realizar estimaciones de los valores de los parametroos de una poblacion. 

2) **Pruebas de hipotesis:**

**Para estimacion de parametros tenemos dos formas de realizarse:**

* **Por intervalo:** 

* **Puntual:** Se calcula puntualmente un unico valor del parametro desconocido. Para ello se utiliza: 
    - Promedio
    - Mediana
    - Moda
    - Valor mismo de la variable

*Nosotros nos vamos a concentrar en la estimacion puntual.*

#### Propiedades de un buen estimador

* **Estimador Insesgado E(Ô)=O:** la media del estimador coincide con el esperado (el parametro). Podriamos utilizar la media aritmetica o promedio; el cual tiene el mismo valor que el valor esperado o parametro (Mu).
* **Estimador Consistente:** Si n->infinito, var(Ô)->0.
    Ejemplo: para X(media), var(X)=G-cuadrado/n; n->infinito, var(X)->0.
* **Estimador Eficiente:** Debe poder encontrar estimadores los cuales encuentren estimaciones con menor varianzas. Para dos estimadores, aquel que tenga una carianza menor es la mas eficiente. Osea aquel que aprovecha mejor  a la mustra.
    Ejemplo: Para x(media), var(X)=G-cuadrado/n. Para M(mediana), var(M)=G-cuadrado * Pi/2.
* **Estimador Suficiente:** Para que un estimador sea suficiente, este debe trabajar con la mayor cantidad de datos posibles; lo ideal seria con todos los datos.
* Ejemplo, el Promedio trabaja con todos los elementos, la Mediana solo con el valor central. El promedio es mas suficiente.    

**Con todo lo anterior, concluimos que la Media Aritmetica o Promedio es un muy buen estimador, ya que es Insesgado, Consistente, Eficiente y Suficiente.** Por este motivo, siempre se usa la Media Aritmetica o Promedio como estimador.
