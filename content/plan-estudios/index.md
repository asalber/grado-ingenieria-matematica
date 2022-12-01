---
title: Plan de Estudios
date: 2022-09-01
mermaid: true
---

{{< mermaid >}}
classDiagram
class PRIMERO
PRIMERO: Fundamentos de Matemáticas (3)
PRIMERO: Algebra (9)
PRIMERO: Análisis I (6)
PRIMERO: Matemática Discreta (6)
PRIMERO: Programación (6)
PRIMERO: Análisis II (6)
PRIMERO: Probabilidad y Estadística (6)
PRIMERO: Algoritmos y Estructuras de Datos (9)
PRIMERO: Claves de Historia Contemporanea (6)
PRIMERO: Proyecto I (3)

class SEGUNDO
SEGUNDO: Análisis III (6)
SEGUNDO: Ecuaciones Diferenciales y en Diferencias (6)
SEGUNDO: Bases de Datos (6)
SEGUNDO: Estadística Inferencial (6)
SEGUNDO: Fundamentos Económicos (6)
SEGUNDO: Métodos Numéricos I (6)
SEGUNDO: Ecuaciones en Derivadas Parciales (6)
SEGUNDO: Análisis de Datos (6)
SEGUNDO: Electrónica Digital y Arquitectura de Ordenadores (6)
SEGUNDO: Geometría Diferencial (3)
SEGUNDO: Proyecto II (3)

class TERCERO_1S
TERCERO_1S: Métodos Numéricos II (6) 
TERCERO_1S: Optimización (6)
TERCERO_1S: Sistemas Operativos y Redes de Ordenadores (6)
TERCERO_1S: Hombre y Mundo Moderno (6)
TERCERO_1S: Optativas (6)

class TERCERO_2S_IA
TERCERO_2S_IA: Aprendizaje Automático (6)
TERCERO_2S_IA: Computación en Paralelo (6)
TERCERO_2S_IA: Lógica Formal (6)
TERCERO_2S_IA: Teoría de la Computación (6)
TERCERO_2S_IA: Fundamentos de la Inteligencia Artificial (6)

class TERCERO_2S_ACF
TERCERO_2S_ACF: Aprendizaje Automático (6)
TERCERO_2S_ACF: Computación en Paralelo (6)
TERCERO_2S_ACF: Cálculo Estocástico (6)
TERCERO_2S_ACF: Matemática Financiera I (6)
TERCERO_2S_ACF: Matemáticas Actuariales (6)

class CUARTO_IA
CUARTO_IA: Programación Lógica (6)
CUARTO_IA: Programación Funcional (6)
CUARTO_IA: Percepción Computacional (6)
CUARTO_IA: Procesamiento del Lenguaje Natural (6)
CUARTO_IA: Administración de Sistemas (6)
CUARTO_IA: Doctrina Social de la Iglesia (6)
CUARTO_IA: Optativa (3)
CUARTO_IA: Prácticas Externas (12)
CUARTO_IA: Trabajo Fin de Grado (9)

class CUARTO_ACF
CUARTO_ACF: Matemática Financiera II (6)
CUARTO_ACF: Minería de Datos y Big Data (6)
CUARTO_ACF: Modelos de Riesgo Cuantitativo (6)
CUARTO_ACF: Teoría y Optimización de Carteras (6)
CUARTO_ACF: Series Temporales (6)
CUARTO_ACF: Doctrina Social de la Iglesia (6)
CUARTO_ACF: Optativa (3)
CUARTO_ACF: Prácticas Externas (12)
CUARTO_ACF: Trabajo Fin de Grado (9)

PRIMERO --|> SEGUNDO
SEGUNDO --|> TERCERO_1S
TERCERO_1S --|> TERCERO_2S_IA
TERCERO_1S --|> TERCERO_2S_ACF
TERCERO_2S_IA --|> CUARTO_IA
TERCERO_2S_ACF --|> CUARTO_ACF
{{< /mermaid >}}

