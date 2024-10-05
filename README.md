Análise de Voos (2023 e 2024)
Este projeto visa a análise de dados de voos dos anos de 2023 e 2024, utilizando Python e bibliotecas como Pandas, Seaborn e Matplotlib para tratamento e visualização dos dados. O objetivo é identificar padrões, atrasos e comportamentos relacionados aos voos, bem como explorar os aeroportos de maior movimentação e os que apresentaram maiores atrasos.

Estrutura do Projeto
Arquivos de Dados
Voos 2023: Conjunto de dados de voos de 2023.
Voos 2024: Conjunto de dados de voos de 2024.
Aeroportos: Informações sobre os aeroportos (nome, sigla, cidade, estado, etc.).
Passaportes: Dados de emissão de passaportes no ano de 2023 e 2024.


Limpeza e Padronização de Dados
Leitura e Concatenação de Arquivos de Voos, carrega múltiplos arquivos CSV de voos e os concatena em um único DataFrame.
Salva o DataFrame consolidado em um arquivo CSV único para os anos de 2023 e 2024.
Renomeia as colunas para nomes mais adequados e consistentes.
Remoção de dados duplicados.
Converte colunas de datas para o tipo datetime.
Análise Exploratória dos Dados

Visualização da distribuição do status dos voos usando gráficos de barras.
Identificação dos aeroportos com maior volume de partidas.
Cálculo dos atrasos médios nos aeroportos e visualização gráfica dos principais aeroportos com maiores atrasos.


