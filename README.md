# Radar Público
### Plataforma de Análise de Dados Governamentais e Identificação de Padrões Contratuais

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/python-3.x-blue)
![Data Analysis](https://img.shields.io/badge/data-analysis-green)
![Government Data](https://img.shields.io/badge/government-open%20data-lightgrey)

## Sobre o Projeto

O **Radar Público** é um sistema de análise de dados voltado para o processamento, organização e interpretação de bases públicas governamentais, com foco na identificação de padrões, inconsistências e indicadores relevantes em contratos administrativos.

O projeto foi desenvolvido com o objetivo de transformar grandes volumes de dados públicos em informações estruturadas, facilitando análises exploratórias, cruzamento de informações e apoio à tomada de decisão baseada em dados.

A proposta é evoluir continuamente a plataforma para incorporar automações, análise estatística, mecanismos inteligentes de identificação de anomalias e visualização de dados.

---

## Objetivos do Projeto

- Processar grandes volumes de dados públicos;
- Automatizar limpeza e padronização de informações;
- Identificar padrões contratuais;
- Detectar possíveis inconsistências e anomalias;
- Facilitar análise exploratória de dados governamentais;
- Estruturar indicadores analíticos para apoio à interpretação de informações públicas.

---

## Funcionalidades

### Processamento de Dados
- Importação de bases CSV/XLSX;
- Tratamento e limpeza de dados;
- Normalização de campos;
- Padronização de informações.

### Análise de Dados
- Cruzamento de informações contratuais;
- Identificação de padrões operacionais;
- Geração de indicadores;
- Filtragem e segmentação de dados.

### Automação
- Processamento automatizado de arquivos;
- Estruturação de dados para análise;
- Geração de relatórios analíticos.

### Evoluções Futuras
- Dashboard interativo;
- Detecção de anomalias com IA;
- Score de risco contratual;
- Sistema de alertas;
- Visualização gráfica avançada.

---

## Arquitetura do Projeto

```text
Entrada de Dados (CSV/XLSX)
            ↓
Pré-processamento
(Limpeza e Padronização)
            ↓
Motor de Análise
(Cruzamento e Regras)
            ↓
Indicadores Analíticos
            ↓
Relatórios e Insights
```

---

## Estrutura do Projeto

```text
radar-publico/
│
├── data/               # Bases de dados
├── docs/               # Documentação
├── images/             # Imagens e diagramas
├── src/                # Código-fonte
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Tecnologias Utilizadas

- Python
- Pandas
- OpenPyXL
- CSV / XLSX Processing
- Automação de Dados
- Estatística Aplicada
- Data Analysis

---

## Como Executar

### Clone o repositório

```bash
git clone https://github.com/davioa/radar-publico.git
cd radar-publico
```

### Crie um ambiente virtual

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Instale as dependências

```bash
pip install -r requirements.txt
```

### Execute o projeto

```bash
python src/analisar_governo.py
```

## Exemplo de Aplicação

O sistema pode ser utilizado para:

- análise de contratos administrativos;
- consolidação de bases públicas;
- exploração de dados governamentais;
- identificação de padrões operacionais;
- apoio à análise de informações públicas.

---

## Roadmap do Projeto

### Fase 1 – Base Analítica
- [x] Estrutura inicial do projeto
- [x] Processamento de arquivos
- [x] Leitura de dados públicos
- [ ] Padronização completa dos dados
- [ ] Regras analíticas iniciais

### Fase 2 – Inteligência Analítica
- [ ] Sistema de indicadores
- [ ] Identificação de padrões
- [ ] Score de risco

### Fase 3 – Evolução Inteligente
- [ ] Dashboard interativo
- [ ] Detecção de anomalias
- [ ] Integração com IA

---

## Aprendizados do Projeto

Este projeto tem contribuído para o desenvolvimento de competências em:

- análise de dados;
- automação;
- arquitetura de sistemas;
- processamento de grandes volumes de informação;
- desenvolvimento em Python;
- modelagem de soluções analíticas.

---

## Autor
**Davi Oliveira**  
Estudante de Análise e Desenvolvimento de Sistemas  
Interesses: automação, análise de dados, IA defensiva, sistemas inteligentes e segurança analítica.

---

⚠️ **Observação:** Este projeto possui caráter educacional, analítico e experimental, utilizando exclusivamente bases públicas e abertas.
