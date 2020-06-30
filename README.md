# Mapeando el Universo
**Mentor**: Mario Agustín Sgró

**Enlaces a los repositorios de los mentoreados**
[Grupo 1] (https://github.com/bvaldeiglesias/astrodatos_grp_1)
[Grupo 2] (https://github.com/leoborgnino/mentoria-astro-datos)

![Sloan Digital Sky Server ><](./images/sloan.svg)

## Descripción

Para realizar realizar estudios de la distribución de materia en gran escala, los astrónomos deben contar con grandes relevamientos de galaxias que contengan información no sólo sobre su posición en la bóveda celeste y el brillo con que se las observa, sino también la distancia (o más precisamente el corrimiento al rojo, *redshift* por su nombre en inglés). Esta última propiedad es muy difícil de medir en grandes conjuntos de galaxias, dado que para ello, es preciso tomar el espectro individual de cada galaxias y analizarlo, lo cual lo hace un procedimiento costoso en muchos aspectos.
Por ello, hace algunas décadas se ha planteado el interrogante si es posible estimar la distancia a las galaxias, no ya realizando estudios espectroscópicos sino tomando datos fotomoétricos tales como el brillo que presenta una dada galaxia en diferentes bandas del espectro electromanético.

Nos propondremos en esta mentoria explorar estas posibilidades haciendo uso de las diferentes técnicas de *Machine Learning*.
Adicionalmente se podrán explorar otros aspectos interesantes donde es posible aplicar métodos de *Deep Learning* con datos astronómicos, como por ejemplo la clasificación del tipo morfológico de las galaxias.

Uno de los relavamientos público más extenso que posee en la actualidad la comunidad astronómica es el **Sloan Digital Sky Server** <sup>https://www.sdss.org/dr16/</sup>. Este catálogo provee información fotométrica para cerca de 500 millones de galaxias, sin embargo solo 1 millón de ellas poseen información espectroscópica (es decir, distancias). Contar con esta información para todo el conjunto de galaxias otorgaría a la comunidad con más datos que permitan contrastar los modelos actuales de la formación y evolución del Universo como un todo.

## Objetivo general

- Determinar el corrimiento al rojo (*redshift*) de galaxias a partir de datos fotométricos.

## Algunos objetivos específicos

- Analizar las distribuciones de los datos e identificar poblaciones de galaxias.
- Hallar correlaciones entre las variables.
- Explorar métodos de aumentación de información para "fabricar" nuevas variables.
- Emplear metodos de aprendizaje supervisado para construir un estimador de distancias.
- Estudiar métodos de aprendizaje no supervisado para encontrar grupos de galaxias.

### Bonnus track

En el caso de realizar la materia de **Deep Learning**

- Explorar el uso de redes neuronales para clasificación de galaxias según el tipo morfológico. 

## Base de datos

La base de datos es una porción del relevamiento SDSS. Una muestra se encuentra en la carpeta **dataseet**. El dataset completo se podrá bajar de una dirección específica luego. También se podrá tener acceso a la base de datos del relevamiento, donde se podrán realizar consultas SQL para extraer más datos en caso de ser necesario.

[Dataset 1](http://iate.oac.uncor.edu/~marioagustin/files/DiploDatos.csv)
[Dataset 2](http://iate.oac.uncor.edu/~marioagustin/files/DiploDatos_Zoo.csv)

## Hitos de la mentoría

Aquí iremos describiendo los diferentes trabajos prácticos.. por el momento solo las fechas

* 22/6 Análisis y visualización

  En esta primera etapa se trabajará con la visualización de los datos (distribución espacial, distribución de magnitudes, etc), determinación de las variables que serán de interés para el estudio futuro, y la correlación entre ellas. 

* 19/7 Análisis exploratorio y curación

  Aquí se trabajará con la "construcción" de nuevas variables a partir de las presentes en el dataset (tales como colores de las galaxias), se determinarán los datos faltantes y se limpiará el base de datos de outliers. 

* 16/8 Introducción al aprendizaje automático

  En esta etapa se planteará alguno de los métodos de regresión lineal y polinomial para predecir la distancias a las galaxias a partir de las variables fotométricas.

* 13/9 Aprendizaje supervisado

  Emplear árboles de decisión, multi-layer perceptron y redes neuronales con la misma finalidad.

* 27/9 Aprendizaje no supervisado

  Haciendo uso de los espectros se realizará una descomposición de componentes principales y se propondrá la utilización de algoritmos de clustering para analizar la población de galaxias. 

* 6/11/2020 – 7/11/2020 presentación de mentorías



