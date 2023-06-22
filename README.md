<h1 align='center'>Estatistica-parte-2</h1>

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/estatistica-parte-2)
![GitHub Org's stars](https://img.shields.io/github/stars/fab-souza/estatistica-parte-2?style=social)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Estatística com Python parte 2: probabilidade e amostragem**
| :label: Tecnologias | python
| :rocket: URL         | Notebook no [Kaggle](https://www.kaggle.com/code/fabianadesouza/estatistica-parte-2)
| :fire: Desafio     | Conteúdo do 4º [curso](https://www.alura.com.br/curso-online-estatistica-probabilidade-e-amostragem) da formação [Data Science](https://www.alura.com.br/formacao-data-science)

![](https://user-images.githubusercontent.com/67301805/236349468-3b024586-dcb1-48db-98fd-8779169a49e1.jpg#vitrinedev)


# Sobre o curso 📚

Este é o segundo curso de estatística básica da [Alura](https://www.alura.com.br/), também ministrado pelo instrutor [Rodrigo Dias](https://www.linkedin.com/in/rodrigo-fernando-dias-118181120/). No curso anterior, o foco estava nas frequências e medidas, enquanto neste, houve um aprofundamento em conceitos teóricos, por exemplo, 
- o que são as distribuições de probabilidade (binomial, de Poisson e normal) que são utilizadas para modelar diferentes eventos e fenômenos;
- também foi discutido o conceito de nível e intervalo de confiança, que são usados para fazer inferências estatísticas;
- além disso, foram apresentadas técnicas de amostragem e o cálculo do tamanho da amostra.  

Os conceitos do curso foram aplicados ao dataset da [Pesquisa Nacional por Amostra de Domicílio](https://www.ibge.gov.br/estatisticas/sociais/populacao/19897-sintese-de-indicadores-pnad2.html?=&t=microdados), provenientes do IBGE. 

![image](https://user-images.githubusercontent.com/67301805/236932527-88136f4d-4077-4419-81e4-6e36380afceb.png)

Desta forma, finalizamos o curso elaborando um projeto, com ênfase em **Probabilidade**, **Amostragem**, e **Estimação**.

![image](https://github.com/fab-souza/estatistica-parte-2/assets/67301805/da9e06c7-eb1d-4af9-9868-1ea2ef6a611b)
![image](https://github.com/fab-souza/estatistica-parte-2/assets/67301805/55bef16d-59e6-4b6f-b27b-ffa8335b6402)
![image](https://github.com/fab-souza/estatistica-parte-2/assets/67301805/3fedc309-655c-4cc3-981e-546e4b390079)
![image](https://github.com/fab-souza/estatistica-parte-2/assets/67301805/2fe71e45-79bf-4b2f-b131-336a0b973000)



# Minha prática 👩🏻‍💻

Mais uma vez, eu decidi trabalhar com um dataset referente aos empreendimentos de geração de energia elétrica presentes no país, os dados da [Agência Nacional de Energia Elétrica](https://dadosabertos.aneel.gov.br/dataset/siga-sistema-de-informacoes-de-geracao-da-aneel).

![image](https://github.com/fab-souza/estatistica-parte-2/assets/67301805/17e9dee7-35ce-48f6-9403-d800f0369919)

Ao utilizar este dataset, eu não teria à disposição todos os tipos de dados (qualitativa ordinal e nominal, quantitativa discreta e contínua), e com distribuições que representassem condições ideias para análise. No entanto, achei interessante trabalhar com essa ‘imperfeição’ nos dados, pois acredito que, em um ambiente de trabalho, a situação seja semelhante.

Decidi replicar os problemas A, B e C, apresentados no curso, para este dataset e adaptando alguns pontos.

## Problema A:

A proporção de Usinas Solar Fotovoltaicas (UFV) presentes no parque gerador nacional, é um pouco maior do que 75%. Considerando os outros tipos de usina como ‘Não UFV’, qual a probabilidade de selecionar aleatoriamente um grupo de 10 usinas que apresente uma proporção semelhante à da população?

## Problema B:

Ainda sobre a questão anterior, quantos grupos (de 10 usinas) será preciso selecionar, de forma aleatória, para conseguir 100 grupos compostos por 7 usinas UFV e 3 'Não UFV'?

## Problema C:

Tenho que fazer um estudo para avaliar o **preço de automóveis**. Para isso, preciso realizar uma pesquisa de campo. Após reunião com meu supervisor fictício, foi possível elencar o seguinte conjunto de informações:

- Tenho somente **R$ 30.000,00** de recursos para realização da pesquisa de campo; e

- Seria interessante uma **margem de erro** não superior a **10%** em **relação a média estimada**.

Em estudos deste tipo, o **custo médio por entrevista**, fica em torno de **R$95,00**. Com este conjunto de fatos, preciso avaliar e obter as seguintes informações:

> 1. Para obter uma estimativa para os parâmetros da população (preço dos automóveis), realize uma amostragem aleatória simples no conjunto de dados. Essa amostra deve conter 300 elementos, obtenha a média e o desvio-padrão dessa amostra.
> 2. Para a **margem de erro** especificada, obtenha os **tamanhos de amostra** necessários para garantir os **níveis de confiança de 90%, 95% e 99%**.
> 3. Obtenha o **custo da pesquisa** para os três níveis de confiança.
> 4. Para o maior nível de confiança viável (dentro do orçamento disponível), obtenha um **intervalo de confiança para a média da população**.
> 5. Assumindo o **nível de confiança escolhido no item anterior**, qual **margem de erro** pode ser considerada utilizando todo o recurso disponibilizado?
> 6. Assumindo um **nível de confiança de 95%**, **quanto a pesquisa custaria**, caso fosse considerada uma **margem de erro de apenas 5%** em relação à média estimada?

# Conclusão 🏁

Fiquei contente em concluir o curso, no qual aprendi como calcular uma série de tópicos essenciais em estatística através de métodos do Scipy, entre eles:
- as Distribuições Binomial, Poisson e Normal, que são fundamentais para lidar com dados estatísticos e realizar análises mais precisas; 
- os conceitos de Nível e Intervalo de Confiança, que permitem avaliar a precisão de estimativas estatísticas e fornecem uma base sólida para a tomada de decisões baseadas em dados; 
- as técnicas de Amostragem, pois selecionar uma amostra representativa de uma população é crucial para evitar vieses e garantir a validade das conclusões estatísticas que podemos obter a partir dos dados coletados; 
- e por último, mas não menos importante, calcular o tamanho da amostra necessário para alcançar uma margem de erro desejada, que é uma habilidade inestimável ao planejar estudos e pesquisas, pois permite determinar a quantidade adequada de dados a serem coletados para obter resultados confiáveis.

Ter a oportunidade de aplicar esses conhecimentos em uma simulação de projeto foi extremamente gratificante, poder ver na prática como as técnicas estatísticas podem ser úteis na resolução de problemas e na tomada de decisões só reforçou a importância do curso.

Em suma, estou muito contente de ter aprendido todos os tópicos e de ter colocado a mão na massa, agora me sinto mais preparada para enfrentar desafios estatísticos no futuro e utilizar essas habilidades para tomar decisões informadas e embasadas em dados.

---

Muito obrigada por chegar até aqui e até a próxima 🤗

## Ferramentas utilizadas 🧰
<p>
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
  <a href="https://scipy.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/b/b2/SCIPY_2.svg" alt="scipy" width="40" height="40"/> </a>
  </p>
  
<br><hr>
[🔼 back to Top](https://github.com/fab-souza/estatistica-parte-2/tree/main#estatistica-parte-2)
