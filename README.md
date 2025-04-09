# Intro-a-la-IA

Notas del curso **Introducción a la Inteligencia Artificial** 🤖  
Este repositorio contiene apuntes, ejercicios y recursos útiles recopilados durante el desarrollo del curso.

---

## 📚 Semana 1: Algoritmos de búsqueda


- **Búsqueda en profundidad (DFS)**  
  Explora tan profundo como sea posible por cada rama antes de retroceder.

- **Búsqueda en amplitud (BFS)**  
  Explora todos los nodos vecinos antes de profundizar.

- **Algoritmo Primero el Mejor (Best-First Search)**  
  Selecciona el siguiente nodo basado en una función heurística `h(n)` (estimación del costo restante al objetivo).

- **Algoritmo A***  
  Combina el costo acumulado `g(n)` con la heurística `h(n)` usando `f(n) = g(n) + h(n)` para encontrar rutas óptimas.

---

## 📚 Semana 2: Sistemas basados en reglas

### 1. **Lógica Proposicional**  
   - **Tablas de verdad**: Herramienta utilizada para evaluar las proposiciones lógicas y determinar su validez.
   - **Inferencias**: Técnicas para deducir nuevas proposiciones a partir de otras.
     - **Modus Ponens**: Si "P implica Q" (P → Q) y "P" es cierto, entonces "Q" también es cierto.
     - **Modus Tollens**: Si "P implica Q" (P → Q) y "Q" es falso (¬Q), entonces "P" también es falso (¬P).
   - **Lógica de Predicados**: Ampliación de la lógica proposicional que maneja variables y cuantificadores (como "para todo" y "existe").
   - **Inferencia en lógica de predicados**: Utilización de reglas y teoremas para deducir nuevas afirmaciones a partir de hechos y premisas.

### 2. **Sistemas Expertos**  
Un **sistema experto** es un programa diseñado para simular el razonamiento y la toma de decisiones de un experto humano en un área específica.

#### Componentes principales:
   - **Hechos**: Información relevante y conocida, utilizada como base para el razonamiento.
   - **Reglas**: Conjunto de instrucciones o condiciones que representan el conocimiento experto sobre el dominio y guían las decisiones.
   - **Razonamiento**: Proceso de deducción mediante inferencias a partir de hechos y reglas.

### 3. **Sistemas Expertos en Python**  
   - **Implementación**: Utilización de Python para desarrollar sistemas expertos, aprovechando su capacidad para manejar lógica y razonamiento.
   - **libreria**:  `experta`, para crear sistemas expertos basados en reglas.

