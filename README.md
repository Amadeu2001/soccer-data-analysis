# Soccer data analysis

Este projeto demonstra como consumir dados da API Football-Data.org
 para obter informações sobre os jogos da Premier League (ID 2021) na temporada 2024/2025.

Através de um notebook em Python, são realizadas requisições à API, tratamento dos dados recebidos em formato JSON e organização das informações em um DataFrame com Pandas.


### Funcionalidades

- Consumo da API Football-Data.org usando requests;
- Autenticação com X-Auth-Token;
- Conversão da resposta JSON em DataFrame;
- Limpeza de colunas irrelevantes;
- Formatação de datas para dd-mm-aaaa.

### Tecnologias Utilizadas

- Python
- Jupyter Notebook
- Bibliotecas principais:
  - requests
  - json
  - pandas
