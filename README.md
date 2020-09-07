# IIC3633 Sistemas Recomendadores
10 de agosto, 2020

### Equipo Docente e Información Administrativa
**Instructor**: [Denis Parra](http://dparra.sitios.ing.uc.cl), Profesor Asociado PUC Chile, Ph.D. University of Pittsburgh

**Ayudantes**:  
[Vladimir Araujo](https://vgaraujov.github.io/), Alumno de Doctorado en Ciencia de la Computación PUC Chile.  
Manuel Cartagena, Alumno de Magister en Ciencia de la Computación PUC Chile.  
[Andrés Carvallo](https://scholar.google.com/citations?user=DinpmCUAAAAJ&hl=es), Alumno de Doctorado en Ciencia de la Computación PUC Chile.  
[Francisca Cattan](https://www.linkedin.com/in/franciscacattan/), Alumna de Doctorado en Ciencia de la Computación PUC Chile.  
[Andrés Villa](https://www.linkedin.com/in/andres-felipe-villa-ojeda-b3132811b), Alumno de Doctorado en Ciencia de la Computación PUC Chile.  

**Institución**: Pontificia Universidad Católica de Chile

**Horario**: Martes y Jueves, Módulo 3 (11:30 a 12:50).

Programa IIC 3633, 2do Semestre 2020: [pdf](http://dparra.sitios.ing.uc.cl/classes/recsys-2019-2/IIC3633Sist%20Recomendadores_v3.pdf).

### Descripción del Curso

El curso de Sistemas Recomendadores cubre las principales tareas de recomendación, algoritmos, fuentes de datos y evaluación de estos sistemas. Al final de este curso serás capaz de decidir qué técnicas y fuentes de datos usar para implementar y evaluar sistemas recomendadores.

**Software**: [pyRecLab](https://github.com/gasevi/pyreclab/).

La componente práctica de este curso se enseña a través del uso de pyRecLab desarrollado por Gabriel Sepúlveda (ex-alumno de este curso), biblioteca de software para desarrollo de sistemas recomendadores en Python.

**Contenido**:

## Contenidos por Semana

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->

| Semana  | Tema             | link slide(s) | link video | comentario(s) |
|:--------|:-----------------|:-------------:|:----------:|:-------------:|
| 1       | Introducción                                          | x    | [video](https://drive.google.com/file/d/1lhHoO0JN5PI-6tc9samHx7ui7iB-ycV-/view?usp=sharing)    |                   |
| 1       | Ranking no personalizado y Filtrado colaborativo (FC) | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s1-c2-nonpers-UBCF.pdf)    | [video](https://drive.google.com/file/d/1PrlxIa_qx5n4s-OylzXyMQeuErqCl_Py/view?usp=sharing)    |                   |
| 1       | User-based FC con clustering                          | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s1-c2-UBCF_clustering.pdf)    | [video](https://drive.google.com/file/d/15gwdIm7MlVhBltB1vjOhsKW6n7ezqw0f/view?usp=sharing)  |                   |
| 1       | Pendiente Uno                                         | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s1-c2-SlopeOne.pdf)    | [video](https://drive.google.com/file/d/15gwdIm7MlVhBltB1vjOhsKW6n7ezqw0f/view?usp=sharing)   |                   |
| 2       | Item-based FC                                         | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s2_c1-IBCF.pdf)    | [video](https://drive.google.com/file/d/15gwdIm7MlVhBltB1vjOhsKW6n7ezqw0f/view?usp=sharing)    |                   |
| 2       | Factorización Matricial: FunkSVD                      | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s2_c2-Factorizacion_matricial.pdf)    | [video](https://drive.google.com/file/d/1Wi5O1VKrx72Ux0LdhxcAAL0FXSGV7FVQ/view)    |                   |
| 3       | Implicit Feedback CF                                  | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s3_c1-Implicit-feedback.pdf)    | [video1](https://drive.google.com/file/d/1hAxJpXX6VMgEcTQTfUtHNu-7ttDYTG9o/view?usp=sharing) [video2](https://drive.google.com/file/d/1EH59esO_bnd6t3YJm-gw6PhM0mHbqRqd/view?usp=sharing)   |                   |
| 3       | Bayesian Personalized Ranking (BPR)                   | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s3_c2-BPR.pdf)    | [video](https://drive.google.com/file/d/1VV_s8c7b-ftCcg68q0oRRBh00T4JypPc/view?usp=sharing)    |                   |
| 4       | Evaluación: metricas de error y ranking               | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s4_c1-metricas.pdf)    | [video](https://drive.google.com/file/d/1wFQc9h1pdaJH1YbbUgbw8Wb56m1mHvZf/view?usp=sharing)    |   [slides P Castells LARS 2019](http://ir.ii.uam.es/castells/lars2019.pdf)                |
| 4       | Evaluación II: Cobertura, diversidad, novedad                        | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s4_c1-metricas.pdf)    | [video](https://drive.google.com/file/d/1TPjmn7FWK2C4G3rg7UYY4NGG2bLJyTOy/view?usp=sharing)     |                   |
| 5       | Evaluación III: Tests estadísticos                        | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s4_c1-tests_estadisticos.pdf)     | [video](https://drive.google.com/file/d/1jis_iIjFFWk7NcggeMn26rLAhrWuRK5h/view?usp=sharing)    |                   |
| 5       | Recomendación basada en contenido 1                   | x    | x    |                   |
| 5       | Recomendación basada en contenido 2                   | x    | x    |                   |
| 6       | Recomendación basada en contexto                      | x    | x    |                   |
| 6       | Recomendación híbrida y ensambles                     | x    | x    |                   |


**MES 1** En las primeras semanas nos enfocaremos en métodos básicos para hacer recomendación usando y prediciendo ratings (filtrado colaborativo User-based & item-based, slope-one). Luego veremos métodos de factorización matricial para ratings y para feedback implícito. En la 3ra semana veremos formas adicionales de evaluar más alla de la métricas de error de predicción de rating (MAE, MSE, RMSE) e incorporaremos métricas para evaluar listas de ítems (precision, recall, MAP, P@n, nDCG). Veremos métodos basados en contenido y sistemas híbridos.

**MES 2** Métodos basados en contexto, máquinas de factorización y modelos fundamentales de deep learning para recomendación. Recapitulación de las tareas de recomendacion (predecir rating, predecir una lista de items, recomendar una secuencia, recomendación TopN) y de su evaluacion considerando diversidad, novedad, coverage, y otras métricas.

**MES 3** User-centric RecSys, FAT (Fairness, Accountability and Transparency), Aplicaciones de Deep learning para problemas más específicos: recomendación de ropa, multimedia, etc. Modelos profundos generativos para recomendación. Revisaremos problemas de recomendación aún no resueltos en el área.

**MES 4** Principalmente presentaciones de alumnos.

### Código de Honor

Este curso adscribe el Código de Honor establecido por la Escuela de Ingeniería el que es vinculante. Todo trabajo evaluado en este curso debe ser propio. En caso de que exista colaboración permitida con otros estudiantes, el trabajo deberá referenciar y atribuir correctamente dicha contribución a quien corresponda. Como estudiante es su deber conocer la versión en línea del Código de Honor

### Evaluaciones

Detalles de las evaluaciones en [esta presentacion](https://docs.google.com/presentation/d/1DkBNxdazzUH_UCo2ufBnvwA4nNuhHLKkthd_MJfc1VM/edit?usp=sharing).

**Tarea 1**

Al final de las primeras 4 semanas, las(los) estudiantes implementarán mecanismos de recomendación para predecir ratings y para rankear items en un dataset que se entregará durante clases. Usarán la biblioteca pyreclab para los métodos básicos, pero si quieren optar a la nota máxima debe hacer un sistema híbrido o contextual que utilice información de contenido, como texto o imágenes. Para tener una idea de qué se trata la tarea, pueden revisar el [enunciado de la tarea del año 2019](https://github.com/PUC-RecSys-Class/RecSysPUC-2019/blob/master/tarea/Tarea_1_RecSys_2019_2.pdf)

**Lecturas: Blog y Presentación**

Fecha de revisión de blogs: El post de la semana x, tiene fecha de entrega el lunes a las 12pm de la semana x+1. Ejemplo: Las lecturas de la semana 1 (del 10 al 14 de agosto) se entregan a más tardar el lunes 17 de agosto de 2020 a las 8pm.

Cada alumno tendrá un repositorio en github (debe indicarlo en [este formulario](https://docs.google.com/forms/d/e/1FAIpQLSe06lSVzL7cUdFrTfmwDHdW6CFAVKQEnIs5CocOyiNpFmD4PA/viewform)) donde escribirá en markdown sus comentarios respecto de los papers indicados como obligatorios. No es necesario hacer un resumen largo del paper, sino indicar un resumen corto, puntos que pueden abrir discusión, mejoras o controversias: Evaluación inadecuada, parámetros importantes no considerados, potenciales mejoras de los algoritmos, fuentes de datos que podían mejorar los resultados, etc.

Adicionalmente, cada alumno presentará al menos una vez durante el semestre un paper sobre un tópico, con el objetivo de abrir una discusión sobre el tema durante la clase.

**Proyecto Final** 

Durante septiembre, las(los) estudiantes enviarán una idea de proyecto final, la cual desarrollarán durante octubre y noviembre. Enviarán un informe de avance a fines de octubre, para hacer una presentación de su proyecto al final del curso en una sesión de posters.

## Planificación general (sujeta a actualización)

![Planificacion RecSys 2020](https://user-images.githubusercontent.com/208111/90056740-5e6ee400-dcad-11ea-8d6e-5b83663c20f2.png)


## Lecturas por Semana

### Semana 1:  

**Obligatorias**  
 * Sarwar, B., Karypis, G., Konstan, J., & Riedl, J. (2001). Item-based collaborative filtering recommendation algorithms. In Proceedings of the 10th international conference on World Wide Web (pp. 285-295).

 * [Post original FunkSVD](https://sifter.org/~simon/journal/20061211.html)  

**Sugeridas**

* Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In The adaptive web (pp. 291-324). Springer Berlin Heidelberg.  
* Lemire, D., & Maclachlan, A. (2005). Slope One Predictors for Online Rating-Based Collaborative Filtering. In SDM (Vol. 5, pp. 1-5).

### Semana 2:

**Obligatorias**  
* Hu, Y., Koren, Y., & Volinsky, C. (2008). Collaborative filtering for implicit feedback datasets. In Data Mining, 2008. ICDM’08. Eighth IEEE International Conference on (pp. 263-272). IEEE.  
* Rendle, S., Freudenthaler, C., Gantner, Z., & Schmidt-Thieme, L. (2009). BPR: Bayesian personalized ranking from implicit feedback. In Proceedings of the Twenty-Fifth Conference on Uncertainty in Artificial Intelligence (pp. 452-461). AUAI Press.

**Sugeridas**  
* Jannach, D., Lerche, L., & Zanker, M. (2018). Recommending based on implicit feedback. In Social Information Access (pp. 510-569). Springer, Cham.
* Takács, G., Pilászy, I., Németh, B., & Tikk, D. (2009). Scalable collaborative filtering approaches for large recommender systems. Journal of machine learning research, 10(Mar), 623-656.  
* Pan, R., Zhou, Y., Cao, B., Liu, N. N., Lukose, R., Scholz, M., & Yang, Q. (2008). One-class collaborative filtering. In 2008 Eighth IEEE International Conference on Data Mining (pp. 502-511). IEEE. En este artículo aparecen la derivación y reglas de actualización de los parámetros así como las nociones de AMAN y AMAU.
* Srebro, N., & Jaakkola, T. (2003). Weighted low-rank approximations. In Proceedings of the 20th International Conference on Machine Learning (ICML-03) (pp. 720-727). Artículo citado por Pan et al. (2008) indicando detalles de la versión no regularizada que inspira OCCF.
* El siguiente paper es opcional, pero permite entender cómo se deriva <a href="https://www.codecogs.com/eqnedit.php?latex=y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" title="y_i=(X^TC^iX+ \lambda I)^{-1} X^TC^ip(i)" /></a> e <a href="https://www.codecogs.com/eqnedit.php?latex=x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^1&space;Y^TC^up(u)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^{-1}&space;Y^TC^up(u)" title="x_u=(Y^TC^uY+ \lambda I)^1 Y^TC^up(u)" /></a> del paper de Hu et al.: Takács, G., Pilászy, I., & Tikk, D. (2011). Applications of the conjugate gradient method for implicit feedback collaborative filtering. In Proceedings of the fifth ACM conference on Recommender systems (pp. 297-300). ACM.

### Semana 3:

**Obligatorias**  
* Cremonesi, P., Koren, Y., & Turrin, R. (2010). Performance of recommender algorithms on top-n recommendation tasks. In Proceedings of the fourth ACM conference on Recommender systems (pp. 39-46). ACM.  
* Guy, S., & Gunawardana, A.. (2011) “Evaluating recommendation systems.” In Recommender systems handbook, pp. 257-297. Springer US, 2011.  

**Sugeridas**  
* Herlocker, J. L., Konstan, J. A., Terveen, L. G., & Riedl, J. T. (2004). Evaluating collaborative filtering recommender systems. ACM Transactions on Information Systems (TOIS), 22(1), 5-53.  

### Semana 4:

**Obligatorias**  
* Pazzani, M. J., & Billsus, D. (2007). Content-based recommendation systems. In The adaptive web (pp. 325-341). Springer Berlin Heidelberg. Xu, W., Liu, X., & Gong, Y. (2003).
* Document clustering based on non-negative matrix factorization. In Proceedings of the 26th annual international ACM SIGIR conference on Research and development in informaion retrieval (pp. 267-273). ACM.

**Sugeridas**  
* Messina, P., Dominguez, V., Parra, D., Trattner, C., & Soto, A. (2019). Content-based artwork recommendation: integrating painting metadata with neural and manually-engineered visual features. User Modeling and User-Adapted Interaction, 29(2), 251-290.


### Semana 5:

**Obligatorias**  
* Adomavicius, G., Mobasher, B., Ricci, F. and Tuzhilin, A. (2011). Context-Aware Recommender Systems. AI Magazine, 32(3), 67-80. 
* Jahrer, M., Töscher, A. and Legenstein, R. (2010). Combining predictions for accurate recommender systems. In Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 693-702. ACM.

**Sugeridas**  
* Pigi K., Shobeir F., James F., Magdalini E. and Lise G. (2015). HyPER: A Flexible and Extensible Probabilistic Framework for Hybrid Recommender Systems. In Proceedings of the 9th ACM Conference on Recommender Systems (RecSys '15), 99–106. ACM. 

### Semanas 6 y 7:

Libre de lecturas (fiestas patrias)

### Semana 8 (29 sept a 2 de octubre):

* User Centric Recommender Systems (por definir)
