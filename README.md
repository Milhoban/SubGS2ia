# SubGS2ia
##Alunos:

- Benjamim Lucas Rodrigues Gonçalo - RM96026 - 3ECR
- Ingrydh Santos Potter - RM94731 - 3ECA
- Vitor de Andrade Ferreira Dias – RM957132 - 3ECR


# Análise de Dados de Veículos Elétricos em Washington

## 1. Descrição do Problema

Este projeto aborda a crescente necessidade de entender o mercado de veículos elétricos (VEs) e identificar oportunidades para promover sua adoção, como parte dos esforços para um transporte mais sustentável. A adoção de VEs ainda enfrenta desafios como preços elevados, autonomia limitada e infraestrutura de recarga. Este estudo visa analisar dados de VEs em Washington para obter insights sobre o mercado e fornecer recomendações para grupos de defesa.

## 2. Metodologia

**2.1 Coleta de Dados:**

O conjunto de dados "Electric_Vehicle_Population_Data.csv" foi usado como base para a análise. Este conjunto de dados contém informações sobre VEs registrados em Washington, incluindo localização, marca, modelo, tipo de veículo, elegibilidade para incentivos e outros atributos.

**2.2 Pré-processamento de Dados:**

- Limpeza de dados: Linhas com valores ausentes foram removidas para garantir a qualidade dos dados.
- Extração de coordenadas: A latitude e longitude foram extraídas da coluna "Vehicle Location" para permitir análises geográficas.
- Engenharia de atributos: Novas colunas foram criadas para enriquecer a análise:
    - "Location": Combina condado, cidade e estado para uma representação geográfica mais completa.
    - "Price_Range_Category": Categoriza os veículos em faixas de preço (Baixa, Média, Alta, Desconhecida).
    - "Electric_Range_Category": Categoriza os veículos por autonomia (Curta, Média, Longa, Desconhecida).

**2.3 Análise Exploratória de Dados (EDA):**

- Distribuições de frequência: Foram analisadas as distribuições de variáveis-chave, como localização, marca, modelo, tipo de veículo e elegibilidade para incentivos.
- Visualizações geográficas: Mapas foram gerados para visualizar a distribuição espacial dos VEs e identificar áreas de concentração.
- Relações entre variáveis: Foram exploradas relações entre variáveis como alcance elétrico, preço e elegibilidade para incentivos.

**2.4 Ferramentas:**

- Python com bibliotecas como Pandas, Matplotlib, Seaborn e Plotly foram usados para análise e visualização de dados.

## 3. Resultados

**3.1 Distribuição Geográfica:**

- A maioria dos VEs está concentrada em áreas urbanas, principalmente em Seattle e King County.
- Há potencial para expandir a adoção de VEs em outros condados e cidades.

**3.2 Marcas e Modelos:**

- Tesla é a marca dominante, seguida por Nissan e Chevrolet.
- Os modelos mais populares são Tesla Model 3 e Model Y.
- Há uma oportunidade de promover a diversidade de marcas e modelos.

**3.3 Elegibilidade para Incentivos:**

- Uma parte significativa dos VEs é elegível para incentivos CAFV.
- É importante coletar dados sobre o alcance da bateria para determinar a elegibilidade.

**3.4 Faixa de Preço:**

- Muitos VEs têm preços base desconhecidos.
- Há uma necessidade de mais transparência nos preços e incentivos para opções acessíveis.

**3.5 Utilitários Elétricos:**

- Puget Sound Energy Inc. é o principal fornecedor de energia para VEs.
- A colaboração com empresas de energia é crucial para expandir a infraestrutura de recarga.


## 4. Conclusões e Recomendações

**4.1 Conclusões:**

- O mercado de VEs em Washington está crescendo, mas concentrado em áreas urbanas.
- A Tesla domina o mercado, mas há espaço para outras marcas e modelos.
- A elegibilidade para incentivos e a faixa de preço são fatores importantes na adoção.
- A infraestrutura de recarga precisa ser expandida.

**4.2 Recomendações:**

- **Para grupos de defesa de VEs:**
    - Focar em áreas urbanas com potencial de crescimento.
    - Promover a diversidade de marcas e modelos.
    - Defender políticas que incentivem a adoção de VEs, como incentivos fiscais e expansão da infraestrutura de recarga.
    - Colaborar com concessionárias e empresas de energia para educar os consumidores sobre os benefícios dos VEs.

- **Para o governo:**
    - Implementar políticas que promovam a adoção de VEs.
    - Investir em infraestrutura de recarga pública.
    - Apoiar a pesquisa e desenvolvimento de tecnologias de
