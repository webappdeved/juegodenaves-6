# Juego_de_naves

**Versión:** 1.0.0  
**Lenguaje:** C++  
**Materia:** Laboratorio de Programación  
**Curso:** 5to 3ra  
**Institución:** E.E.S.T. N.º 1 de Vicente López Docente y Estudiante?

---

## Descripción del proyecto

El Juego de Combate Espacial es un proyecto desarrollado en C++ que consiste en controlar una nave espacial para evitar y destruir asteroides que aparecen en la pantalla.
El jugador debe utilizar los controles del teclado para moverse y disparar, intentando conseguir la mayor cantidad de puntos posibles sin perder todas sus vidas.
El proyecto tiene como objetivo aplicar los conceptos de **Programación Orientada a Objetos (POO)**, utilizando clases, objetos, atributos privados, métodos públicos, constructores, vectores y punteros.

##  Características principales

- Control de una nave espacial.
- Movimiento en cuatro direcciones.
- Sistema de disparos.
- Generación de 5 asteroides en posiciones aleatorias.
- Detección de colisiones entre la nave y los asteroides.
- Detección de colisiones entre balas y asteroides.
- Sistema de 3 vidas iniciales.
- Sistema de puntaje que suma 10 puntos por cada asteroide destruido.
- Identificación del jugador mediante su nombre y apellido.
- Pantalla de finalización cuando se pierden todas las vidas.

##  Controles

  W : Mover hacia arriba 
  A : Mover hacia la izquierda 
  S : Mover hacia abajo 
  D : Mover hacia la derecha 
  ESPACIO : Disparar 

## Tecnologías utilizadas

- **C++:** lenguaje utilizado para desarrollar el juego.
- **iostream:** entrada y salida de datos.
- **windows.h:** control de la consola y pausas de ejecución.
- **conio.h:** detección de teclas presionadas.
- **vector:** almacenamiento de asteroides y balas.
- **ctime:** inicialización de números aleatorios.
- **cctype:** conversión de caracteres a minúsculas.

## Estructura del proyecto
<pre>
juegodenaves/
│
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
├── CHANGELOG.md
│
├── docs/
│   ├── InformeEEST1_LPR2026_ACT08_G03_v1.0.0.pdf
│   │
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf
│       └── manual_usuario_v1.0.0.pdf
│
├── src/
│   └── main.cpp
│
└── capturas/
    └── combate_consola.png
</pre>

##  Objetivo

Este proyecto busca poner en práctica los conocimientos adquiridos durante la materia, especialmente los relacionados con la Programación Orientada a Objetos, el encapsulamiento, la administración de memoria y la organización del código.
También permite comprender cómo se relacionan los diferentes objetos para desarrollar un programa interactivo.
