Nesse espaço você encontra os arquivos dos meus projetos relacionados a BI.

1 - ***Relatorio_estudo:***
Recentemente, enfrentei um desafio interessante proposto pela equipe do Empowerdata. Fui incumbido de analisar uma base de dados de acidentes de trânsito na região Sudeste do Brasil, abrangendo os anos de 2018 a 2020, e construir um dashboard interativo no Power BI. Quero compartilhar com vocês o processo e as análises realizadas, destacando os pontos fortes e fracos do projeto.

Objetivos do Projeto
Quantificar o total de eventos ocorridos com visões por horários, dias da semana e estados.
Levantar a quantidade de óbitos e feridos.
Criar um mapa com a geolocalização dos eventos.
Comparar a quantidade de registros entre os anos.
Inserir uma análise da quantidade de óbitos a cada cem registros.
Calcular a média de acidentes por dia.
Passos Realizados
Importação e Consolidação dos Dados

Utilizei o Power Query para importar e consolidar as três bases de dados de 2018, 2019 e 2020 em uma única tabela. Isso facilitou a manipulação e análise dos dados.
Transformação e Limpeza dos Dados

Realizei a extração de informações cruciais como o ano e mês das datas dos acidentes.
Criei colunas calculadas para categorizar os acidentes com base na criticidade, utilizando uma pontuação específica para mortos, feridos graves, feridos leves, ilesos e ignorados.
Classificação dos Acidentes

Desenvolvi uma lógica para classificar os acidentes em três níveis de criticidade:
Nível 1: Pontuação de 0 a 30
Nível 2: Pontuação de 31 a 90
Nível 3: Pontuação maior que 90
Análises e Visualizações

Criei gráficos para comparar a quantidade de acidentes por ano e por mês.
Desenvolvi um mapa interativo para visualizar a geolocalização dos acidentes.
Análise de óbitos e feridos, mostrando a proporção de óbitos a cada cem registros.
Calculei a média de acidentes por dia e destaquei os horários mais críticos com base em intervalos específicos (0-6h, 6-12h, 12-18h, 18-24h).
Pontos Fortes
Interatividade: O dashboard permite uma análise detalhada e interativa, facilitando a visualização dos dados de várias perspectivas.
Insights Valiosos: A classificação por criticidade e a análise temporal proporcionaram insights importantes sobre os períodos e locais com maior incidência de acidentes.
Mapas Interativos: A utilização de mapas ajudou a identificar padrões geográficos de acidentes.
Pontos Fracos
Qualidade dos Dados: A qualidade dos dados impactou a análise, especialmente com registros incompletos ou inconsistentes em alguns campos.
Performance: A grande quantidade de dados e cálculos complexos afetaram a performance do Power BI em algumas situações.
Detalhamento de Dados: Alguns dados detalhados, como causas dos acidentes, não estavam disponíveis, limitando a profundidade da análise.
Conclusão
Este projeto foi uma excelente oportunidade para aplicar e aprimorar minhas habilidades em Power BI, transformando dados brutos em insights valiosos. Agradeço à equipe do Empowerdata pelo desafio e pela oportunidade de demonstrar minha capacidade analítica e técnica.

Se você tiver interesse em ver mais detalhes sobre este projeto ou discutir possíveis colaborações, sinta-se à vontade para entrar em contato!
