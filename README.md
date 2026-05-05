# **Tech Challenge (Fase 01) – NPS Preditivo para E-commerce**  

### Pós-Tech IA Scientist

---

### 👥 **Integrantes do Grupo**

- **Ana Beatriz Porto Pereira** - RM 372544
- **Cristiane Marina de Oliveira** - RM 373841
- **Felipe Nadal de Oliveira** - RM 372547 
- **Leonardo Neves de Carvalho** - RM 372394
- **Rafael Maia Frenhe** - RM 370271

---

## 🎯 **Objetivo do Projeto**

> **Transformar dados operacionais em decisões de negócio**

Este projeto analisa a experiência do cliente em um e-commerce a partir de dados reais de **pedidos, logística e atendimento**, com foco em compreender quais fatores operacionais realmente influenciam o **Net Promoter Score (NPS)**.

A análise parte de uma provocação central do negócio:

 ```Por que clientes submetidos a operações aparentemente semelhantes avaliam a experiência de forma tão diferente?```

A partir dessa questão, o projeto busca:

- Identificar processos que antecedem a insatisfação do cliente  
- Permitir atuação **proativa**, antes da aplicação da pesquisa de NPS  
- Priorizar ações com maior impacto na experiência do cliente  

Mais do que mensurar satisfação, o foco está em:

- ✅ Traduzir dados operacionais em insights executivos  
- ✅ Apoiar decisões estratégicas baseadas em evidências  
- ✅ Conectar análise de dados à geração de valor para o negócio  

Os resultados apoiam decisões nas áreas de:

- 📦 Logística  
- 💬 Atendimento  
- 🛍️ Produto & Experiência  
- 📊 Estratégia  

---

## 📂 **Descrição da Base de Dados**

A base de dados utilizada reúne informações históricas de um cenário de e-commerce, contemplando diferentes etapas da jornada do cliente, desde a realização do pedido até o pós-venda.

Ela é composta por variáveis relacionadas a:

- **Dados do cliente** (idade, região, tempo de relacionamento)
- **Informações do pedido** (valor, quantidade de itens, descontos, forma de pagamento)
- **Indicadores logísticos** (tempo de entrega, atrasos, tentativas de entrega, frete)
- **Interações com o atendimento** (contatos, tempo de resolução, reclamações)
- **Indicadores internos de negócio**
- **Nota de satisfação do cliente** (Net Promoter Score – NPS)

A base permite analisar a experiência do cliente de forma integrada, conectando aspectos operacionais à percepção de satisfação.

---

## 🔍 **Metodologia Utilizada**


A metodologia adotada neste projeto é baseada no **CRISP-DM (Cross Industry Standard Process for Data Mining)**, um contexto de análise orientada a negócio e geração de insights.

As etapas consideradas foram:

- ```Entendimento do Negócio```  
  Compreensão do contexto do e-commerce, da importância do NPS e das principais dores relacionadas à experiência do cliente

- ```Entendimento dos Dados```  
  Análise inicial da base de dados, avaliação das variáveis disponíveis e entendimento de como os dados representam a jornada do cliente

- ```Preparação dos Dados```  
  Tratamento da base de dados, organização das informações para análise, criação de feature, exploração dos dados com foco em identificar padrões, relações e possíveis pontos de ruptura que impactam a satisfação do cliente

- ```Modelagem```  
  Reflexão sobre abordagens analíticas e preditivas que poderiam ser utilizadas para antecipar o NPS, considerando aspectos técnicos e de negócio

- ```Avaliação e Interpretação```  
  Interpretação dos resultados sob a ótica do negócio, priorizando insights acionáveis em detrimento de complexidade técnica

---

## 🔁 **Organização do Projeto**

```
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         case_nps and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── setup.cfg          <- Configuration file for flake8
```

---

## 🔁 **Como Reproduzir os Resultados**

Para reproduzir as análises deste projeto, siga os passos abaixo:

- Clone o repositório do GitHub
- Garanta que o arquivo de dados esteja disponível na pasta `data/`
- Instale as bibliotecas necessárias (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Acesse a pasta `notebooks/`
- Execute o notebook principal de forma sequencial, do início ao fim
- Executar pelo Google Colab (Jupyter Notebook)

<br>

> **Toda a estrutura do projeto foi organizada para permitir que qualquer pessoa consiga compreender e reproduzir a análise de forma simples e transparente**