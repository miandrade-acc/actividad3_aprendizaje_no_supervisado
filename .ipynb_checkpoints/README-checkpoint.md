Clasificación Supervisada - Human Activity Recognition

Este proyecto aplica modelos de clasificación supervisada para identificar actividades humanas a partir de datos recolectados por sensores en smartphones. Forma parte de la actividad académica de la Semana 2 del curso Aprendizaje Automático.

🔍 Objetivos

- Implementar modelos de clasificación supervisada (SVM, Árbol de Decisión, Regresión Logística).

- Evaluar el rendimiento de los modelos mediante F1-score, matriz de confusión y reporte de clasificación.

- Comparar gráficamente el desempeño de los clasificadores.

📊 Dataset

- Nombre: Human Activity Recognition Using Smartphones Dataset

- Fuente: UCI Machine Learning Repository

- Muestras de entrenamiento: 7352

- Variables predictoras: 561

- Variable objetivo: Actividad física (6 clases: caminar, estar de pie, etc.)

📌 Dominio del Dataset

El dataset utilizado corresponde al proyecto Human Activity Recognition Using Smartphones de la Universidad de Génova. Los datos fueron recolectados de acelerómetros y giroscopios integrados en smartphones Samsung Galaxy S II, usados por 30 sujetos mientras realizaban seis actividades físicas distintas: caminar, subir escaleras, bajar escaleras, sentarse, estar de pie y acostarse. Las señales fueron preprocesadas y convertidas en 561 características que describen estadísticas del movimiento.

⚖️ Modelos Entrenados

Modelo	F1-score (Macro)

Regresión Logística	0.9812
SVM (RBF)	0.9798
Árbol de Decisión	0.9399

Los tres modelos presentaron resultados sobresalientes. La regresión logística se posicionó ligeramente por encima, aunque SVM fue también altamente efectivo.

📈 Resultados Visuales

Las matrices de confusión y el gráfico comparativo están disponibles en la carpeta results/:

matriz_confusion_arbol.png

matriz_confusion_svm.png

matriz_confusion_logistica.png

comparacion_modelos_f1score.png

📂 Estructura del Proyecto

actividad1_semana2/
├── data/        # Dataset original
├── notebooks/   # Notebooks de desarrollo
├── results/     # Salidas y gráficos generados
├── docs/        # Documentos complementarios
├── src/         # Código adicional (si aplica)
└── README.md    # Descripción del proyecto

📌 Conclusiones

- Se cumplió exitosamente con el desarrollo de modelos supervisados en un contexto real.

- El preprocesamiento, especialmente el escalado de variables, fue esencial para los buenos resultados.

- La evaluación gráfica y cuantitativa permitió comparar de manera clara el rendimiento de cada modelo.

Autores:

- MARÍA AUGUSTA FLORES
- MARCELO ISMAEL ANDRADE
- JORGE ANDRÉS ORELLANA
- GALO VLADIMIR GONZÁLEZ

Curso: Aprendizaje Automático - UEES
Fecha: Abril 2025



