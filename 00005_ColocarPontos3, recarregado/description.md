Vamos agora com uma versão recarregada de `ColocarPontos3` que, claramente, se chamará  `ColocarPontos3Recarregado`.

O que modifica? Agora tem que colocar primeiro 1 pedra, depois 2 e finalmente 3; cuidado com isso, deverá respeitar **rigorosamente** a quantidade de pedras que te pedimos, se não seu procedimento não fará o correto.

Como uma imagem vale mais do que mil palavras, aí vai um exemplo de como deveria ficar o tabuleiro depois de executar `ColocarPontos3Recarregado(Verde)`, partindo da célula marcada:

<gs-board>
  GBB/1.0
    size 7 2
    cell 0 1 Verde 1
    cell 3 1 Verde 2
    cell 6 1 Verde 3
    head 0 1
</gs-board>

Dessa vez, não nos interessa aonde ficará a garra.
