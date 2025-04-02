# ADS-fuzzylogic

# Gestión de Tráfico en Sistemas de Conducción Autónoma mediante Lógica Difusa

Este proyecto simula un sistema de toma de decisiones para vehículos autónomos utilizando lógica difusa. Se enfoca particularmente en la gestión del tráfico y la reacción ante vehículos tripulados en escenarios compartidos. En concreto, se centra en la maniobra de incorporación a una vía principal.

## Autor
Miguel Bande Rodríguez

## Descripción del Proyecto

El sistema utiliza variables difusas como la **velocidad relativa** y la **distancia de seguridad** para determinar una **acción óptima**: acelerar, mantener la velocidad o frenar. Las decisiones se basan en un conjunto de reglas difusas diseñadas para representar escenarios de tráfico comunes.

### Variables Difusas

- **Velocidad relativa**: negativa, cero, positiva.
- **Distancia de seguridad**: muy corta, corta, media, larga, muy larga.
- **Acciones resultantes**: frenar, mantener, acelerar.

### Reglas Difusas

Se definieron múltiples reglas que combinan las entradas para decidir la acción del sistema de conducción autónoma.

## Dependencias

Asegúrate de tener instaladas las siguientes librerías:

```bash
pip install scikit-fuzzy matplotlib imageio pandas
