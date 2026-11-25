# 🚕 Análise de Mobilidade Urbana: Estratégia e Impacto Climático em Chicago

## 1. Objetivo do Projeto
Análise do mercado de transporte por táxi em Chicago através da integração de dados extraídos via SQL e processados em Python. O estudo visa identificar as empresas líderes em volume de viagens, mapear os principais destinos urbanos e testar a hipótese de impacto das condições meteorológicas na duração dos trajetos entre o centro (Loop) e o Aeroporto Internacional O'Hare.

## 2. Resultado
- **Identificação de Líderes**: Mapeamento das empresas de táxi com maior quota de mercado em volume de corridas.
- **Hotspots de Destino**: Determinação dos 10 bairros de Chicago com maior frequência de desembarque, fornecendo dados para otimização de frotas.
- **Validação Estatística do Clima**: Verificação de que a duração média das viagens para o aeroporto sofre alterações significativas em sábados chuvosos, permitindo uma melhor previsão de tempo de percurso para os usuários.
- **Consolidação de Dados**: Entrega de um relatório analítico que une métricas operacionais e variáveis externas (meteorologia).

## 3. Ferramentas Utilizadas
- **Linguagem**: Python
- **Bibliotecas**: Pandas (Tratamento de dados), Matplotlib e Seaborn (Visualização de dados), SciPy.stats (Execução de testes estatísticos).
- **Extração de Dados**: SQL (Consultas avançadas para geração da base de análise).
- **Ambiente de Desenvolvimento**: VS Code.

## 4. O que Aprendi (Evidências Técnicas)
- **Integração SQL-Python**: Execução da etapa final de processamento de dados a partir de tabelas consolidadas via consultas SQL complexas.
- **Análise de Frequência e Distribuição**: Criação de visualizações gráficas para identificar o "Top 10" destinos, facilitando a interpretação de volumes de tráfego.
- **Tratamento de Variáveis Temporais**: Conversão e manipulação de objetos datetime para filtragem específica de corridas aos sábados.
- **Aplicação de Testes de Hipóteses**: Formulação de hipóteses nula ($H_0$) e alternativa ($H_1$) e aplicação do Teste t de Student para amostras independentes, avaliando a diferença de médias de tempo sob diferentes condições climáticas.

## 5. Melhorias Futuras
- **Análise de Sazonalidade**: Expansão da base de dados para incluir meses de inverno rigoroso em Chicago, avaliando o impacto da neve na mobilidade.
- **Visualização Geoespacial**: Implementação de mapas de calor (Heatmaps) utilizando bibliotecas como Folium ou Geopandas para visualização das rotas mais rápidas.
- **Previsão de Tarifas**: Desenvolvimento de modelos de regressão para estimar o custo das viagens com base na duração média e nas condições de tráfego.
