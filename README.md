# **Clasificación de Imágenes Dermatológicas para Detección de Melanoma**

## **Descripción**

Proyecto de clasificación de imágenes dermatológicas enfocado en la detección de lesiones cutáneas malignas, como el melanoma, frente a lesiones benignas.

Este proyecto abarca la implementación y entrenamiento de un modelo de aprendizaje automático que sea capaz de detectar lesiones cutáneas en fotografías y de distinguir entre lesiones malignas (tales como melanoma) y benignas (tales como nevos melanocíticos); también se considera parte del proyecto el preprocesamiento de las imágenes y la evaluación de los resultados obtenidos.

## **Objetivos**

+ *Automatización:* Utilización un modelo de AA para reducir la subjetividad en el diagnóstico visual de lesiones.
+ *Optimización:*  Depuración del conjunto de datos para optimizar la extracción de descriptores morfológicos y características del tejido cutáneo.
+ *Validación:* Comprobar la eficacia del algoritmo mediante métricas de precisión y sensibilidad.

## **Instrucciones de uso**

1. Clonar el repositorio en tu equipo local:
```bash
git clone https://github.com/usuario/clasificacion-dermatologica.git
```

2. Acceder al directorio del proyecto:
```bash
cd clasificacion-dermatologica
```

3. Instalar las dependencias necesarias (si aplica):
```bash
pip install -r requirements.txt
```

4. Ejecutar el preprocesamiento de las imágenes:
```bash
python src/preprocessing.py
```

5. Entrenar el modelo de clasificación:
```bash
python src/train_model.py
```

6. Evaluar el modelo:
```bash
python src/evaluate_model.py
```

## **Información Adicional**

+ *Herramientas utilizadas:*
    * Python: Lenguaje principal del modelo.
    * Markdown: Documentación técnica del repositorio.
    * GitHub: Control del versiones.
 
+ *Datos utilizados:*
    * Imágenes dermatológicas de lesiones cutáneas (benignas y malignas).

+ *Estructura del proyecto*
```text
.
├── data/               
├── docs/              
│   └── references/      
├── models/            
├── results/            
├── src/                
├── .gitignore          
├── LICENSE             
└── README.md           
```

## Notas
Este repositorio se ha creado como parte del trabajo correspondiente a la asignatura de Introducción a la Programación Científica del Máster de Bioinformática de la UNIR.

## **Autores**

+ Sara Guillén, Pablo Carballo, Vicente Llorente, Yanis Cruz y Víctor Pérez.
+ 
