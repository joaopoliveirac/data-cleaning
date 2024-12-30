# data-cleaning

Aplicando meus conhecimentos de limpeza e organização de dados para estruturar uma base de dados para modelagem.
Esse tratamento foi divido em 10 etapas, as quais foram:

# 1-Leitura do dataset
Receber o arquivo .csv e verificar a distribuição dos dados

# 2-Valores nulos
Verificação de valores nulos, caso existam, iremos remove-los

# 3-Preços unitários e quantidade de produtos iguais ou inferior a 0
Analise da coluna de preço e quantidade, não podemos ter valores valores negativos, nulos ou iguais a zero

# 4-Linhas duplicadas
Verificar se existem linhas duplicadas, se sim, remove-las.

# 5-Tipos de dados da coluna
Verificar o tipo de dados das colunas, e se eles fazem sentido, caso não faça, alterar

# 6-Outliers
Verificar se existem outliers, se existir remove-los

# 7-Coluna adicional
Criação de uma coluna com quantidade*preço

# 8- Data
Encontrar a data da ultima compra, iremos utiliza-la mais a frente

# 9- Plotar gráficos que fazem sentido

# 10- Calculo RFM
R= recência, diferença em dias da última compra do cliente e da última compra disponível no conjunto de dados, que calcularam previamente;
F= frequência, ou seja, a quantidade de compras feitas pelo cliente;
M= ticket médio, ou seja, a média das compras feitas pelo cliente.



