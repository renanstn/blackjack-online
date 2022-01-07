# blackjack-online

## Regras do Blackjack

### Valores das cartas

Cada carta vale o valor do seu número
Figuras valem 10
O A vale 1 ou 11

Somar 21 nas cartas = `blackjack`

### Andamento do jogo

Toda rodada possui um dealer

O dealer entrega 2 cartas para cada jogador, virada para cima
Por último, o dealer pega 2 cartas, e as deixa uma virada para cima, e outra para baixo

Se em qualquer momento um jogador desistir (surrender), ele automaticamente perde metade da sua aposta para o dealer

Em sua vez, cada jogador possui 2 ações:
- Pedir uma carta (hit)
- Parar (stand)

Se os valores das cartas forem `>21`, o jogador automaticamente perde

O dealer joga por último, vira a sua carta oculta para cima, e joga como os outros jogadores

Se o jogador parar, e ganhar do dealer, ele recebe do dealer o valor da apostado
Se o dealer ganhar, ele pega o valor apostado pelo jogador

### Split

Caso você comece com 2 cartas iguais, você pode fazer a divisão (split), isso é, dividir as cartas, apostando o mesmo valor que já estava apostado no monte inicial, em outro monte, e com isso ele joga 2 vezes, uma para cada monte.

### Insurance

Se a carta virada pra cima do dealer for um A, você pode abrir um seguro (insurance): o seguro é aberto com METADE do valor apostado.
Feito um seguro, na rodada do dealer, se a próxima carta que ele virar, for um 10 ou uma figura, ele faz blackjack (21), e você ganha 2 vezes o valor do seu seguro.
