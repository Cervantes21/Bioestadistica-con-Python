# **Estadística Descriptiva**

## **Introducción**:

La estadística es la rama de las matemáticas aplicadas que permite estudiar fenómenos cuyos resultados son en parte inciertos. 

Al estudiar sistemas bilógicos, esta incertidumbre se debe al desconocimiento de muchos de los mecanismos fisiológicos y fisiopatológicos, a la incapacidad de medir todos los determinantes de la enfermedad y a los errores de medida que inevitablemente se producen. Así, al realizar observaciones en clínica o en salud pública, los resultados obtenidos contienen una parte sistemática o estructural, que aporta información sobre las relaciones entre variables estudiadas, y una parte de *"ruido"* aleatorio.

El objeto principal de la estadística consiste en extraer la máxima información sobre estas relaciones estructurales a partir de los datos recogidos.

En estadística se distinguen dos grandes grupos de técnicas:

### La ***estadística descriptiva***,
en la que se estudian las técnicas necesarias para la organización, presentación y resumen de los datos obtenidos.

### La ***estadística inferencial***, 
en la que se estudian las bases lógicas y las ténicas mediante las cuales pueden establecerse conclusiones sobre la población a estudio a partir de los resultados obtenidos en una muestra.

> El análisis de una base de datos siempre partirá de técnicas simples de resumen de los datos y presentación de los resultados. 

Las técnicas de **estadística descriptiva** no precisan de asunciones para su interpretación, pero en contrapartida la información que proporcionan no es fácilmente generalizable.

La **estadística inferencial** permite esta generalización, pero requiere ciertas asunciones que deben verificarse para tener un grado razonable de seguridad en las inferencias.

## **Definiciones de conceptos generales**

### ***Población***: 
Es el conjunto de todos los elementos que cumplen ciertas propiedades y entre los cuales se desea estudiar un determinado fenómeno.

### ***Muestra***: 
Es un subconjunto de la población seleccionado mediante un mecanismo más o menos explícito. En general, rara vez se dispone de los recursos necesarios para estudiar a toda la población y, en consecuencia, suelen emplearse muestras obtenidas a partir de estas poblaciones.

#### **Algunos ejemplos de poblaciones son:**

- Los residentes de Washington D.C.
- Las personas infectadas con COVID en Brasil

    **Para estás poblaciones, algunas muestras podrían ser**:

    - 500 Residententes de Washington D.C. Seleccionados aleatoriamente en un rango de edades de 20-67 años.
    - Todas las personas que acuden a los hospitales de *Río de Janeiro* durante un périodo de 6 meses para realizarse una prueba de **COVID**.

### **Variables**
son propiedades o cualidades que presentan los elementos de una población. Las variables pueden clasificarse en:

#### **Variables cualitativas o atributos**:
Son aquellas que no pueden medirse numéricamente y que, a su vez, pueden ser:

- ***Nominales***, en las que no pueden ordenarse las diferentes categorías.
- ***Ordinales***, en las que pueden ordenarse las categorías, pero no puede establecerse la distancia relativa entre las mismas.
- En **Python** Tenemos los valores ***bool*** que trabajan con valores buleanos, o binarios. De Verdadero, o Falso
#### **Variables cuantitativas**:
Son aquellas que tienen una interpretación numérica y que se subdividen en:

- ***Discretas***, sólo pueden tomar unos valores concretos dentro de un intervalo. En este caso los podemos llamar también números enteros. En ***Python se conoce como valores int***

- ***Continuas***, pueden tomar cualquier valor dentro de un intervalor. También conocidos como números decimales. En ***Python son valores float***

##### **Algunos ejemplos de variables son:**

- **Variables cualitativas nominales**: sexo, raza, estado civil(soltero, casado, viudo, separado, divorciado), religión, nacionalidad.
- **Variables cualitativas ordinales**: salud auto-percibida(buena, regular, mala), severidad de la enfermedad(leve, moderada, grave). Cada uno de estos valores también pueden ser preprocesados posteriormente por una representación númerica. Calificación de satisfacción con estrellas en dónde 1 es malo y 5 es bueno.
- **Variables cuantitativas discretas**: Número de hijos, número de dientes, número de familiares. Aquello que no puede ser divisible.
- **Variables cuantitativas continuas**: edad, peso, altura, presión arterial, niveles de colesterol en sangre, etc. Aquello que puede ser divisible, o escalable.

### **Estadístico**:
es cualquier operación realizada sobre los valores de una variable.

### **Párametro**:
es un valor de la población sobre el que se desea realizar inferencias a partir de estadísticos obtenidos de la muestra, que en este caso se denominan **estimadores**. Por convención, los parámetros poblacionales se denotan con letras del alfabeto griego, mientras que los estimadores muestrales se denotan con letras de nuestro alfabeto.

#### **Algunos ejemplos estadísticos incluyen:**

- La media de los valores de colesterol de una muestra.
- El valor más alto de colesterol de una muestra.
- La suma de los valores de colesterol de una muestra elevados al cuadrado.

Así, por ejemplo, la media del colesterol en una población, que se denotaría por ***µ*** (mu), es un parámetro que se estima a partir de la media de los valores de colesterol en una muestra obtenida de esa población, que se representaría por ***X***

