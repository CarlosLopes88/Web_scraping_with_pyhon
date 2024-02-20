# Web Scraping de Dados Cadastrais de Empresas

Este projeto consiste em um código Python desenvolvido em um Jupyter Notebook para realizar web scraping do site [ReceitaWS](https://www.receitaws.com.br), a fim de coletar dados cadastrais abertos de empresas a partir de uma lista de CNPJs fornecida em um arquivo Excel.

## Requisitos

Para executar o código, você precisará das seguintes bibliotecas Python:

- `bs4` (Beautiful Soup)
- `requests`
- `pandas`
- `numpy`
- `time`
- `google.colab` (se estiver usando o Google Colab)

Você pode instalá-las usando o pip:

            pip install beautifulsoup4 requests pandas numpy

## Estrutura do diretório

Web_scraping_with_pyhon/  
├── Readme.md  
├── Tratamento da lista em PQ.xlsx  
├── Web_scraping_receitaws.ipynb  
└── lista.xlsx  

## Instruções de Execução

1. Clone ou faça o download deste repositório para a sua máquina local.
2. Certifique-se de ter instalado as bibliotecas listadas nos requisitos.
3. Execute o Jupyter Notebook `web_scraping_receitaws.ipynb`.
4. No notebook, forneça o caminho do arquivo Excel contendo a lista de CNPJs a serem consultados.
5. Execute todas as células do notebook. O código irá realizar a consulta ao site e coletar os dados, respeitando o intervalo de 20 segundos entre cada consulta.
6. Após a conclusão da coleta, os dados serão salvo em um arquivo Excel chamado `lista_pronta.xlsx`.

Obs: utilize o arquivo "Tratamento da lista em PQ.xlsx" para tratamento dos dados no powerquery.

## Tecnologias Utilizadas

- Python;
- Jupyter Notebook;
- Beautiful Soup (para análise HTML);
- Requests (para fazer solicitações HTTP);
- Pandas (para manipulação de dados);
- NumPy (para manipulação de arrays).