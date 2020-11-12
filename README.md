# IIC3633 Sistemas Recomendadores
Agosto-Diciembre 2020


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
| 4       | Evaluación III: Tests estadísticos                        | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s4_c2-tests_estadisticos.pdf)     | [video](https://drive.google.com/file/d/1jis_iIjFFWk7NcggeMn26rLAhrWuRK5h/view?usp=sharing)    |                   |
| 5       | Recomendación basada en contenido 1                   | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s5_c1-content.pdf)    | [video](https://drive.google.com/file/d/1HiBLWh0l-aRq4ldVjk3Z0bf56gwQP2wp/view?usp=sharing)    |                   |
| 5       | Recomendación basada en contenido 2                   | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s5_c2-content.pdf)    | [video](https://drive.google.com/file/d/1cUR-bApLvOlVYRMAdGzEqeatP44jol0N/view?usp=sharing)    |                   |
| 6       | Recomendación híbrida                                 | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s6_c1-hibridos.pdf)    | [video](https://drive.google.com/file/d/1aUNYNli4l4xk_hGRB7v-PaRr0xtJWQau/view?usp=sharing)    |                   |
| 6       | Recomendación por ensambles                           | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s6_c2_p3-blending_ensemble.pdf)    | [video](https://drive.google.com/file/d/1o5cL5JspHI8QizFeMT8_9HQKqNT2rmqm/view?usp=sharing)    |                   |
| 6       | Recomendación basada en contexto                      | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s6_c1-contexto.pdf)    | [video1](https://drive.google.com/file/d/1fC3Ypg5aF8Be_8b7ZpPFqwVdtJS2kwzm/view?usp=sharing) [video2](https://drive.google.com/file/d/10r_6DzrKflF8sVzgZ1mU8xb8mJC2BcgO/view?usp=sharing)   |                   |
| 6       | Máquinas de Factorización                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s6_c2_p2-FMachines.pdf)    | [video](https://drive.google.com/file/d/111IK4ZIE-bqiNWmYLyafQoS0kthETLUr/view?usp=sharing)    |                   |
| 7       | Semana Break                             | Break    | Break    |                   |
| 8       | [Ideas de Proyecto](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/tree/master/proyecto) |  [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/Denis-IdeasProyectosFinales-2020.pdf)        |   [video1](https://drive.google.com/file/d/1o8TFNtax9cYiIrVFdnxGxJ3P3fItIFwA/view?usp=sharing) [video2](https://drive.google.com/file/d/1NjC6iw9LRDmaKGh-rSAHVm_iolcsvMy1/view?usp=sharing)      |                   |
| 9       | Evaluación centrada en usuarios                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s9_c1_usercentric.pdf)    | [video1](https://drive.google.com/file/d/1N6KBXkGN6Gh409mxkkD8KFGLs8Bvntz7/view?usp=sharing)  [video2](https://drive.google.com/file/d/1NlALFJzBcLv1SZGFSiOgjFoINlKzkdN4/view?usp=sharing)  |                   |
| 9       | Sistemas Justos, Explicables y Transparentes                                      |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s9_c2_FATv2.pdf)       |  [video](https://drive.google.com/file/d/1kgJHc3DoKem0VW1gKvm2RaweGJJF3uPv/view?usp=sharing)        |                   |
| 10       | Aprendizaje Activo (Active Learning)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s10_c1_activelearning.pdf)       |  [video](https://drive.google.com/file/d/1tb1qhBWUgO5jHrpQIYhWhvmy3z93Jimc/view?usp=sharing)        |                   |
| 10       | Bandits: Invitada [PhD(c) Andrea Barraza](https://apbarraza.com/)                                      |   [slides](https://gitlab.insight-centre.org/andbar/bears/raw/c4f04b377f6ad30a1ab0e5f1c97d05eaacec364e/tutorials/RECSYS2020/slides/%5BRecSys2020%5D%20Introduction%20to%20Bandits%20in%20Recommender%20Systems.pdf)       |  [video1](https://drive.google.com/file/d/1tTnkIjVOUu8Y_PkNYKZVBuWWscwn2Zni/view?usp=sharing)  [video2](https://drive.google.com/file/d/1Q8dYPUQ-EPmg_JEYK86Jw7smtr0ZPrEc/view?usp=sharing)        |   Tutorial eng. RecSys 2020 [video](https://player.vimeo.com/video/460128124) [slides](https://gitlab.insight-centre.org/andbar/bears/raw/c4f04b377f6ad30a1ab0e5f1c97d05eaacec364e/tutorials/RECSYS2020/slides/%5BRecSys2020%5D%20Introduction%20to%20Bandits%20in%20Recommender%20Systems.pdf)                 |
| 11       | Aprendizaje Profundo para RecSys (Intro y FC)                                      |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s11_c1_deep_learning.pdf)       |  [video](https://drive.google.com/file/d/1-T_vxETMbzqk2FNJzUPGaPJtIpfe-R9g/view?usp=sharing)        |                   |
| 11       | Aprendizaje Profundo para RecSys (Secuencias)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s11_c2_secu_deep_learning.pdf)       |  [video](https://drive.google.com/file/d/1krx9jda3TC8xyIn0n5FGuR-xgp-zezev/view?usp=sharing)        |                   |
| 12       | Aprendizaje Profundo para RecSys (Imágenes, Transformer, Grafos)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s12_c1_deep_learning_s.pdf)       |  [video1](https://drive.google.com/file/d/11aUkSvabuHZMevDd4yP0dBTrc3_2eNtV/view?usp=sharing)  [video2](https://drive.google.com/file/d/1LJ6jI3gHPqS45Olv-Iu29W5DunO8ZbF6/view?usp=sharing)      |                   |
| 12       | 10 problemas en Sistemas de Recomendación                                     |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s12_c2_10bigproblems-recsys-small.pdf)       |  [video](https://drive.google.com/file/d/1DtyzGOfMZY8UE223SMM2ROczH_qHhkNc/view?usp=sharing)        |                   |

### Parte II del curso: seminario

A partir de noviembre el curso toma modalidad seminario, los alumnos hacen presentaciones de los [siguientes papers](pap)

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->

| Semana  | Tema             | link slide(s) | link video |
|:--------|:-----------------|:-------------:|:----------:|
| 13       | CTRec: A Long-Short Demands Evolution Model for Continuous-Time Recommendation         | [slides](https://drive.google.com/file/d/1Ys-8asyvEYR1Fr_lbY3D_pJkU88f1jHs/view?usp=sharing)    | [video](https://drive.google.com/file/d/12wMh58M3ogqaWdmfKJpXDsZRyTOba9r1/view?usp=sharing)    |                   |
| 13       | Collaborative Similarity Embedding for Recommender Systems         | [slides](https://drive.google.com/file/d/1QoreUxFm_Qu5hHvzywPsj02pslXvefkK/view?usp=sharing)    | [video](https://drive.google.com/file/d/15ewTouX8aLn2ib3LEt_2s226zd2VZyi0/view?usp=sharing)    |
| 13       | Personalized re-ranking for recommendation         | [slides](https://drive.google.com/file/d/1Xnt_NpqR_7CHIBvhkB-J5MFOpxwSiAwR/view?usp=sharing)    | [video](https://drive.google.com/file/d/155ljkGXASvx-AwWN7STHL4xjWoUEYOMP/view?usp=sharing)    |
| 13       | Recommending what video to watch next: a multitask ranking system         | [slides](https://drive.google.com/file/d/1qzi589_zrzgV0zKDY4d3MPCikjcHgf64/view?usp=sharing)    | [video](https://drive.google.com/file/d/1uZGioos0x9xHo01AW3jAlip8jVn9k2Hv/view?usp=sharing)    |
| 13       | Interactive Recommender System via Knowledge Graph-enhanced Reinforcement Learning         | [slides](https://drive.google.com/file/d/1IdR28OnjbzY2YVmlekyNQippslYJB4cZ/view?usp=sharing)    | [video](https://drive.google.com/file/d/1i_ASoIHXTn8LTK4z-xE5NQNSfDnNb-rw/view?usp=sharing)    |
| 13       | The Impact of More Transparent Interfaces on Behavior in Personalized Recommendation         | [slides](https://drive.google.com/file/d/14LUW4ZQE9kHaAilSzDMl96tCPHH5UcdE/view?usp=sharing)    | [video](https://drive.google.com/file/d/14LUW4ZQE9kHaAilSzDMl96tCPHH5UcdE/view?usp=sharing)    |
| 14       | Complete the Look: Scene-based Complementary Product Recommendation         | [slides](https://drive.google.com/file/d/1RaB0XwZwfIPtKSOPAIxPEMtOoLE8Ty3V/view?usp=sharing)    | [video](https://drive.google.com/file/d/1efJnREr6D1lr5fx4lm1CHRyIf9-fqJW4/view?usp=sharing)    |
| 14       | Dynamic Online Conversation Recommendation     | [slides](https://drive.google.com/file/d/1S4ITTihWbGj5mb-FvsIOWYFJIJt98doK/view?usp=sharing)    | [video](https://drive.google.com/file/d/1mz2_L3vBfx8asvRqmvCYnE4lSvInpa0F/view?usp=sharing)    |
| 14       | Temporal-Contextual Recommendation in Real-Time.         | [slides](https://drive.google.com/file/d/1AM9HgY75MptUkboOZNKktesPLP17Rjln/view?usp=sharing)    | [video](https://drive.google.com/file/d/18DkeuikFjL3Rp477T3J1LIEsNJPxoiOV/view?usp=sharing)    |
| 14       | What does BERT Know about Books, Movies and Music? Probing BERT for Conversational Recommendation         | [slides](https://drive.google.com/file/d/1TKKuA1_V9X2x_JaIHee-iUl2g1Q6IsbF/view?usp=sharing)    |   |
| 14       | Fairness-Aware Explainable Recommendation over Knowledge Graphs         | [slides](https://drive.google.com/file/d/169p_F5YWoIPrn9QyiuepyqhvNnP6ufOZ/view?usp=sharing)    | [video](https://drive.google.com/file/d/19U2Fpq3Pj7qKEuCr47HPkPGRTdwvBUk4/view?usp=sharing)    |
| 15       | Deep generative ranking for personalized recommendation         | [slides]()    | [video]()    |
| 15       | Revisiting Adversarially Learned Injection Attacks Against Recommender Systems       | [slides]()    | [video]()    |
| 15       | Neural Interactive Collaborative Filtering         | [slides]()    | [video]()    |
| 15       | Explanation Mining: Post Hoc Interpretability of Latent Factor Models for Recommendation Systems        | [slides]()    | [video]()    |
| 15       | Towards Conversational Recommendation over Multi-Type Dialogs         | [slides]()    | [video]()    |
| 15       | Self-Supervised Reinforcement Learning for Recommender Systems         | [slides]()    | [video]()    |
| 16       | Controlling Fairness and Bias in Dynamic Learning-to-Rank         | [slides]()    | [video]()    |
| 16       | Are we really making much progress? A worrying analysis of recent neural recommendation approaches         | [slides]()    | [video]()    |
| 16       | KRED: Knowledge-aware Document Representation for News Recommendations         | [slides]()    | [video]()    |
| 16       | Improving Relevance Prediction with Transfer Learning in Large-scale Retrieval Systems         | [slides]()    | [video]()    |
| 16       | BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer         | [slides]()    | [video]()    |



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

(actualizada el 8 de octubre de 2020)

![Planificacion RecSys 2020](https://user-images.githubusercontent.com/208111/95472551-92871e00-0959-11eb-8725-5fb2fe7842f9.png)



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
* Verstrepen, K., Bhaduriy, K., Cule, B., & Goethals, B. (2017). Collaborative filtering for binary, positiveonly data. ACM Sigkdd Explorations Newsletter, 19(1), 1-21.

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
* Celma, Ò., & Herrera, P. (2008). A new approach to evaluating novel recommendations. In Proceedings of the 2008 ACM conference on Recommender systems (pp. 179-186).
* Van den Oord, A., Dieleman, S., & Schrauwen, B. (2013). Deep content-based music recommendation. In Advances in neural information processing systems (pp. 2643-2651).


### Semana 5:

**Obligatorias (esta semana se puede elegir una de las dos para entregar*)**  
* Adomavicius, G., Mobasher, B., Ricci, F. and Tuzhilin, A. (2011). Context-Aware Recommender Systems. AI Magazine, 32(3), 67-80. 
* Jahrer, M., Töscher, A. and Legenstein, R. (2010). Combining predictions for accurate recommender systems. In Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 693-702. ACM.

**Sugeridas**  
* Pigi K., Shobeir F., James F., Magdalini E. and Lise G. (2015). HyPER: A Flexible and Extensible Probabilistic Framework for Hybrid Recommender Systems. In Proceedings of the 9th ACM Conference on Recommender Systems (RecSys '15), 99–106. ACM. 
* Rendle, S. (2010). Factorization machines. In 2010 IEEE International Conference on Data Mining (pp. 995-1000). IEEE.

*No olvidar declarar en la crítica el título elegido.

### Semanas 6 y 7:

Libre de lecturas (fiestas patrias)

### Semana 8 :

**Obligatorias con entrega lunes 5 de octubre**
* Pu, P., Chen, L. and Hu, R. (2011). A user-centric evaluation framework for recommender systems. RecSys'11 - Proceedings of the 5th ACM Conference on Recommender Systems. 157-164.
* Parra, D., Brusilovsky, P., and Trattner, C. (2014). See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation. International Conference on Intelligent User Interfaces, Proceedings IUI.

**Obligatoria con entrega miércoles 7 de octubre**
* Knijnenburg, B., Bostandjiev, S., O'Donovan, J., and Kobsa, A. (2012). Inspectability and control in social recommenders. RecSys'12 - Proceedings of the 6th ACM Conference on Recommender Systems. 

### Semana 9 :

**Obligatorias**
* Cañamares, R., Redondo, M., & Castells, P. (2019). Multi-armed recommender system bandit ensembles. In Proceedings of the 13th ACM Conference on Recommender Systems (pp. 432-436).
* Bendada, W., Salha, G., & Bontempelli, T. (2020). Carousel Personalization in Music Streaming Apps with Contextual Bandits. In Fourteenth ACM Conference on Recommender Systems (pp. 420-425).

**Sugeridas**
* Lacerda, A., Santos, R. L., Veloso, A., & Ziviani, N. (2015). Improving daily deals recommendation using explore-then-exploit strategies. Information Retrieval Journal, 18(2), 95-122.
* Guillou, F., Gaudel, R., & Preux, P. (2016). Scalable explore-exploit collaborative filtering. In Pacific Asia Conference On Information Systems (PACIS). Association For Information System.
* Teo, C. H., Nassif, H., Hill, D., Srinivasan, S., Goodman, M., Mohan, V., & Vishwanathan, S. V. N. (2016). Adaptive, personalized diversity for visual discovery. In Proceedings of the 10th ACM conference on recommender systems (pp. 35-38).

### Semana 10 :

**Obligatorias**
* Hasta la sección 3.4 (incluyendo 3.4): Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.

**Sugeridas**
* Covington, P., Adams, J., & Sargin, E. (2016). Deep neural networks for youtube recommendations. In Proceedings of the 10th ACM conference on recommender systems (pp. 191-198).
* Bansal, T., Belanger, D., & McCallum, A. (2016). Ask the gru: Multi-task learning for deep text recommendations. In Proceedings of the 10th ACM Conference on Recommender Systems (pp. 107-114).

### Semana 11 :

**Obligatorias**

* Desde la sección 3.5 en adelante: Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.

**Sugeridas**
* Chen, J., Zhang, H., He, X., Nie, L., Liu, W., & Chua, T. S. (2017). Attentive collaborative filtering: Multimedia recommendation with item-and component-level attention. In Proceedings of the 40th International ACM SIGIR conference on Research and Development in Information Retrieval (pp. 335-344).
* Liang, D., Krishnan, R. G., Hoffman, M. D., & Jebara, T. (2018). Variational autoencoders for collaborative filtering. In Proceedings of the 2018 World Wide Web Conference (pp. 689-698).
