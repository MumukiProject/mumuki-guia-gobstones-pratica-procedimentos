Bom, agora vem um exercício para pensar um pouquinho...

Se você quiser criar um programa que faça um “moinho" como o da  figura. A garra pode pensar que já está no centro do tabuleiro. Preste atenção que em cada "aspa" vai aumentando a quantidade de pedras a medida que se distancia do centro.

<gs-board>
  GBB/1.0
    size 7 7
    cell 3 0 Negro 3
    cell 3 1 Negro 2
    cell 3 2 Negro 1
    cell 3 4 Negro 1
    cell 3 5 Negro 2
    cell 3 6 Negro 3
    cell 0 3 Negro 3
    cell 1 3 Negro 2
    cell 2 3 Negro 1
    cell 4 3 Negro 1
    cell 5 3 Negro 2
    cell 6 3 Negro 3
    head 3 3
</gs-board>

Aquí é fundamental **pensar que parte se repete** e definir a estratégia a partir disso.
