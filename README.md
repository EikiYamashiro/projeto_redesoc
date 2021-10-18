# Projeto Final - Redes Sociais

Repositório do projeto final da disciplina Redes Socias, sexto semestre de Engenharia de Computação no Insper.

**Insper - Instituto de Ensino e Pesquisa**

6º Semestre - Engenharia de Computação

Antonio Fuziy, Eiki Yamashiro, Marcelo Miguel

### Database

- The Marvel Universe Social Network: https://www.kaggle.com/csanhueza/the-marvel-universe-social-network?select=edges.csv

- Etherium Blockchain: https://www.kaggle.com/bigquery/ethereum-blockchain?select=transactions

- Twitch Social Network: https://www.kaggle.com/andreagarritano/twitch-social-networks

- Esport Team Earnings: https://www.kaggle.com/chanoncharuchinda/top-100-highest-overall-esport-team-earning


## Ciclo 1:

### Escolha do Database:

- Top 250 Football transfers from 2000 to 2018: https://www.kaggle.com/vardan95ghazaryan/top-250-football-transfers-from-2000-to-2018

### MP1:

- Formular hipótese baseada em redes, explicar um fenômeno, deve ser específica para ser rejeitada.
- Utilizar conceitos na hipótese.
- Propor um mecanismo que justifica a hipótese e explicar os conceitos usados no mecanismo.
- Mecanismos sem saltos lógicos.
- Formular hipótese alternativa.
- Formular mecanismo alternativo.
___

### Conceitos

- **Sucesso da transferência:** Caso o time consiga intermediar uma boa compra e venda, mensurada a partir do percentual do lucro.

- **Times recrutadores:** Times que contratam jogadores promissores e vendem para clubes maiores por maior preço.

### Variáveis

- **Lucro:** Percentual calculado a partir do valor de compra e venda do jogador.

- **Betweenness:** Centralidade que mensura a capacidade de intermediar diferentes "panelinhas".

### Hipótese

**Times recrutadores que intermediam diferentes ligas, possuem maior sucesso nas transferências.**

### Mecanismo

Times das mesmas ligas costumam realizar mais transferências entre si, por outro lado, grandes jogadores, aqueles mais caros, passam por diferentes ligas ao longo de suas carreiras. Dessa forma, existem times que aproveitam jogadores promissores de times menores em ligas menos valorizadas para revelá-los aos times maiores, de modo a intermediar diferentes ligas **(alto betweenness)**.

### Hipótese Alternativa

**Times grandes, os quais não dependem do sucesso das tranferências, intermediam mais delas entre diferentes ligas.**

### Mecanismo Alternativo

Times grandes compram jogadores reconhecidos, bem conceituados e com valor alto de mercado de outros times grandes muitas vezes de outras ligas, visto que rivais nacionais evitam realizar transferências entre si. Além disso, os times grandes possuem receitas em outros setores, assim não se preocupam em realizar operações de vendas lucrativas de jogadores comprados anteriormente.