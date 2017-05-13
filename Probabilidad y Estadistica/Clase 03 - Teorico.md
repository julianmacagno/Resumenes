## **Probabilidades**

### **Reglas de probabilidades**

**Suma** - *P(AuB)*

Nos da la probabilidad de que curra un evento, el otro, o ambos.

`
  Ej: Tirar un dado y que salga un numero par o mayor a 4.
`

**Multiplicacion** - *P(AnB) (Probabilidad conjunta)*.

Sive para calcular la probabilidad de que dos eventos ocurran simultaneamente.

`
  Tirar un dado y que salga un numero par y mayor a 4
`

**Ejemplo**
  
1) P(AuB):
* Elementos no excluyentes.
* Se calcula como la probabilidad de que ocurra un evento mas la probabilidad de que ocurra la otra.
          
2) P(AnB):
* Elementos excluyentes.
* Admite eventos simultaneos o sucesivos (tirar dos monedas simultaneamente es lo mismo que tirar la misma moneda.
* Se calcula como la probabilidad de que ocurra un evento por la probabilidad de que ocurra el otro evento cuando YA ocurrio el primero (Si los eventos son dependientes). `P(A)*P(B/A)`

* (Si los eventos son independientes) Se calcula como la probabilidad de que ocurra un evento por la probabilidad de que ocurra el otro.

### **Variable aleatoria**

Es una funcion que asigna un valor (numerico) al resultado de un experimento aleatorio.

` Ej: X= nº que sale al tirar un dado {1,2,3,4,5,6}.`

` X= monto de precipitaciones de una lluvia {x/x>=0}`

Puede ser discreta o continuas.

#### **Funcion de probabilidad**

Se utiliza cuando la variable es discreta.

* p(x) = P(X=x) *Valuamos la funcion en ese punto. Nos devuelve dicho valor.*

#### **Funcion de Distribucion Acumulada**

F(x) = P(X<=x)

Permite calcular la probabilidad de que ocurra un evento.

1) Ejemplo: Tirar una moneda y que salga solo una cara

* `p(1)=P(X=1)=0,5`

2) Tirar una moneda y que salga a lo sumo una cara

* `P(x<=1)=F(1)=0,75`

3) Tirar una moneda y que no salga ninguna cara

* `P(x>1)=1-P(x<=1)=1-F(1)=0,25`

#### Valor esperado para una variable

E(X)=Mu

*Calculo para una variable aleatoria discreta*
    E(X)=sumatoria xi*p(xi)

# **Unidad 3: Modelos de probabilidades**

Se pretende aproximar el resultado o probabilidad de un experimento.

### **Tipos de modelos**

1) **Fisicos**

2) **Matematicos**

Nosotros vamos a estudiar los fenomenos matematicos.
Nos van a servir para aproximar el resultado o el comportamiento de una variable aleatoria.

Para ello, utilizamos diferentes modelos:

1) Modelos de variables discretas:

* Binomial
* Poisson

2) Modelos de variables continuas

* Normal
* Exponencial

**Ensayos de Bernoulli**

* Tiene dos resultados posibles: Exito o fracaso (Que ocurra o no el evento).
* La probabilidad de exito o fracaso son constantes.
* Los resultados son independientes.

### **Distribucion binomial**

Cuenta el numero de exitos en **n** ensayos de Bernoulli.

` Ejemplo: nº de caras en 10 tiradas de moneda: {1,2,3,...,10} `

Para calcular esto se utiliza la **funcion de probado binomial**
