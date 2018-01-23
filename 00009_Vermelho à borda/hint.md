Como não sabemos as dimensões que terá o tabuleiro, não é possível usar `Mover` para chegar até a borda.

Existe uma primitiva chamada `IrABorda`, que escolhe uma direção, e se move ao máximo nessa direção, **até chegar na borda**. Nesse caso você precisa conseguir quea garra fique em uma esquina, e portanto deve pensar em **duas bordas**: Norte e Oeste.