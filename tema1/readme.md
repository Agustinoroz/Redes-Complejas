# Conceptos básicos de redes complejas

Trabajo orientado al análisis exploratorio de redes reales utilizando herramientas básicas de teoría de redes. Se estudian propiedades estructurales, métricas globales y patrones de interacción en redes biológicas y sociales.

## Objetivos

Cargar y representar redes a partir de distintos formatos de datos.

Comparar propiedades topológicas entre diferentes redes reales.

Analizar homofilia en una red social mediante modelos nulos.

## Redes analizadas

Redes de interacción proteína–proteína de levadura:

Y2H (Yeast Two-Hybrid)

AP-MS (Affinity Purification–Mass Spectrometry)

LIT (Literature-curated)

Red social de delfines (Dolphins network).

## Metodología

Construcción de grafos a partir de archivos .txt y .gml.

Visualización de redes usando distintos layouts.

Cálculo de métricas globales:

Número de nodos y enlaces

Grado medio, máximo y mínimo

Densidad

Coeficiente de clustering

Transitividad

Diámetro de la componente gigante

Comparación estructural entre distintas redes biológicas.

Análisis de homofilia en la red de delfines:

Asignación de atributos de género a los nodos

Cálculo de enlaces homofílicos

Contraste con modelos nulos mediante:

Reasignación aleatoria de atributos

Recableado de la red manteniendo la distribución de grado

Estimación de p-valores e índice de homofilia.

## Resultados principales

Las redes PPI presentan diferencias estructurales claras según el método experimental.

La red AP-MS muestra mayor densidad y clustering.

En la red de delfines se observa homofilia significativa por género, confirmada mediante comparación con modelos nulos.

### Lenguajes y herramientas

Python

NetworkX

NumPy, Pandas

Matplotlib
