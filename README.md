# Análisis de Displays de Multímetros y el Caso del Greenlee DM-860A

## Introducción

En instrumentos de medición digitales como los multímetros, el número de dígitos en el display es una característica clave para determinar su resolución y capacidad de medición. En particular, expresiones como **"3.5 dígitos"**, **"3.75 dígitos"** o **"5.83 dígitos"** indican la cantidad de cifras que el instrumento puede mostrar y su nivel de detalle en las mediciones.

## Conceptos Fundamentales

- **Dígitos**: Indican la cantidad de posiciones numéricas que el display puede mostrar. Un dígito completo va de 0 a 9.
- **Medio dígito**: Representa un rango más limitado (por ejemplo, de 0 a 1 o de 0 a 3).
- **Resolución**: Es el cambio más pequeño que el instrumento puede detectar.
- **Precisión (accuracy)**: Qué tan cerca está la medición del valor real.

## Fuentes principales de estudio

- [Electrical Baba: ¿Qué significa un medidor de tres y medio dígito?](https://electricalbaba.com/what-three-half-digit-meter-display/)
- [Keysight: ¿Qué son dígitos, precisión y resolución en un DMM?](https://www.keysight.com/blogs/en/tech/bench/2019/01/02/what-are-digits-accuracy-and-resolution-with-a-dmm)

## Análisis del Multímetro Greenlee DM-860A

### Display de 5.83 dígitos

El Greenlee DM-860A posee un display de 5.83 dígitos, lo cual significa:

- 5 dígitos completos (0 a 9).
- 1 dígito adicional parcial que puede llegar hasta 3.
- Esto permite mostrar números desde 0 hasta aproximadamente **399999**.

### Rangos de medición esperados por el display

| **Tipo de medición** | **Rango esperado por el display** |
| :-------------------- | :------------------------------- |
| Voltaje DC | ±399.999 V |
| Corriente DC | ±39.9999 A |

### Información real según el datasheet

- **Voltaje máximo medible:** 1000V DC
- **Corriente máxima medida:** 10A DC (por 30 segundos máximo)

Rangos disponibles:
- Voltaje DC: 400mV, 4V, 40V, 400V, 1000V
- Corriente DC: 400µA, 4000µA, 40mA, 400mA, 4A, 10A

### Correlación entre display y especificaciones

El display de 5.83 dígitos ofrece una resolución alta que permite ver detalles finos en todas las escalas, especialmente en rangos bajos (por ejemplo, 400mV). Sin embargo, los límites de voltaje y corriente medibles están definidos por la protección y diseño interno del instrumento, no únicamente por la capacidad del display.

## Conclusiones

El número de dígitos en un multímetro digital influye directamente en su capacidad de resolución, pero no necesariamente en su precisión máxima. En el caso del Greenlee DM-860A, el display de 5.83 dígitos proporciona un nivel de detalle muy alto que se corresponde adecuadamente con los rangos de medición definidos en su datasheet.
