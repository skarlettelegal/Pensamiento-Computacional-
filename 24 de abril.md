# Funciones Propias — Pensamiento Computacional

## ¿Qué es el pensamiento computacional?

El pensamiento computacional es una forma de resolver problemas utilizando lógica y organización.  
Se basa en 4 pilares principales:

- Descomposición
- Reconocimiento de patrones
- Abstracción
- Algoritmos

# 1. Descomposición

Consiste en dividir un problema grande en partes más pequeñas para resolverlo de forma más simple.

## En programación

Se usa mediante funciones propias para separar tareas dentro del código.

function dibujarCirculo() {
  ellipse(100, 100, 50, 50);
}


# 2. Reconocimiento de patrones

Se basa en identificar elementos que se repiten para automatizarlos.

## En programación

Se utiliza principalmente con ciclos `for`.

for (let i = 0; i < 5; i++) {
  ellipse(i * 50, 100, 30, 30);
}


# 3. Abstracción

Consiste en quedarse solo con la información importante y eliminar detalles innecesarios.

## En programación

Se representa mediante variables y valores dinámicos.


let tamaño = mouseX;

ellipse(200, 200, tamaño, tamaño);


# 4. Algoritmos

Son instrucciones ordenadas paso a paso para resolver un problema.

## En programación

Se usan estructuras condicionales como `if` y `else`.


if (mouseX > 200) {
  background(255);
} else {
  background(0);
}


# Tipos de interacción

## Interacción discreta

Ocurre cuando el usuario realiza una acción específica, como un clic.


function mousePressed() {
  ellipse(mouseX, mouseY, 40, 40);
}


## Interacción continua

El sistema responde constantemente al movimiento o acciones del usuario.


ellipse(mouseX, mouseY, 50, 50);


# Funciones propias

Las funciones propias permiten organizar mejor el código, hacerlo modular y reutilizable.
