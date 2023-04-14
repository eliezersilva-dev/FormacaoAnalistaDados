# Projeto 05

- Neste Projeto vamos trabalhar com Encoding de Variáveis.

O Encoding de Variáveis é a substituição de um valor por outro a depender da necessidade do projeto.
Em geral a transformação da variável se dá de Variável Categórica (qualitativa) para Variável Numérica (quantitavia).
O motivo é que em análise de dados, em geral, usaremos matemática e estatística, dessa forma Variáveis Categóricas deverão ser transformadas.

Existe três principais técnicas de Encoding de Variáveis, são elas:

- Count/Frequency Encoding
    - Count -> contagem; substitui as categorias (quantitativas) pela contagem das observações dessa categoria;

    - Frequency -> frequência; substitui as categorias (quantitativas) pela porcentagem das observações (o quanto ela aparece);

    - Quando usar: Técnica usada quando se tem muitas categorias. 

- Label Encoding
    - É a substituição de uma categoria por sua representação numérica correspondente;
    - Quando usar: Técnica usada para poucas categorias (máximo 15).

- One Hot Encoding
    - Substituição de cada Variável Categórica (quantitativa) em diferentes variáveis booleanas (0 ou 1);
    - Quando usar: Técnica usada para número intermediário de categorias ou quando se precisa estabelecer uma relação binária entre as categorias.

> Cada uma das técnicas foram abordadas de forma prática nos Labs do Projeto.

#

## Descrição do Projeto

Neste projeto aplicaremos técnicas de Encoding em um cenário de Análise de Dados Para Traçar Estratégias de Crescimento e Retenção da Base de Clientes.
Embora Machine Learning não faça parte deste curso mostraremos o efeito das
transformações no modelo de aprendizado de máquina.

- Imagine uma empresa de compra e venda de carros usados. A empresa gostaria de criar um modelo preditivo capaz de prever o preço de venda de um veículo a partir de dados do modelo do veículo, a kilometragem e a idade (tempo de uso). O objetivo é fornecer uma avaliação mais precisa para o cliente e faz parte da estratégia da empresa para aumentar a retenção da base atual de clientes.
Como Analista de Dados, você deve preparar os dados para a modelagem preditiva a fim de obter o modelo mais preciso possível.
- Aplicaremos One-Hot-Encoding e Label Encoding, vamos comparar o resultado de ambas as transformações e então fazer a nossa escolha final sobre qual técnica de encoding deve ser usada para este projeto. 

> Para este projeto foram usados dados fictícios. O dataset se encontra na pasta 'dados' deste projeto.

#

📌 Projeto desenvolvido na Formação Analista de Dados da [Data Science Academy](https://www.datascienceacademy.com.br/).
