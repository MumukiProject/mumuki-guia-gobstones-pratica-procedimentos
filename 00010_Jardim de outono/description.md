Chegou o outono e o tio Estevão teve a idéia de fazer um jardim no terraço... de novo. Como soube que você está "com essa coisa de programação", te pediu que fizesse para ele um programa em Gobstones que o ajude a fazer um layout do seu novo jardim, com as seguintes condições:

* cada **vaso de planta** é um quadrado de 2x2 (ou seja que ocupa um total  de 4 células);
* como ainda não sabe qual será o tamanho do jardim, o programa precisa funcionar **para qualquer tabuleiro** que seja suficientemente grande;
* deve existir um vaso de planta em **cada esquina do jardim** e cada um deve ser de uma cor diferente.

Como você já sabe, o tio é um pouco detalhista, então deve respeitar a ordem das cores que ele escolheu. Te deixamos um exemplo de como deveria estar o jardim, reconhecendo que possui 5 células de largura e 5 de comprimento.

<gs-board>
  GBB/1.0
    size 5 5
    cell 0 0 Rojo 1
    cell 0 1 Rojo 1
    cell 0 3 Negro 1
    cell 0 4 Negro 1
    cell 1 0 Rojo 1
    cell 1 1 Rojo 1
    cell 1 3 Negro 1
    cell 1 4 Negro 1
    cell 3 0 Azul 1
    cell 3 1 Azul 1
    cell 3 3 Verde 1
    cell 3 4 Verde 1
    cell 4 0 Azul 1
    cell 4 1 Azul 1
    cell 4 3 Verde 1
    cell 4 4 Verde 1
    head 3 0
</gs-board>

O operador começa na origem.
