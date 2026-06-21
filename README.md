<div align="center">

# Desambiguación del Sentido de Palabras (WSD) con NLTK y Aprendizaje Automático Supervisado

![NLP](https://img.shields.io/badge/NLP-Word_Sense_Disambiguation-00897B?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3.x-FF6B35?style=for-the-badge)

> WSD con clasificadores supervisados: extracción de características léxicas, entrenamiento y evaluación sobre corpus anotado con NLTK.

## Descripción

</div>

---

Implementación de un sistema de **Word Sense Disambiguation (WSD)** usando clasificadores supervisados de aprendizaje automático en Python con NLTK. El sistema extrae características léxicas y contextuales del texto (palabras vecinas, POS tags, n-gramas), entrena clasificadores (Naive Bayes, Decision Tree, MaxEnt) y evalúa la precisión de desambiguación sobre corpus anotado semánticamente.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Laboratorio_Desambiguacion_Palabras.ipynb` | Notebook principal con todo el pipeline WSD |
| `*.pdf` | Informe de resultados y análisis |

## Pipeline de WSD implementado

```python
# 1. Extracción de características
features = extract_context_features(word, sentence, window=5)

# 2. Entrenamiento de clasificadores
classifier = nltk.NaiveBayesClassifier.train(training_set)

# 3. Evaluación
accuracy = nltk.classify.accuracy(classifier, test_set)
```

## Contexto académico

**Asignatura:** Minería de Información y Análisis — NLP · **Institución:** Ingeniería Informática
**Autor:** Alejandro De Mendoza — Ingeniero Informático · Especialista en IA

---

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
