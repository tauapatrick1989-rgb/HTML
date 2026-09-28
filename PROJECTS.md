# Estrutura dos projetos de portfólio

Este documento define o padrão para os próximos projetos de Data Analytics do portfólio.

## Estrutura recomendada

```text
nome-do-projeto/
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── dashboards/
├── images/
├── requirements.txt
└── .gitignore
```

> Bases grandes, confidenciais ou com restrições de uso não devem ser versionadas no GitHub. Nesses casos, o README deve explicar a origem dos dados e como reproduzir o projeto.

## Padrão do README de cada projeto

### 1. Contexto
Explique o problema em linguagem de negócio.

### 2. Objetivo
Defina o que a análise pretende responder ou melhorar.

### 3. Dados
Informe fonte, período, principais campos e limitações.

### 4. Tratamento
Documente limpeza, padronização, transformações e critérios adotados.

### 5. Análise
Mostre perguntas, indicadores, consultas e raciocínio analítico.

### 6. Visualização
Inclua dashboards, gráficos ou telas relevantes.

### 7. Principais conclusões
Liste somente conclusões sustentadas pelos dados.

### 8. Tecnologias
Exemplo: Python, Pandas, SQL, Power BI, Looker Studio, BigQuery.

### 9. Como executar
Inclua instruções curtas para reproduzir o projeto quando aplicável.

### 10. Próximos passos
Registre melhorias planejadas sem apresentar funcionalidades futuras como já concluídas.

## Projetos prioritários

### Projeto 1 — Análise operacional e KPIs
Construir um case de análise de desempenho operacional com indicadores, tratamento de dados e dashboard.

**Objetivo de portfólio:** demonstrar capacidade de transformar dados operacionais em métricas e decisões.

### Projeto 2 — Pipeline simples de dados
Extrair dados de CSV, planilha ou API, tratar com Python/SQL e disponibilizar uma base pronta para análise.

**Objetivo de portfólio:** demonstrar coleta, tratamento, qualidade e organização de dados.

### Projeto 3 — Dashboard analítico
Criar uma visualização com perguntas de negócio claras, indicadores, filtros e conclusões.

**Objetivo de portfólio:** demonstrar BI, storytelling e comunicação.

### Projeto 4 — Automação + análise
Automatizar uma rotina de coleta, consolidação ou geração de relatório.

**Objetivo de portfólio:** conectar sua experiência em processos ao novo posicionamento em dados.

## Critério para publicar um projeto

Um projeto só deve entrar como destaque no perfil quando tiver:

- README completo;
- objetivo claro;
- dados ou fonte documentados;
- código organizado;
- resultados reproduzíveis quando possível;
- imagens ou dashboard;
- conclusões;
- ausência de dados confidenciais;
- linguagem própria e objetiva.

A prioridade é qualidade e clareza, não quantidade de repositórios.
