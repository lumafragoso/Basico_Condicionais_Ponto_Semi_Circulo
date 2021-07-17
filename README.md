# Basico_Condicionais_Ponto_Semi_Circulo
Assessment activity of the 1º period of IT Bachelor on Basic and Conditionals in Python / Atividade avaliativa do 1º periodo do Bacharelado em TI sobre Básico e Condicionais em Python

## Ponto no Semi-Círculo

### Goal / Objetivo

The figure below is defined by the set of points (x,y) that meet the following criteria: x>=0, y>=0 and x^2+y^2<=1. That is, a semi-circle with a radius equal to 1.
Write a program to check whether a given point p, defined by its coordinates (x,y), belongs or not to the region drawn in the figure. Your program should initially draw the semi-circle, axes, and figure texts. Then the program must read the x and y coordinate values ​​of P from the user and draw it. If P is inside the figure, it must be drawn in green color, if not, it must be drawn in red.
To visually confirm that the point belongs or not to the region, draw the figure and points to scale. To do this just multiply all values ​​by some fixed number. For example, if the scale is 10, draw the semi circle with radius 10, and multiply the coordinates of the received points by 10 before drawing! Note that scale is just a matter of design, you don't need to change anything in the equation.
Pay attention to the elements of the drawing as they are the hardest part of the question, don't get hung up on the colors (as long as the arc, lines, dots and letters have different colors, it's ok!), but try to draw all of them elements!
Some tips for drawing:
1. Use the function with its additional parameter, the function takes two parameters, in the form circle(r, a), where r is the radius and a is the degree of the arc to be drawn.
2. Use the function write(text, font=('Arial', 8, 'normal')). Changing the font size to a size that is readable in the picture. Remember to move the turtle to the desired position before drawing.
3. Use the turtle.dot(size=2) function to draw a point at the position where the turtle is.

A figura abaixo é definida pelo conjunto de pontos (x,y) que atendem os seguintes critérios: x>=0, y>=0 e x^2+y^2<=1. Ou seja, um semi-círculo de raio igual a 1. 
Escreva um programa para verificar se um dado ponto p, definido através de suas coordenadas (x,y), pertence ou não à região desenahda na figura. Seu programa deve inicialmente desenhar o semi circulo, os eixos e os textos da figura. Depois o programa deve ler do usuário os valores das coordenadas x e y de P e desenhá-lo. Caso P esteja dentro da figura, ele deve ser desenhando na cor verde, caso não esteja deve ser desenhado na cor vermelha.
Para confirmar visualmente que o ponto pertence ou não à região, desenhe a figura e os pontos em escala. Para fazer isso apenas multiplique todos os valores por algum número fixo. Por exemplo, se a escala é 10, desenhe o semi círuclo com raio 10, e multiplique as coordenadas dos pontos recebidos por 10 antes de desenhar! Veja que a escala é apenas uma questão relacionada ao desenho, não precisa mudar nada na equação.
Atente para os elementos do desenho uma vez que são a parte mais dificil da questão, não se prenda às cores (desde que o arco, as linhas, os pontos e as letras tenham cores diferentes, está ok!), mas tente desenhar todos os elementos!
Algumas dicas para o desenho:
1. Use a função com seu parametro adicional, a função recebe dois parâmetros, no formato circle(r, a), onde r é o raio e a é o grau do arco a ser desenhado.
2. Use a função write(texto, font=('Arial', 8, 'normal')). Mudando o tamanho da fonte para um tamanho que fique legível na figura. Lembre de mover a turtle para a posição desejada antes de desenhar.
3. Use a função turtle.dot(size=2) para desenhar um ponto na posição em que a turtle estiver.

1. Example / Exemplo
```py

x:  1
y:  1
não pertence

x:  0.2
y:  0.2
pertence

x:  -0.1
y:  0.3
não pertence

x:  1
y:  0
pertence
```
