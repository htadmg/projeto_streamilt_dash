# Dashboard de Vendas

## Descrição do Projeto
Este projeto é um **Dashboard de Vendas** desenvolvido com **Streamlit**, **Python** e **Plotly**. Ele permite a visualização de métricas de vendas como receita total, quantidade de vendas, e dados filtrados por vendedores. Além disso, oferece gráficos interativos para análise detalhada de categorias de produtos, receita por estado e desempenho de vendedores.

## Funcionalidades
- Visualização da receita total e quantidade de vendas.
- Gráficos interativos para acompanhar a receita por estado e por mês.
- Análise de vendas e receita por vendedores.
- Filtros dinâmicos para selecionar vendedores, categorias de produtos e faixa de preço.
- Exportação de dados filtrados para arquivo CSV.

## Tecnologias Utilizadas
- **Streamlit**: Framework para construção de aplicações web interativas.
- **Python**: Linguagem de programação utilizada para manipulação de dados e construção da aplicação.
- **Plotly**: Biblioteca utilizada para criar gráficos interativos.
- **Pandas**: Utilizada para manipulação de dados e agrupamento de informações.
- **JSON**: Utilizado para carregar o conjunto de dados inicial.

## Estrutura do Projeto
```
├── app.py              # Arquivo principal da aplicação
├── dataset.py          # Manipulação do dataset
├── graficos.py         # Configuração dos gráficos
├── utils.py            # Funções utilitárias
├── dados/              # Pasta com os dados (vendas.json)
├── requirements.txt    # Dependências do projeto
└── README.md           # Este arquivo
```

## Como Configurar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
```bash
git clone https://github.com/htadmg/projeto_streamilt_dash.git
```
- Usando HTTPS:
```bash
git clone https://github.com/htadmg/dashboard_com_dash.git
```
- Usando SSH:
```bash
git clone git@github.com:htadmg/projeto_streamilt_dash.git
```
- Navegue até o diretório do projeto:
```bash
cd .\projeto_streamilt_dash
```
2. **Crie e Ative um Ambiente Virtual (opcional, mas recomendado)**
- **Para Linux/MacOS:**
```bash
python -m venv .venv
source venv/bin/activate
```
 
- **Para Windows:**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```   
3. **Instale as dependências**
```bash
pip install -r requirements.txt
```

### Iniciar o Servidor de Desenvolvimento

Inicie o servidor de desenvolvimento com o comando:

```bash
streamlit run app.py
```
### Acessar o Projeto
Abra um navegador e vá para http://localhost:8501 para ver o aplicativo em funcionamento.
