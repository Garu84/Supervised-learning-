# Supervised-learning
# Dataset Sintético - Deserción Estudiantil

Este dataset lo creé para la Actividad I de Data Mining de la Universidad de la Costa.

**Tamaño:** 500 estudiantes

## Variables incluidas
- **Demográficas:** age, gender, place_of_origin
- **Académicas:** high_school_avg, admission_test_score, first_semester_grades
- **Financieras:** socioeconomic_level, has_scholarship, has_loan
- **Variable objetivo:** dropout (Yes = desertó / No = no desertó)

## Cómo creé los datos
- Usé números aleatorios simples con `numpy.random`
- Agregué **valores nulos** (null values) en algunas columnas (aprox. 70 nulos en total)
- Agregué **outliers** manualmente (edades raras, notas imposibles, estrato 0, etc.)
- La columna "dropout" depende un poco de las notas del primer semestre (más probabilidades de desertar si la nota es baja)

Este dataset simula información real de estudiantes y cumple con todos los requisitos de la actividad.

**Creado por:** [Tu nombre aquí]  
**Fecha:** Marzo 2026
