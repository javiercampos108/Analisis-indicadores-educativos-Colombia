# Resultados de limpieza y validación de datos

## Resumen del procesamiento

El dataset original contenía 15.707 registros y 41 columnas. Después del proceso de limpieza y preparación mediante Python, se obtuvo un conjunto de datos de 15.704 registros.

## Resultados

| Indicador | Resultado |
|---|---:|
| Registros originales | 15.707 |
| Registros finales | 15.704 |
| Columnas | 41 |
| Filas sin indicadores válidos | 29 |
| Valores vacíos finales | 21.124 |
| Duplicados por año y municipio | 0 |

## Controles de calidad

- Municipios que no coinciden con su departamento: 0.
- Valores con punto fuera de 2021: 0.
- Valores perdidos al convertir indicadores: 0.
- Duplicados por año y municipio: 0.
- Municipios con más de un nombre: 0.
- ETC con más de un nombre: 0.

## Correcciones realizadas

Se identificaron y corrigieron inconsistencias en los datos de población de 2021 para San Onofre, Capitanejo y Filadelfia.

## Tratamiento de valores faltantes

Se conservaron los valores nulos para distinguir la ausencia de información de los valores numéricos iguales a cero.

## Herramientas utilizadas

- Python.
- Pandas.
- NumPy.
- Google Colab.

## Resultado

Dataset preparado y validado para su utilización en el desarrollo del dashboard de indicadores educativos en Power BI.
