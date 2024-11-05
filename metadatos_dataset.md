
# Metadatos del Dataset de Fosfoproteómica

## Descripción General
Este documento describe los metadatos asociados al dataset de fosfoproteómica utilizado en 
el análisis.El dataset incluye información sobre las modificaciones post-traduccionales de 
secuencias peptídicas en diferentes grupos tumorales.

## Estructura del Dataset
El dataset consta de las siguientes columnas:

| Columna                   | Descripción                                               |
|---------------------------|-----------------------------------------------------------|
| `SequenceModifications`   | Tipo de modificaciones en la secuencia y ubicación.       |
| `Accession`               | Identificador de la secuencia.                            |
| `Description`             | Descripción de la secuencia analizada.                    |
| `Score`                   | Score que evalúa la confiabilidad de la identificación.   |
| `CLASS`                   | Clase de la muestra (H o C).                              |
| `PHOSPHO`                 | Aminoácido donde ocurre la fosforilación (Y, S/T).        |
| `Group`                   | Grupo tumoral (MSS o PD).                                 |


## Información sobre los Grupos
- **Grupo MSS**: Incluye las muestras M1, M5 y T49.
- **Grupo PD**: Incluye las muestras M42, M43 y M64.

## Consideraciones
- Las columnas `CLASS` y `PHOSPHO` son categóricas y pueden ser convertidas a factores para 
análisis estadísticos.

