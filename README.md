# Predicción por KNN y Naive Bayes (alumos graduados y desertados)

En este proyecto vamos a ver las diferencias al utilizar Naive Bayes y KNN, dos métodos de clasificación distintos los cuales su objetivo final es predecir si un alumno se graduará o desertará de acuerdo a ciertos factores.

## Introducción 

En la actualidad cada vez más personas tienen acceso a la educación pero existen diferentes factores ya sea externos o internos que afectan las probabilidades de que un alumno se gradue o no; entre ellos: la nacionalidad, edad, género, inflación en el país que residen, tasa de desempleo y claro rendimiento en la escuela. Analizar este tipo de datos no solo nos da información requerida para clasificar sino también nos puede abrir un panorama más amplio para ubicar ciertos factores que pueden facilitar la deserción escolar. De esta manera se pueden localizar a los alumnos que tienen más riesgo de sufrir un abandono escolar y buscar soluciones o exponer los resultados para que un experto en el tema opine. <br> <br>
Por eso en este proyecto se puede observar la utilización y manipulación de cierto tipo de datos utiizando 2 diferentes métodos, especificamente KNN y Naive Bayes para clasificar.

## Materiales y métodos

Los métodos utilizados pertenecen al aprendizaje supervisado, los cuales son algoritmos trabajan con datos “etiquetados”, intentado encontrar una función que, dadas las variables de entrada, les asigne la etiqueta de salida adecuada. El algoritmo se entrena con un “histórico” de datos y así “aprende” a asignar la etiqueta de salida adecuada a un nuevo valor, es decir, predice el valor de salida.

Los datos a utilizar se bajaron de una plataforma llamada kaggle con el titulo "Predict Dropout or Academic Success" con más de 4000 registros. Los atributos que contiene este dataset son: Estado civil, Modo de solicitud, Orden de solicitud,
       Curso, Asistencia diurna/nocturna, Título anterior,
       Título previo (grado), Nacionalidad,
       Calificación de la madre, Calificación del padre,
       Ocupación de la madre, Ocupación del padre, Grado de admisión,
       Desplazado, Necesidades educativas especiales, Deudor,
       Tasas de matrícula al día, Género, Titular de la beca,
       Edad de inscripción, Internacional,
       Unidades curriculares 1er sem (acreditado),
       Unidades curriculares 1er sem (matriculados),
       Unidades curriculares 1er sem (evaluaciones),
       Unidades curriculares 1er sem (aprobado),
       Unidades curriculares 1er sem (grado),
       Unidades curriculares 1er sem (sin evaluaciones),
       Unidades curriculares 2º sem (acreditado),
       Unidades curriculares 2º sem (matriculados),
       Unidades curriculares 2º sem (evaluaciones),
       Unidades curriculares 2º sem (aprobado),
       Unidades curriculares 2º sem (grado),
       Unidades curriculares 2º sem (sin evaluaciones),
       Tasa de desempleo, Tasa de inflación, PIB, y Target. Lo que vamos a predecir es Target la cual viene dividida en 3 partes que es, graduado, deserto e inscrito, los alumnos que estan inscritos no resultan útiles a la hora de predecir así que  se eliminó todas las filas que estén clasificadas de esa manera. Tambien se observo que el curso no servía para la clasificación ya que la distribución está sesgada a la derecha
       
### Dataset
https://www.kaggle.com/datasets/ankanhore545/dropout-or-academic-success
       
