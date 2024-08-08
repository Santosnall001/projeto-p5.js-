<p xmlns:cc="http://creativecommons.org/ns#" >Este trabalho está licenciado sob <a href="https://creativecommons.org/licenses/by-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-ND 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="altura:22px!importante;margem-esquerda:3px;alinhamento-vertical:texto-inferior;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1" alt=""></a></p>

# projeto-p5.js-
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}
function setup() {
  createCanvas(400, 400);
  background("white");
}

function draw() {
}
function draw() {
  circle(200,200,50);
}
function draw() {
  fill("red");
  circle(200,200,50);
}
let cor;

function setup() {
  createCanvas(400, 400);
  background("white");
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = "blue";
}
function draw() {
  fill(cor);
  circle(200,200,50);
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(0, 255, 0);
}
random(0, 255);
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(random(0, 255), 0, 0);
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(random(0, 255), random(0, 255), random(0, 255));
}
let cor;
let posicaoHorizontal // x
let posicaoVertical // y
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(random(0, 255), random(0, 255), random(0, 255));
  posicaoHorizontal = 200;
  posicaoVertical = 200;
}
function draw() {
  
  fill(cor);
  circle(posicaoHorizontal, posicaoVertical, 50);
}
if(mouseX < posicaoHorizontal) {
    posicaoHorizontal = posicaoHorizontal - 1;
}
function draw() {
  
  fill(cor);
  circle(posicaoHorizontal, posicaoVertical, 50);
  
  if(mouseX < posicaoHorizontal) {
    posicaoHorizontal = posicaoHorizontal - 1;
  }
}
