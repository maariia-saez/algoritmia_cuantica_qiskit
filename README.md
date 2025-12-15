# Fundamentos de Computación y Algoritmia Cuántica

Implementación práctica en Python y Qiskit de los conceptos fundamentales de la computación cuántica. Este repositorio sirve como anexo técnico al proyecto académico **"Fundamentos de Computación Cuántica: De la Teoría de Circuitos al Algoritmo de Shor"**.

## Contenido

Este repositorio incluye:

- `proyecto_algoritmia_cuantica.ipynb`: Jupyter Notebook que reúne las implementaciones y experimentos numéricos.

El notebook valida experimentalmente varios pilares teóricos de la computación cuántica utilizando el simulador `Aer` de Qiskit:

1. **Estados de Bell**: Generación de superposición y entrelazamiento (violación de desigualdades clásicas).
2. **Teleportación cuántica**: Protocolo completo de transferencia de estados sin clonación.
3. **QFT (Quantum Fourier Transform)**: Transformada de Fourier para 3 qubits, base de la aritmética cuántica.
4. **QPE (Quantum Phase Estimation)**: Estimación de fase para la puerta T, núcleo del algoritmo de Shor.

## Requisitos

- Python 3.x
- Qiskit
- Qiskit Aer
- Matplotlib
- `pylatexenc` (si se generan expresiones en LaTeX en las figuras)

Instalación recomendada:

```bash
pip install qiskit qiskit-aer matplotlib pylatexenc
```

## Ejecución

1. Abrir el notebook (`proyecto_algoritmia_cuantica.ipynb`) con Jupyter.
2. Ejecutar las celdas en orden, desde la sección de importaciones hasta las últimas simulaciones.

## Autoras

- **Alicia Elvira Montes Núñez**
- **María Sáez Díaz**
