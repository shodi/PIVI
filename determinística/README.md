## NECESSÁRIO GNUPLOT
# Para compilar `gcc simulacao.c -o sim.exe`
# Para executar `./sim.exe example.txt`

Simulação determinística do deslocamento de uma partícula com aceleração variada.
No arquivo de entrada devemos possuir na primeira linha: velociade e aceleração iniciais
todas as linhas subsequentes serão aceleração num proximo segundo. Entao se meu arquivo possuir 5 linhas, minha simulação vai determinar a velocidade da minha partícula após 5 segundos com a aceleração podendo variar, ou não.
Unidades de medida:
    Tempo:: segundo
    Velocidade:: metro/segundo
    Aceleração:: metro/segundo²
Entradas:
    Velocidade e aceleração iniciais e acelerações nas linhas consecutivas
Saídas:
    Gráfico de evolução da velocidade da partícula, por segundo, no arquivo nomeado `velocidy.png`.
    Gráfico de evolução da aceleração da partícula, por segundo, no arquivo nomeado `aceleration.png`.
    Informação textual a respeito da velocidade final da partícula no arquivo `result.txt`.

*Para exemplo de entrada, vide `example.txt`.