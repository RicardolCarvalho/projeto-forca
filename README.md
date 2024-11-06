# projeto-forca

## Ricardo e Manoela 

O projeto consiste em utilizar um jogador automático para jogar o Jogo da Forca, tentando adivinhar as palavras corretamente. O objetivo foi criar um algoritmo que, com base no vocabulário, seja capaz de escolher letras que maximizem as chances de sucesso com o mínimo de tentativas possíveis. 

O uso da probabilidade e análise de frequência das letras nas palavras do vocabulário disponível foi o conceito principal. Essa estratégia se baseia na ideia de que a distribuição de letras em uma língua contém informação suficiente para realizar aproximações sobre a palavra que o jogador quer acertar. 
Para isso, fizemos uma contagem de frequência de letras nas palavras possíveis e calculamos suas probabilidades para selecionar as mais "promissoras" em cada rodada. Ou seja, o jogador identifica letras comuns nas palavras que ainda não foram testadas e prioriza as que têm maior probabilidade de serem encontradas com base na sua frequência. 

Isso pode ser considerado como uma forma de otimização, isot é, ao calcular probabilidades, o jogador minimiza as tentativas desperdiçadas. Além disso, esse conceito se relaciona com teoria da informação ao buscar a letra que pode trazer o maior ganho de informação sobre a palavra da forca. Essa ideia é similar com a entropia, em que letras mais frequentes podem forncecer um "caminho de menos incerteza" sobre a palavra certa. 

Os testes foram feitos com diferentes palavras e o desempenho foi avaliado em relação ao número de tentativas e vidas restantes em cada rodada. No código, há uma simulação de diversas partidas e observamos os resultados em um gráfico, que nos ajudou a entender a eficiência da estratégia de probabilidade. O jogador apresentou um desempenho bom na maioria dos casos, mas falhou em palavras com letras menos comuns, isso demonstra que há uma limitação do modelo baseado apenas em frequências. 

Portanto, o projeto mostra como conceitos de alg. linear e teoria da informação podem ser usados para resolver problemas de interferência em contextos que demonstram que a incerteza é alta e as decisões devem ser tomadas com o mínimo de informações diretas sobre a palavra. 

