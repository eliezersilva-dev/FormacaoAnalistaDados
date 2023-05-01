# Projeto 09

Neste projeto serão aplicados os conceitos de Pré Processamento de Dados.

    Definição: Pré-Processamento de Dados é tudo aquilo que é feito desde a coleta dos dados brutos até a entrega dos dados prontos para a análise.

    Pré-Processamento -> Limpeza, Engenharia de Atributos, Redução e Transformação.

> O Pré-Processamento deve necessariamante transformar os dados mas não a informação.

#

## Principais Técnicas:

Técnica  | Categoria | Quando Usar | Como Usar 
---------|----------|--------------|----------
Imputação de valores ausentes | Permissão de leitura | Normalmente no início do projeto | Diferentes estratégias a depender do tipo de dado
Detecção e Tratamento de Outliers | Limpeza | Normalmente no início do projeto | Diferentes estratégias a depender da necessidade do projeto
Redução de Dimensinalidade | Redução | Normalmente usada quando o número de variávies é muito alto | Técnicas como PCA, LDA, High correlation filter e Low variance filter podem ser aplicadas
Seleção de Atributos | Redução | Sempre que a análise exploratória demonstrar que algumas variáveis podem não ser relevantes | Aplicar Machine Learning para seleção automática das variáveis ou usar conhecimento do problema
Extração de Atributos | Engenharia de Atributos | Quando for necessário simplificar os dados para análise ou reduzir o tempo de processamento | Aplicar Machine Learning ou alguma técnica matemática
Transformação dos dados | Transformação | Sempre que for necessário converter variáveis | Aplicar a conversão dependendo do tipo de variável
Normalização e Padronização dos Dados | Transformação | Sempre que for necessário colocar os dados na mesma escala ou seguindo uma distribuição normal | Python oferece diversas funções para esse tipo de pré-processamento
Particionamento dos Dados | Redução | Quando for necessário reduzir o volume de dados ou fazer análise por particões dos dados | Pode ser feito via programação
Aumento de Dados (Data Augmentation) | Transformação | Quando o volume de dados não for suficiente para a análise | O pacote Scikit-Learn fornece funções para esse tipo de tarefa
Agregação, Suavização, Binarização | Transformção | Sempre que os dados tiverem que ser resumidos | Python e/ou SQL 
Generalização, Discretização | Transformação | Quando a generalização for suficiente para análise | Python e/ou SQL
Transfer Learning | Redução | Sempre que houver um modelo pré treinado disponível | Técnica avançada de IA
#

## Descrição do Problema:
Toda empresa que tem presença na internet pode estar interessada em extrair insights de comentários de usuários sobre seus produtos ou serviços, sobre concorrentes, sobre o
mercado ou sobre suas próprias preferências.

Neste projeto teremos em mãos dados de texto simulando comentários de usuários. Dados de texto são dados em formato não estruturado e seria muito difícil usar um Data Warehouse para armazenar os dados e realizar análise. Por essa razão, usaremos um Data Lake, onde os dados serão carregados em seu formato bruto e então faremos o pré-processamento
dos dados em tempo de análise para entregar insights aos tomadores de decisão.

#

Para este projeto preparamos uma massa de dados fictícios simulando posts de comentários de usuários em redes sociais e/ou blogs. Usamos o site abaixo para gerar a massa de dados:

https://www.mockaroo.com/

#

📌 Projeto desenvolvido na Formação Analista de Dados da [Data Science Academy](https://www.datascienceacademy.com.br/).
