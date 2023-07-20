# Machine Learning
# Regressão Linear - Análise de Dados de Preços de Produtos

## Descrição

Este repositório contém um programa escrito em Python que realiza uma análise de regressão linear usando dados de preços de produtos. O objetivo é fornecer uma ferramenta para empresas interessadas em compreender as relações entre as características dos produtos e seus preços.

## Dados

Os dados utilizados no programa estão armazenados no arquivo "dadospararegressao.csv". O arquivo contém as seguintes colunas:

- 'preço pix': Preço do produto em moeda local (variável dependente)
- 'Garantia': Tempo de garantia do produto em meses
- 'peso': Peso do produto em gramas
- 'memoria': Capacidade de memória do produto em GB
- 'fonte w': Potência da fonte do produto em watts
- 'boostclock': Clock de aumento do produto em MHz

## Dependências

Para executar o programa, você precisará das seguintes bibliotecas Python:

- pandas
- statsmodels
- scikit-learn
- matplotlib

Você pode instalar as dependências usando o seguinte comando:

```
pip install pandas statsmodels scikit-learn matplotlib
```

## Instruções de Uso

1. Faça o clone ou o download deste repositório.
2. Certifique-se de que o arquivo "dadospararegressao.csv" esteja no mesmo diretório que o arquivo do programa.
3. Execute o programa em um ambiente Python com as dependências instaladas.
4. O programa realizará uma análise de regressão linear usando os dados fornecidos e exibirá os resultados.

## Análise de Regressão Linear

O programa utiliza a biblioteca pandas para ler os dados do arquivo CSV e, em seguida, realiza uma análise de regressão linear usando a biblioteca statsmodels. A variável dependente é o "preço pix" e as variáveis independentes são "Garantia", "peso", "memoria", "fonte w" e "boostclock".

Após a análise, o programa gera um gráfico com os valores previstos pela regressão (em vermelho) e os valores reais dos preços dos produtos (em preto).

## Resultados

Os resultados da regressão linear são salvos no arquivo "resultadoregressao.csv", contendo as previsões para os preços dos produtos.

## Notas

- Este programa foi desenvolvido para fins educacionais e pode não refletir uma análise completa e abrangente.
- Recomendamos a revisão dos dados e a aplicação de técnicas estatísticas mais avançadas para análises mais precisas.

## Autor

Davi Damasceno
E-mail de Contato: ddavidamasceno@email.com
