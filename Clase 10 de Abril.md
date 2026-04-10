# Movimiento en P5

## Movimiento mouseX, mouseY





## Movimiento en x,y
let circuloAzul = 0;

function setup() {
  createCanvas(400, 400);
  background(255, 214, 247);
}

function draw() {
  circuloAzul = circuloAzul + 1 * 6;

  background(255, 214, 247);
  fill(37, 37, 133);
  ellipse(circuloAzul, circuloAzul, 50, 50);
}

## JavaScrip objects
Para ordenar las variables, ya que seran varias durante el procedimiento

* Antes del setup

let circulo=(
x:0
y:200
diameter:50,


function setup() {
  createCanvas(400, 400);
  background(255, 214, 247);

function draw() {
  circuloAzul = circuloAzul + 1;

  background(255, 214, 247);
  noStroke()
  ellipse(circulo.x,circulo.y,diameter,);

}

## Random Fuction

let tamanoCuadrado;
let bordeCuadrado;

function setup() {
  createCanvas(400, 400);
  background(255, 214, 235);
}

function draw() {
  //background(255, 214, 235);
  
tamanoCuadrado = random(20,300)
  bordeCuadrado = random (1,20)
  
  rectMode(CENTER)
  stroke(74,114,247,10) 
  strokeWeight(bordeCuadrado)
  fill(247,74,74,10)
  square(200,200,tamanoCuadrado)
}

## Movimiento mouse + Random

function setup() {
  createCanvas(1000, 1000);
  background(0,0,0)
  noCursor()
  frameRate(20)
}

function draw() {
  //background(220);
  ellipse(mouseX,mouseY,random(250))
  strokeWeight(10)
  stroke(146,192,247)
  fill(20, 64, 168)
  
   ellipse(mouseX,mouseY,random(250))
  strokeWeight(10)
  stroke(191, 65, 130)
  fill(138, 0, 73)
}
