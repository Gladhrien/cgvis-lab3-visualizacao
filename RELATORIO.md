# Relatório

> [!CAUTION]
>
> - Você <ins>**não pode utilizar ferramentas de IA para escrever este relatório**</ins>.

## Identificação

- **Nome**: Eduarda Waechter
- **Cartão UFRGS:** 00304585

## Dados utilizados

> [!IMPORTANT]
>
> - Os dados utilizados devem ser informados como **links** para as fontes originais.
> - Se houver mais de um conjunto de dados, liste todos separadamente.
> - Para cada conjunto de dados, inclua também uma **descrição curta** explicando os dados.

1. **Dataset 1**: [Dataset 'Global Health Spending'](https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-04-21)
    * **Descrição curta**: Dados comparativos que mostram quanto cada país gasta em saúde, de onde vem esse dinheiro e onde está sendo gasto.
2. **Dataset 2**: [Dataset de regiões de cada país](https://api.worldbank.org/v2/country)
    * **Descrição curta**: Para algumas das análises que fiz, foi necessário separar por região, então utilizei este dataset.
3. **Dataset 1**: [Dataset de população por país](https://api.worldbank.org/v2/country/all/indicator/SP.POP.TOTL)
    * **Descrição curta**: Dados sobre a população de cada país.

## Código-fonte da visualização

> [!IMPORTANT]
>
> - Indique abaixo onde está, dentro deste repositório, o código-fonte usado para gerar a visualização.

- **Arquivo principal**: https://github.com/Gladhrien/cgvis-lab3-visualizacao/blob/main/Untitled3.ipynb
- **Arquivos complementares (se houver)**: <mark>`<preencher>`</mark>

## Imagem da visualização gerada

> [!IMPORTANT]
>
> - Insira aqui uma imagem da visualização criada por você. Troque `imagem-da-visualizacao.png` pelo caminho correto do arquivo no repositório. 
> - Se você criou alguma visualização interativa, então descreva aqui como acessá-la. Por exemplo, se for uma página HTML, coloque o link, ou se for uma visualização 3D, descreva como compilar e executar o código. 


![Visualização resultante](https://github.com/Gladhrien/cgvis-lab3-visualizacao/blob/main/final-vis.png)

## Descrição da visualização

### Legenda (*caption*)

No gráfico da esquerda, divisão dos gastos com saúde do Brasil divididos por fonte. Em azul, temos os gastos governamentais (SUS), em laranja os gastos voluntários (como planos de saúde) e em vermelho o quanto a população precisa pagar out-of-pocket (do seu bolso) no momento do atendimento.
No gráfico da direita, quanto a população brasileira precisa pagar out-of-pocket comparado com outros países. A barra de cima demonstra o valor em dólares e a de baixo a porcentagem dos gastos que são direto do bolso.

### Conclusão demonstrada pela visualização

> [!IMPORTANT]
>
> - Escreva uma conclusão curta sobre os dados com base na visualização.
> - Explique qual insight, padrão ou tendência pode ser observado.

Foram gerados diversos gráficos de visualização sobre gastos com saúde no notebook, porém a visualização acima demonstra a resposta para a pergunta que gostaria de responder com esse exercício: como o SUS se compara com outros sistemas governamentais e o quanto a população brasileira precisa pagar do seu bolso. 
Um primeiro ponto a ser notado é como os gastos governamentais com saúde não aumentaram muito através dos anos, o que é demonstrado pela linha azul relativamente estável no gráfico da esquerda.
Também é possível ver que há uma correlação negativa entre quanto as pessoas gastam com planos de saúde (voluntary) e direto do bolso. Ou seja, quando diminui-se o gasto out-of-pocket, provavelmente é porque as pessoas estão comprando planos de saúde. 
No gráfico da direita, nota-se que o Brasil está em uma faixa similar à outros países da América Latina, em um sistema 'misto' de gastos com saúde, e ainda está longe de países com sistemas universais, como a Noruega.
Uma coisa que não está nessa análise mas pode ser pensada para uma futura é o quanto é gasto em cada país proporcionalmente à renda de cada família. Com isso, talvez seja possível ver que, apesar do Brasil ter um gasto bruto baixo direto do bolso ($265), isso pode ser uma porção grande da renda familiar.
Visualização complementar: [Top países por gastos com saúde e a divisão desses gastos por fonte](https://github.com/Gladhrien/cgvis-lab3-visualizacao/blob/main/expenditure-division.png).
Outras também estão disponíveis no arquivo .ipynb.
