Introducción  

El cáncer de mama es una de las principales causas de muerte entre las mujeres en todo el mundo. La detección temprana de esta enfermedad es fundamental para mejorar las tasas de supervivencia y reducir su impacto. La mamografía, una técnica de imagenología médica que utiliza rayos X de baja dosis para examinar el tejido mamario, es una herramienta crucial en el diagnóstico precoz del cáncer de mama.

En este proyecto, nos proponemos desarrollar un sistema de detección de cáncer de mama basado en análisis de mamografías mediante técnicas de machine learning. Utilizaremos el conjunto de datos DDSM Mammography, que contiene una colección de imágenes de mamografías junto con sus respectivas etiquetas de diagnóstico.

Objetivos  

El objetivo principal de este proyecto es construir un modelo de machine learning capaz de identificar automáticamente la presencia de cáncer de mama en mamografías. Para lograr este objetivo, nos planteamos los siguientes pasos:

Exploración y Preparación del Dataset:  

Cargar y explorar el conjunto de datos DDSM Mammography para comprender su estructura y contenido.
Realizar preprocesamiento de imágenes, incluyendo la normalización y ajuste de tamaño si es necesario.  

Construcción y Entrenamiento del Modelo:  

Probar diferentes modelos de machine learning, tanto tradicionales como modernos, como SVM, Random Forest y Convolutional Neural Networks (CNNs).
Entrenar los modelos utilizando el conjunto de datos de entrenamiento, ajustando los hiperparámetros y aplicando técnicas de regularización.  

Evaluación del Modelo:  

Evaluar el rendimiento de los modelos utilizando métricas como precisión, recall, F1-score y AUC-ROC.
Validar los modelos mediante técnicas como la validación cruzada para garantizar su generalización.  

Implementación y Mejora Continua:  

Optimizar los modelos mediante la ajuste de hiperparámetros y técnicas de optimización.
Probar el modelo final en un conjunto de datos de prueba independiente para obtener una evaluación final de su rendimiento.  

REFERENCIAS:  
[1] The Digital Database for Screening Mammography, Michael Heath, Kevin Bowyer, Daniel Kopans, Richard Moore and W. Philip Kegelmeyer, in Proceedings of the Fifth International Workshop on Digital Mammography, M.J. Yaffe, ed., 212-218, Medical Physics Publishing, 2001. ISBN 1-930524-00-5.

[2] Current status of the Digital Database for Screening Mammography, Michael Heath, Kevin Bowyer, Daniel Kopans, W. Philip Kegelmeyer, Richard Moore, Kyong Chang, and S. Munish Kumaran, in Digital Mammography, 457-460, Kluwer Academic Publishers, 1998; Proceedings of the Fourth International Workshop on Digital Mammography.

[3] Rebecca Sawyer Lee, Francisco Gimenez, Assaf Hoogi , Daniel Rubin (2016). Curated Breast Imaging Subset of DDSM. The Cancer Imaging Archive.

[4] Clark K, Vendt B, Smith K, Freymann J, Kirby J, Koppel P, Moore S, Phillips S, Maffitt D, Pringle M, Tarbox L, Prior F. The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository, Journal of Digital Imaging, Volume 26, Number 6, December, 2013, pp 1045-1057.

[5] D. Levy, A. Jain, Breast Mass Classification from Mammograms using Deep Convolutional Neural Networks, arXiv:1612.00542v1, 2016
