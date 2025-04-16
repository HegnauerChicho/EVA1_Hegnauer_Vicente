# EVA1_Hegnauer_Vicente

**Evaluación 1**
**Integrante:** Vicente Hegnauer Riquelme
**Fecha:** 15 de abril de 2025  

## Descripción del proyecto
Este proyecto implementa una solución para la gestión de inventario, ventas y actualización OTA de vehículos Jaguar en regiones de Chile, utilizando diagramas de flujo y algoritmos simples en PSeInt.

## Dependencias
- PSeInt (versión actual)
- Computador con Windows/macOS/Linux

## Instrucciones de ejecución
1. Abrir PSeInt.
2. Ir a "Archivo > Abrir" y seleccionar el archivo ".psc" correspondiente.
3. Ejecutar cada archivo para ver los resultados.

## Estructura del proyecto
- "registro_vehiculo.psc": Registro de nuevo vehículo
- "venta_vehiculo.psc": Proceso de venta
- "diagrama_ota.psc": Diagrama de OTA
- "calcular_precio_final.psc": Cálculo de precio final
- "inventario_vehiculos.psc": Búsqueda por modelo

## Funcionalidad adicional
- En el proceso de venta dentro del algoritmo fue incorporado un modelo "Si-Entonces" que detecta que modelo de auto se ha seleccionado para así poder dar más detalles en el proceso de venta

## Excepciones creadas
Durante el desarrollo del proyecto se consideraron validaciones simples para evitar errores comunes, tales como:
- En el proceso de venta y en la busqueda de modelo se debe ingresar correctamente el nombre del modelo a buscar, de lo contrario le solicitará que digite de correcta manera el nombre.
- En el texto final del diagrama de ota se agregó un ejemplo de mensaje que dice en qué versión está.
- Se agregó un inventario con datos de prueba para poder así implementar de buena manera el algoritmo.

## Información adicional
Se usó ChatGPT como apoyo en corrección del README

