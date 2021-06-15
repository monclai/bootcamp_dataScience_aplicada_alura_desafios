# 2° Desafio Bootcamp data science
---

## Motivação

Históricamente as vacinas estão ligadas ao mundo financeiro, essa ligação pode ser percebida no custo de produção, na qualidade de vida e nos custos do estado com a população. Com isso, podemos ver um exemplo claro da relação entre os custo do estado e a vacinação no epsódio histórico da revolta da vacina no estado do Rio de Janeiro, na qual vemos a vacinação como coadjuvante de um momento de calamidade de saúde pública e financeira.

fonte: [Revolta da Vacina | Nerdologia](https://www.youtube.com/watch?v=SlsHN-OWCkw)

---

## Hipótese

Diante da motivação podemos levantar como hipótese de que o índice de vacinação gera impactos nos custo hospitalares.

---

## Desenvolvimento

Em vista da motivação, foi realizada a filtragem dos estados com os maiores custos hospitales, também foi filtrado o indice de vacinação de tais estados na última década.   
De acordo com o datasus, os estados com maiores custo são: São Paulo, Minas Gerais e Paraná.  

### fontes
[Datasus - Tabnet](https://datasus.saude.gov.br/informacoes-de-saude-tabnet/)  
[Lista de unidades federativas do Brasil por população - Wikipedia](https://pt.wikipedia.org/wiki/Lista_de_unidades_federativas_do_Brasil_por_popula%C3%A7%C3%A3o)

### Resultados

![Resultados](https://github.com/monclai/bootcamp_dataScience_aplicada_alura_desafios/blob/main/desafio_02/imagens/resultado.png?raw=true)

Como podemos ver apesar de ocorrerem oscilações no indice de vacinação na última na década tal fator não gerou interferências nos gastos hospitalares dos três estados com maiores gastos.

### Conclusão

Podemos concluir que a vacinação é apenas preventiva e com foco no controle das doenças, doenças essas que já estão em estado estável, dessa forma mudanças no indice de vacinação não geram grandes efeitos colaterais, principalmente nos cofres públicas como demonstrado no gráfico acima.

[código fonte da pesquisa](https://github.com/monclai/bootcamp_dataScience_aplicada_alura_desafios/blob/main/desafio_02/notebook/Desafio_02.ipynb)
