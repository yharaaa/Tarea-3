# Tarea 3 - Análisis de Redes: Congresistas del Perú (semana de representación)

Este repositorio contiene un análisis de redes sobre el Congreso del Perú, centrado en dos bancadas principales: Fuerza Popular (FP) y Perú Libre (PL). Utilizando métricas de centralidad y conectividad, hemos aplicado conceptos de teoría de grafos para comprender mejor las relaciones y la importancia de distintos nodos (congresistas) dentro de las redes de cada bancada. Todo basado en los lugares visitados según los informes de la semana de representación presentados en la página web del Congreso de la República del Perú durante periodo 2023 - 2024.

## Descripción del Análisis

El análisis se ha dividido en los siguientes apartados:

1. **Centralidad de Cercanía**: Se analizó qué nodos (congresistas) están más próximos a otros dentro de las redes de cada bancada. Esto permite identificar cuáles nodos tienen acceso más rápido a la información dentro de la red.

2. **Centralidad de Intermediación**: Mide qué nodos actúan como intermediarios dentro de la red, ayudando a conectar a otros nodos que, de otro modo, estarían desconectados.

3. **Conectividad de la Red**: Se evaluó si las redes de Fuerza Popular y Perú Libre son fuertemente conexas, lo que implica si hay un camino dirigido entre cada par de nodos.

## Resultados Principales

### Fuerza Popular (FP)
- **Top 5 nodos por Centralidad de Cercanía**: 
  - Nodos más cercanos en términos de proximidad a otros congresistas dentro de la red.
- **Top 5 nodos por Centralidad de Intermediación**:
  - Nodos que actúan como puntos clave de conexión dentro de la bancada.
- **Conectividad**: Se determinó si la red de Fuerza Popular es fuertemente conexa.

### Perú Libre (PL)
- **Top 5 nodos por Centralidad de Cercanía**:
  - Nodos que tienen acceso rápido a otros dentro de la bancada de Perú Libre.
- **Top 5 nodos por Centralidad de Intermediación**:
  - Congresistas que conectan a otros nodos crucialmente en la bancada de Perú Libre.
- **Conectividad**: Se analizó la conectividad de la bancada de Perú Libre.

## Fuentes de Datos

Los datos fueron obtenidos a partir de información pública del Congreso del Perú y de la organización Transparencia Perú. En el presente trabajo se utilizó la base de datos de Transparencia Perú, que incluye los nombres de todos los congresistas de la República correspondiente al año congresal 2023-2024, así como los lugares visitados según los informes de la semana de representación presentados en la página web del Congreso de la República del Perú durante dicho periodo. Es importante señalar que la base de datos presenta vacíos, por lo que se trabajó con un total de 94 congresistas de los 130.

## Diccionario de Datos

- **Congresistas**: Cada nodo en la red representa a un congresista.
- **Centralidad de Cercanía**: Mide cuán cerca está un nodo de todos los demás nodos en la red.
- **Centralidad de Intermediación**: Mide el número de veces que un nodo actúa como puente en la red.
- **Conectividad**: Determina si todos los nodos en la red están interconectados.

## Gráfico de Redes

*Congreso del Perú*
![image](https://github.com/user-attachments/assets/5d62f93a-f5de-4874-8b63-11d80ea492bd)

*Bancada Fuerza Popular*

![image](https://github.com/user-attachments/assets/74f6c55c-3520-40f2-93af-6f3a43ce4321)

*Bancada Perú Libre*

![image](https://github.com/user-attachments/assets/b6f013f3-0a09-49e1-a839-8fc00b3a25e8)


# Link
https://yharaaa.github.io/Tarea-3/
