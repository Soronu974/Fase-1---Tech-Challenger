# Fase-1---Tech-Challenger

# Análise dos Fatores que Influenciam a Satisfação dos Clientes em um E-commerce

## 📌 Objetivo do Projeto

Este projeto tem como objetivo identificar os principais fatores que influenciam a satisfação dos clientes em um e-commerce, utilizando o **Net Promoter Score (NPS)** como principal indicador de desempenho.

Por meio de uma Análise Exploratória dos Dados (EDA), busca-se compreender como características relacionadas aos clientes, pedidos, logística e atendimento impactam o NPS, gerando insights que possam apoiar a tomada de decisão e contribuir para a melhoria da experiência do cliente.

---

## 📊 Descrição da Base de Dados

A base de dados utilizada contém informações históricas de pedidos realizados por clientes de um e-commerce.

Ela é composta por **2.500 registros** e **19 variáveis**, incluindo informações como:

- Dados dos clientes (idade, região e tempo de relacionamento);
- Informações dos pedidos (valor, quantidade de itens, descontos e parcelamento);
- Dados logísticos (tempo de entrega, atraso, valor do frete e tentativas de entrega);
- Dados de atendimento (quantidade de contatos, tempo de resolução e número de reclamações);
- Indicadores de negócio (CSAT e recompra em até 30 dias);
- Nota do **Net Promoter Score (NPS)**.

A variável de interesse do projeto é:

- **nps_score:** nota de satisfação atribuída pelo cliente ao final da experiência de compra.

---

## 🛠️ Metodologia Utilizada

O desenvolvimento do projeto foi dividido nas seguintes etapas:

### 1. Entendimento do Negócio

Foi realizada uma análise do contexto do problema, buscando compreender a importância do NPS para o e-commerce e identificar quais áreas da empresa poderiam se beneficiar dos resultados.

### 2. Definição da Variável-Alvo

Foi definido o **NPS (nps_score)** como variável que representa a satisfação do cliente, sendo o principal indicador analisado durante o projeto.

### 3. Tratamento e Preparação dos Dados

Nesta etapa foram realizados:

- Importação da base de dados;
- Verificação da estrutura do conjunto de dados;
- Criação da classificação dos clientes em:
  - Promotores;
  - Neutros;
  - Detratores.

### 4. Análise Exploratória dos Dados (EDA)

Foram realizadas análises com o objetivo de identificar padrões e relações entre as variáveis e o NPS, incluindo:

- Distribuição dos clientes por categoria de NPS;
- Distribuição de pedidos por região;
- Correlação entre as variáveis numéricas e o NPS;
- Relação entre número de reclamações e satisfação do cliente;
- Identificação dos principais fatores associados ao aumento do NPS.

### 5. Geração de Insights

A partir das análises, foram identificados os fatores que mais impactam a satisfação dos clientes e elaboradas recomendações para apoiar decisões estratégicas da empresa.

---

## 📈 Principais Insights

A análise exploratória permitiu observar que:

- O atraso na entrega está entre os principais fatores associados à redução do NPS.
- Clientes com maior número de reclamações tendem a apresentar menor satisfação.
- Um maior número de contatos com o atendimento está relacionado a experiências mais negativas.
- Clientes com maior satisfação apresentam maior probabilidade de realizar uma nova compra.
- A logística e o atendimento mostraram-se os principais pilares para melhoria da experiência do cliente.

---

## 💻 Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ Como Reproduzir os Resultados

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/nps-ecommerce.git
```

### 2. Acesse a pasta do projeto

```bash
cd nps-ecommerce
```

### 3. Instale as dependências

```bash
pip install pandas matplotlib seaborn jupyter
```

### 4. Adicione a base de dados

Coloque o arquivo

```
desafio_nps_fase_1.csv
```

na mesma pasta do notebook.

### 5. Execute o notebook

Abra o Jupyter Notebook e execute o arquivo:

```
01_analise_nps.ipynb
```

Todas as etapas da análise poderão ser reproduzidas seguindo a ordem das células do notebook.

---

## 📁 Estrutura do Projeto

```
.
├── desafio_nps_fase_1.csv
├── 01_analise_nps.ipynb
├── README.md
└── apresentacao/
    └── Fase_1_Tech_Challenger.pptx
```

---

## 👨‍💻 Autor

**Gabriell Soriano**

Projeto desenvolvido como parte do desafio técnico **Tech Challenger**, com foco na análise de fatores que influenciam a satisfação de clientes em um e-commerce por meio de técnicas de Análise Exploratória de Dados (EDA).
