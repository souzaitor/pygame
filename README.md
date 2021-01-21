# Pygame Guide

## Table of Contents

  1. [Rect Objects](#rect-objects)

## Rect Objects
O pygame tem duas formas de representar formas retângulares:

- Tupla de quatro inteiros:

  1. A coordenada X do canto superior esquerdo. 
  2. A coordenada Y do canto superior esquerdo.
  3. A largura (em pixels) do retângulo.
  4. A altura (em pixels) do retângulo.
  
 - Objetos do tipo pygame.Rect
 
  ```python
  import pygame
  spamRect = pygame.Rect(10, 20, 200, 300)
  ```

| Nome do atributo  | Descrição |
| ------------- | ------------- |
| myRect.left |  O valor inteiro da coordenada X do lado esquerdo do retângulo.|
| myRect.right | TO valor inteiro da coordenada X do lado direito do retângulo. |
| myRect.top | O valor inteiro da coordenada Y do lado esquerdo do retângulo. |
|myRect.bottom | O valor inteiro da coordenada Y do lado direito do retângulo. |
|myRect.centerx | O valor inteiro da coordenada X do centro do retângulo. |
|myRect.centery | O valor inteiro da coordenada Y do centro do retângulo. |
|myRect.width | O valor inteiro da largura do retângulo. |
|myRect.height | O valor inteiro da altura do retângulo. |
|myRect.size | Uma tupla de dois inteiros: (width, height) |
|myRect.topleft | Uma tupla de dois inteiros: (left, top) |
|myRect.topright | Uma tupla de dois inteiros: (right, top) |
|myRect.bottomleft |Uma tupla de dois inteiros: (left, bottom) |
|myRect.bottomright |Uma tupla de dois inteiros: (right, bottom) |
|myRect.midleft |Uma tupla de dois inteiros: (left, centery) |
|myRect.midright |Uma tupla de dois inteiros: (right, centery) |
|myRect.midtop |Uma tupla de dois inteiros: (centerx, top)|
|myRect.midbottom |Uma tupla de dois inteiros: (centerx, bottom) |
