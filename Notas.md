**Notas**

Scikit-learn es probablemente la librería más útil para Machine Learning en Python, es de código abierto y es reutilizable en varios contextos, fomentando el uso académico y comercial. Proporciona una gama de algoritmos de aprendizaje supervisados y no supervisados en Python.
Este librería está construida sobre SciPy (Scientific Python) e incluye las siguientes librerías o paquetes:

- NumPy: librería de matriz n-dimensional base
- Pandas: estructura de datos y análisis
- SciPy: librería fundamental para la informática científica
- Matplotlib: trazado completo 2D
- Ipython: consola interactiva mejorada
- SymPy: matemática simbólica
---

Las principales funcionalidades que se pueden definir en un modelo de ML son

- Aprendizaje supervisado
  -  Predecir una métrica => Predecir un valor
  -  Predecir una etiqueta => Si alguien esta enfermo o no
- Aprendizaje no supervisado
- Agrupar elementos similares => Clustering
- Optimizar proceso con prueba y error => Test A/B


Machine Learning

Es una disciplina científica del ámbito de la Inteligencia Artificial que crea sistemas que aprenden automáticamente. Aprender en este contexto quiere decir identificar patrones complejos en millones de datos. La máquina que realmente aprende es un algoritmo que revisa los datos y es capaz de predecir comportamientos futuros. Automáticamente, también en este contexto, implica que estos sistemas se mejoran de forma autónoma con el tiempo, sin intervención humana.


Ámbitos de aplicación del Machine Learning

Muchas actividades actualmente ya se están aprovechando del Machine Learning. Sectores como el de las compras online – ¿no te has preguntado alguna vez cómo se decide instantáneamente los productos recomendados para cada cliente al final de un proceso de compra? –, el online advertising – dónde poner un anuncio para que tenga más visibilidad en función del usuario que visita la web – o los filtros anti-spam llevan tiempo sacando partido a estas tecnologías.

El campo de aplicación práctica depende de la imaginación y de los datos que estén disponibles en la empresa. Estos son algunos ejemplos más:


- Detectar fraude en transacciones.

- Predecir de fallos en equipos tecnológicos.

- Prever qué empleados serán más rentables el año que viene (el sector de los Recursos Humanos está apostando seriamente por el Machine Learning).

- Seleccionar clientes potenciales basándose en comportamientos en las redes sociales, interacciones en la web…

- Predecir el tráfico urbano.

- Saber cuál es el mejor momento para publicar tuits, actualizaciones de Facebook o enviar las newsletter.

- Hacer prediagnósticos médicos basados en síntomas del paciente.

- Cambiar el comportamiento de una app móvil para adaptarse a las costumbres y necesidades de cada usuario.

- Detectar intrusiones en una red de comunicaciones de datos.

- Decidir cuál es la mejor hora para llamar a un cliente.
-
---
## 11.-

[Link a los datasets](https://github.com/JuanPabloMF/datasets-platzi-course)

Si no les ha funcionado en Google Colaboraty ya que el enlace de git es la página, deben cargar el link del raw (archivo bruto)

Este es el link que obtendríamos al navegar por git :
https://github.com/JuanPabloMF/datasets-platzi-course/blob/master/datasets/peliculas.csv

Hay dos opciones:

1. Poner un `?raw=true` al final de la url: https://github.com/JuanPabloMF/datasets-platzi-course/blob/master/datasets/peliculas.csv?raw=true

```python
import pandas as pd

movies = pd.read_csv('https://github.com/JuanPabloMF/datasets-platzi-course/blob/master/datasets/peliculas.csv?raw=true',encoding='utf-8')
```

1. Reemplazar la palabra blob por raw
https://github.com/JuanPabloMF/datasets-platzi-course/raw/master/datasets/peliculas.csv

```python
import pandas as pd

movies = pd.read_csv('https://github.com/JuanPabloMF/datasets-platzi-course/raw/master/datasets/peliculas.csv',encoding='utf-8')
```















## 12.-