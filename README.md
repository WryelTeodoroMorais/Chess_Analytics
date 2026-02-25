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
git clone https://github.com/WryelTeodoroMorais/Chess_Analytics.git
cd Chess_Analytics
```

### 2. Configure o Ambiente

**Crie um ambiente virtual:**
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

### 3. Execute a Análise no VS Code

Com as dependências instaladas, siga os passos abaixo:

1. **Abra o arquivo no VS Code:**
   - Abra a pasta do projeto no VS Code
   - Localize e abra o arquivo `Chess_Analytics.ipynb`

2. **Selecione o Kernel Python:**
   - Na parte superior direita do notebook, clique em "Select Kernel"
   - Escolha a opção de Python que corresponde ao seu ambiente virtual `.venv`
  
3. **Execute as Células:**
   - Clique no botão ▶ (play) que aparece ao lado de cada célula para executar
   - Ou use o atalho `Ctrl+Enter` para executar a célula atual
  