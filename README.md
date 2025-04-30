# 📊 Análise Estatística de Jogadores da NBA

Este projeto realiza uma análise exploratória simples de estatísticas de jogadores da NBA com o uso de Python e bibliotecas de ciência de dados, como `pandas`.

## 📝 Descrição

A análise é baseada em um conjunto de dados contendo estatísticas totais dos jogadores da NBA. O notebook percorre etapas como:

- Carregamento e visualização inicial dos dados
- Verificação de valores ausentes
- Remoção de colunas nulas
- Verificação e tratamento de duplicatas
- Análise descritiva (como contagem de jogadores únicos, médias de pontos, rebotes etc.)
- Filtros por jogador específico (ex.: Gui Santos)

## 📂 Estrutura do Projeto

- `main.ipynb`: Notebook com todo o processo de análise.
- `player_totals.csv`: Base de dados utilizada na análise (não incluída neste repositório).

## 📊 Etapas da Análise

1. **Importação de bibliotecas e dados**
2. **Visualização de registros específicos**
3. **Limpeza de dados**:
   - Exclusão de colunas nulas
   - Checagem de duplicatas
4. **Análise descritiva**:
   - Quantidade de jogadores únicos
   - Estatísticas gerais (médias, totais, máximos, mínimos)
   - Comparações específicas

## 💡 Requisitos

- Python 3.8+
- Pandas

Você pode instalar os requisitos com:

```bash
pip install pandas
```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/nba-stats-analysis.git
   cd nba-stats-analysis
   ```
2. Certifique-se de que o arquivo `player_totals.csv` está presente no mesmo diretório.
3. Execute o notebook `main.ipynb` em um ambiente Jupyter.
