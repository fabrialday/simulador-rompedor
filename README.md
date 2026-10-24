# Simulador Pica Roca (Rockbreaker) — Entrenamiento y Evaluación

Simulador 3D (Three.js) para capacitar operarios del rompedor hidráulico (brazo tipo Davon R6136, mando radio Tecman) en una estación de chancado primario.

## Jugar / usar

Abrir `index.html` directamente en el navegador, o visitar la versión publicada vía GitHub Pages:

👉 **https://fabrialday.github.io/simulador-rompedor/**

## Características

- Cinemática directa del brazo de 4 ejes (phi / t2 / t3 / t4) con retardo hidráulico simulado.
- Modo **Entrenamiento** (libre) y modo **Evaluación** (secuencia de rocas determinística, con puntaje).
- Secuencia de introducción: camión llega en reversa cargado de roca, vuelca y se retira; el mando se habilita recién al terminar.
- HUD de "sala de control" con cámaras en miniatura en tiempo real (render multi-cámara sobre el mismo canvas); clic en una miniatura hace un cambio de cámara instantáneo (no transición suave) e intercambia esa vista con la que estaba en pantalla principal.

## Estado

Prototipo funcional, pendiente de:
- Calibración con datos reales del fabricante (CFG del brazo).
- Calibración de joystick/HID real.
- Validación del sistema de puntaje con operadores reales.
- Registro de sesiones/resultados para evaluación formal.
