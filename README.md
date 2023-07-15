# Árvore Pitágoras
Implementação da Árvore de Pitágoras em JS D3

# Como construir a árvore de Pitágoras

A “Árvore de Pitágoras” é um fractal construído apenas com quadrados, numa disposição inspirada no famoso Teorema de Pitágoras.
 

Construí um programinha em Javascript – D3, para plotar interativamente a Árvore de Pitágoras. Mexa em [https://asgunzi.neocities.org/ArteMatematica/arvorepitagoras](https://asgunzi.neocities.org/ArteMatematica/arvorepitagoras).

Como construir a árvore?

Iniciamos com um quadrado. Sobre ele, colocamos um triângulo equilátero, com ângulo θ. No caso mais simples, esse ângulo será de 45º.

![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore01.png)

A partir do triângulo, desenhar dois quadrados, conforme a figura.

 
![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore02.png)

Podemos seguir a mesma regra, para a próxima etapa, com base nos dois triângulos construídos.

 ![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore03.png)


Podemos continuar indefinidamente. 
 
![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore01.png)


Não necessariamente o ângulo inicial deve ser os 45º (que tornam o triângulo retângulo e remetem diretamente à Pitágoras).

Podemos usar a mesma regra com um ângulo menor...

![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore04.png)


Ou um maior:
 
![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore05.png)

Que resultarão em árvores mais “fechadas” ou “abertas”, respectivamente.

![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore06.png)

 


![](https://ideiasesquecidas.files.wordpress.com/2023/07/arvore07.png)



Seja como for, é um ótimo experimento.



Veja também:
[https://ideiasesquecidas.com/laboratorio-de-matematica/](https://ideiasesquecidas.com/laboratorio-de-matematica/)

[https://ideiasesquecidas.com/2023/02/22/tiling-um-quarto-de-truchet/](https://ideiasesquecidas.com/2023/02/22/tiling-um-quarto-de-truchet/)

