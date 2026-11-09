# Actividad 3.4: Optimización en Grafos — Algoritmos de Caminos Más Cortos

**Universidad de Guadalajara — Centro Universitario de Tonalá**

Ingeniería en Ciencias Computacionales

Materia: Estructuras de Datos

Docente: Jose Navarros Rios

## Integrantes del equipo

- Gonzalez Nuñez Isai
- Zuñiga De Leon Bryan

## Descripción

Sistema de gestión de una red de transporte construido sobre un **Grafo Ponderado** en Java, con interfaz gráfica en Swing diseñada con el GUI Builder de NetBeans (arrastrar y soltar).

Sobre el proyecto de la Actividad 3.3 (gestión de vértices y aristas, BFS, DFS, matriz de adyacencia y conectividad) se integró un módulo de optimización de rutas que calcula el camino más corto entre un nodo origen y un nodo destino con dos algoritmos:

- **Dijkstra**: ruta más corta desde un origen con pesos no negativos.
- **Bellman-Ford**: ruta más corta con soporte para pesos negativos y detección de ciclos negativos.

La interfaz muestra en tiempo real la traza paso a paso de cada algoritmo (inicialización, aristas aceptadas, aristas descartadas y resultado final), resalta el camino óptimo en el dibujo del grafo y permite comparar el desempeño de ambos algoritmos sobre la misma red.

## Contenido del repositorio

- `Grafos_2.zip`: proyecto completo de NetBeans.

## Cómo ejecutarlo

1. Descomprimir `Grafos_2.zip`.
2. En NetBeans: **File → Open Project** y seleccionar la carpeta `Grafos_2`.
3. **Run → Run Project** (F6).
4. Pulsar **Cargar red de ejemplo**, escribir un origen y un destino (por ejemplo `GDL` y `CHA`) y pulsar **Calcular ruta óptima**.

Las pruebas automáticas están en `pruebas/PruebasCaminos.java` (clic derecho → **Run File**).

## Video demostrativo

[Ver video](https://youtu.be/Ig4Rse_s_y0)
