# Análise de Tendências de Preços de Produtos com Web Scraping

## Descrição
Este projeto tem como objetivo coletar dados de preços de um produto específico em sites de e-commerce, realizar tratamento e análise dos dados e apresentar visualmente tendências e variações de preço.  
A aplicação utiliza **Python** para coleta, processamento e visualização dos dados.

## Objetivos
- Coletar preços de um produto escolhido por meio de **web scraping**.
- Tratar e organizar os dados coletados.
- Gerar estatísticas descritivas e gráficos para análise de tendências.
- Apresentar um relatório final com os resultados obtidos.

## Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** BeautifulSoup, Requests, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
- **Controle de Versão:** Git e GitHub

## Estrutura do Projeto
```
├── src/               # Scripts de coleta e processamento
├── notebooks/         # Jupyter Notebooks com análises
├── data/              # Arquivos CSV ou JSON com dados coletados
├── README.md          # Documentação do projeto
└── requirements.txt   # Dependências do Python
```

## Como Executar
1. **Clone este repositório:**
   ```bash
   git clone https://github.com/Vinicius-eng20/projeto-analise-precos.git
   cd projeto-analise-precos
   ```

2. **Crie e ative um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute o script de coleta:**
   ```bash
   python src/coleta_dados.py
   ```

5. **Abra o Jupyter Notebook para análise:**
   ```bash
   jupyter notebook notebooks/analise.ipynb
   ```

## Resultados Esperados
- Estatísticas de preços (mínimo, máximo, média).
- Gráficos de evolução dos preços.
- Relatório final em Jupyter Notebook com conclusões.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
