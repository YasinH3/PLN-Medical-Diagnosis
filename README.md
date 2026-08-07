# PLN - Medical Diagnosis

Este repositorio contiene un proyecto de Procesamiento de Lenguaje Natural para clasificar la estadificación del cáncer a partir de textos de diagnósticos médicos. La idea principal es entrenar y evaluar modelos de clasificación supervisada que aprendan a asociar un diagnóstico con una etiqueta de clase, utilizando técnicas modernas de NLP basadas en transformers.

## Objetivo del proyecto

Desarrollar un pipeline completo de análisis y modelado que permita:

- explorar y limpiar datos textuales médicos,
- preparar datasets para entrenamiento,
- entrenar modelos de clasificación,
- evaluar métricas de rendimiento,
- generar predicciones sobre nuevos textos.

## Contenido del repositorio

- [AnálisisCorpus.ipynb](AnálisisCorpus.ipynb): análisis exploratorio del corpus y estudio de los datos.
- [Propuesta1.ipynb](Propuesta1.ipynb): primera propuesta experimental.
- [Propuesta2.ipynb](Propuesta2.ipynb): segunda propuesta y evolución del enfoque.
- [Propuesta3.ipynb](Propuesta3.ipynb): tercera propuesta con ajustes de diseño.
- [Propuesta4.ipynb](Propuesta4.ipynb): experimento más refinado.
- [Propuesta5.ipynb](Propuesta5.ipynb): implementación de la propuesta final de modelado.
- [Propuesta5_Final_Predicciones.ipynb](Propuesta5_Final_Predicciones.ipynb): notebook final para inferencia y generación de predicciones.
- [Memoria_PLN_PO.pdf](Memoria_PLN_PO.pdf): memoria del proyecto con explicaciones técnicas y justificación metodológica.

## Tecnologías utilizadas

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Hugging Face Transformers
- Datasets
- PyTorch

## Requisitos

Se recomienda usar un entorno con Python 3.10 o superior y las siguientes dependencias:

```bash
pip install pandas numpy matplotlib scikit-learn datasets transformers torch jupyter
```

## Uso

1. Abrir cualquiera de los notebooks con Jupyter o VS Code.
2. Ejecutar las celdas en orden.
3. Asegurarse de tener los archivos CSV necesarios en la misma carpeta del proyecto, según lo requerido por los notebooks.
4. Revisar las predicciones generadas en el notebook final.

## Nota

Los notebooks están escritos en español y están orientados a un flujo académico y de experimentación para clasificación de textos médicos.
