# Análise de Performance - Chess.com

Este projeto realiza uma análise detalhada da performance de jogadores no Chess.com utilizando a API pública da plataforma. Ele processa dados de partidas para gerar estatísticas e visualizações sobre taxas de vitória por cor (pretas/brancas), aberturas mais utilizadas e evolução de rating.

## 🚀 Funcionalidades

- **Requisição de Dados:** Busca automática de históricos de partidas via API do Chess.com.
- **Tratamento de Dados:** Processamento com Pandas para extrair resultados, ratings, aberturas e modos de jogo.
- **Estatísticas Gerais:** Total de jogos, vitórias, derrotas, empates, rating atual e maior rating.
- **Visualização:**
  - Gráfico de pizza com taxas de vitória globais.
  - Comparação de performance entre peças brancas e pretas.
  - Top 10 aberturas mais jogadas.

## 🛠️ Tecnologias Utilizadas

- **Pandas:** Manipulação e análise de dados.
- **Matplotlib:** Geração de gráficos.
- **Requests:** Consumo da API do Chess.com.
- **Jupyter Notebook:** Ambiente de desenvolvimento e execução.

## 📋 Como Executar

### 1. Clone o Repositório
```bash
git clone https://github.com/WryelTeodoroMorais/chess-analytics.git
cd chess-analytics
```

### 2. Configure o Ambiente
Recomenda-se o uso de um ambiente virtual (.venv).

```bash
# Criar ambiente virtual
python -m venv .venv

# Ativar ambiente virtual no Linux/MacOS:
source .venv/bin/activate

# Ativar ambiente virtual no Windows:
.venv\Scripts\activate

# Instalar dependências
pip install -r requirements.txt
```

### 3. Execute a Análise
Com as dependências instaladas, abra o Jupyter Notebook para visualizar os resultados:

```bash
jupyter notebook Chess_Analytics.ipynb
```