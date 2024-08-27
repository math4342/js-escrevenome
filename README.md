Grandiose soil
by matheus.pedroso.sena

matheus.pedroso.sena
My Stuff
Settings
Log Out

Arquivo
Novo
Salvar
Exemplos
Editar
Organizar Código
Procurar
Esboço
Adicionar Arquivo
Adicionar Pasta
Settings
Preferences
Language
Ajuda
Atalhos de Teclado
Referência
Sobre


sketch.js
1
function setup() {
2
  createCanvas(400, 400);
3
}
4
​
5
function draw() {
6
  background(220);
7
}function setup() {
8
  createCanvas(400, 400);
9
}
10
​
11
function draw() {
12
  background(220);     
13
}
14
function draw() {
15
    background("white");
16
    
17
    rect(0, 10, 100, 150);
18
}
19
function draw() {
20
    background("white");
21
​
22
    fill("red");
23
    rect(0, 10, 100, 150);
24
}
25
function draw() {
26
    background("white");
27
    
28
    stroke("blue") 
29
    fill("red") 
30
    rect(0, 10, 100, 150)
31
}
32
function draw() {
33
  background(220);
34
  
35
  stroke("blue");
36
  fill("red");
37
  rect(mouseX, mouseY, 100, 150);
38
}
39
function draw() {
40
  background(220);
41
  
42
  stroke("blue");
43
  fill("red");
44
  
45
  console.log(mouseIsPressed);
46
  rect(mouseX, mouseY, 100, 150);
47
}
48
function setup() {
49
  // cria uma tela de 400px de largura por 400px de altura
50
  createCanvas(400, 400);
51
}
52
function setup() {
53
  createCanvas(400, 400);
54
  background("white")
55
}
56
​
57
function draw() {
58
  stroke("blue");
59
  fill("red");
60
  
61
  
62
  if (mouseIsPressed) {
63
    rect(mouseX, mouseY, 20, 35);
64
  }
65
}
66
​
