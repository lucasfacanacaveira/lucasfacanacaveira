let xBolinha = 300;
let yBolinha = 200;
let diametro = 15;

let xRaquete = 5;
let yRaquete = 150;
let larguraRaquete = 10;
let alturaRaquete = 90;

function setup() {
  createCanvas(700, 400);
}

function draw() {
  background(0);
  circle(xBolinha,yBolinha,diametro);
  rect(xRaquete, yRaquete, larguraRaquete, alturaRaquete);
}
