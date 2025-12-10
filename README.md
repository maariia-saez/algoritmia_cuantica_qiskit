# Fundamentos de Computación y Algoritmia Cuántica

Implementación práctica en Python y Qiskit de los conceptos fundamentales de la computación cuántica. Este repositorio sirve como anexo técnico al proyecto académico "Fundamentos de Computación Cuántica: De la Teoría de Circuitos de Algoritmia de Shor".

## Autoras
* **Alicia Elvira Montes Núñez**
* **María Sáez Díaz**

## Descripción del Proyecto
Este código valida experimentalmente los pilares teóricos de la computación cuántica utilizando el simulador `Aer` de Qiskit.

1. **Estados de Bell:** Generación de superposición y entrelazamiento (Violación de desigualdades clásicas).
2. **Teleportación Cuántica:** Protocolo completo de transferencia de estados sin clonación.
3. **QFT (Quantum Fourier Transform):** Transformada de Fourier para 3 qubits, base de la aritmética cuántica.
4. **QPE (Quantum Phase Estimation):** Estimación de fase para la puerta T, núcleo del algoritmo de Shor.

## Requisitos
El código ha sido desarrollado en Python. Para ejecutarlo es necesario instalar las siguientes dependencias:
```bash
pip install qiskit qiskit-aer matplotlib pylatexenc
