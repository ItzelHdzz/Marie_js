# Análisis de Mediana en Sensores - Marie.js

## Descripción
Este programa en **Marie.js** procesa una serie de valores ingresados y los distribuye en dos sensores (Sensor A y Sensor B) para calcular sus medianas respectivas. La lógica sigue los siguientes pasos:

1. **Entrada de datos:** Se ingresa un número y se almacena en `x`. Dependiendo de su valor, se asigna a un sensor.
2. **Evaluación por sensores:**
   - Sensor A: Procesa valores entre `100(16)` y `200(16)`, registrando el mínimo y máximo.
   - Sensor B: Procesa valores entre `200(16)` y `300(16)`, registrando el mínimo y máximo.
3. **Cálculo de la mediana:**
   - Se incrementa el mínimo y se decrementa el máximo hasta que ambos sean iguales.
4. **Finalización:** Se comparan los contadores de ambos sensores y se imprimen las medianas.

## Estructura del Código
- `loop`: Bucle principal de entrada.
- `sensorA`, `sensorB`: Procesamiento de valores según el sensor asignado.
- `maximoA`, `maximoB`: Determinan los valores máximos.
- `medianA`, `medianB`: Calculan la mediana.
- `fin`: Verifica si ambos sensores han procesado la misma cantidad de datos.
- `out`: Imprime los resultados.

## Variables Clave
- `counterA`, `counterB`: Contadores de valores procesados por cada sensor.
- `xminA`, `xmaxA`, `xminB`, `xmaxB`: Mínimos y máximos de cada sensor.
- `Y`, `Z`: Direcciones de almacenamiento para cada sensor.
- `cien`, `doscien`, `trescien`: Constantes utilizadas en las comparaciones.

Este programa permite dividir y analizar datos en dos sensores, obteniendo un valor representativo de cada conjunto mediante la mediana. 🚀
