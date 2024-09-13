# Detección PPM

## Resumen

Este documento aborda los métodos teóricos de detección de señales PPM (Pulse Position Modulation), centrándose en la **decisión blanda** y **decisión dura**, además de la deducción de la **probabilidad de error de símbolo** (SER) y la **probabilidad de error de bit** (BER) para cada caso.

### Métodos de Detección:

1. **Soft Decision (Decisión Blanda)**: 
   - Utiliza el criterio de Máxima Verosimilitud (MAP) para minimizar la probabilidad de error de símbolo (SER).
   - Se describen los vectores recibidos y las pruebas de hipótesis para determinar el símbolo transmitido.
   - Se deriva la probabilidad de error de símbolo y se proporcionan dos formas para calcularla:
     - A partir de eventos que provocan error.
     - A partir de eventos que aseguran el éxito.

2. **Hard Decision (Decisión Dura)**: 
   - Consiste en comparar la amplitud de los slots con un umbral y asignar un 1 o 0 según el resultado.
   - Se describen las probabilidades de detección y falsas alarmas, así como la forma de optimizar el umbral para minimizar la SER.

### Probabilidad de Error:
- **SER (Symbol Error Rate)**: Se derivan fórmulas generales para cualquier número de slots (M) que permiten calcular el SER en diferentes condiciones.
- **BER (Bit Error Rate)**: Se deduce a partir de la SER considerando el número de errores de símbolo que pueden causar un error de bit.

### Fórmulas clave:
- Se incluyen expresiones y aproximaciones para la función Q, utilizada en la evaluación de las probabilidades involucradas en el proceso de detección.

### Umbral Óptimo:
- Se proporciona una aproximación analítica para calcular el umbral que minimiza el SER, derivada a partir de simulaciones.
