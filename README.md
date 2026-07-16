# miniguia-estudos-notebooklm
Caderno temático sobre finanças e investimentos no NotebookLM — desafio DIO
# 📘 Caderno Temático no NotebookLM: Introdução ao Mercado Financeiro e Investimentos

## 🎯 Contexto e Objetivos

Este projeto foi desenvolvido como parte do desafio "IA Generativa com NotebookLM" da DIO. O objetivo é criar um **caderno temático** no NotebookLM sobre **finanças e investimentos**, utilizando **aprendizagem ativa com IA**.

### Objetivos de estudo

- Compreender os fundamentos da educação financeira (orçamento, poupança, investimento).
- Entender o funcionamento do mercado de capitais brasileiro (regulação, bolsa, títulos públicos).
- Conhecer os princípios do investimento em valor (*Value Investing*).
- Desenvolver habilidades práticas para tomar decisões financeiras conscientes.
- Criar um repositório de prompts reutilizáveis para revisões futuras.

---

## 📚 Curadoria de Fontes (5 fontes selecionadas)

Foram selecionadas **5 fontes abertas** que combinam material institucional oficial e literatura clássica:

| # | Título / Fonte | Tipo | Formato | Motivo de Inclusão |
|---|----------------|------|---------|---------------------|
| 1 | Banco Central do Brasil – Caderno de Cidadania Financeira | Instituição Oficial | PDF | Educação financeira prática (orçamento, poupança, investimento). |
| 2 | CVM – Portal do Investidor | Instituição Oficial | HTML | Orientações isentas sobre regulação e investimentos. |
| 3 | B3 – B3 Educação | Instituição Oficial | HTML | Cursos gratuitos sobre finanças e mercado de capitais. |
| 4 | Tesouro Direto – Guia Oficial | Instituição Oficial | HTML | Títulos públicos, investimento de baixo risco. |
| 5 | O Investidor Inteligente – Benjamin Graham | Livro Clássico | PDF | Pilar do Value Investing; conceito de margem de segurança. |

> **Nota:** Embora eu tenha uma lista maior de 50 fontes (disponível em `fontes/links_fontes.txt`), para este caderno temático foquei nas 5 mais representativas para um estudo introdutório, conforme orientação do desafio.

---

## 🔧 Engenharia de Prompts e "Cicatrizes"

### Perguntas estratégicas elaboradas

| # | Pergunta | Objetivo |
|---|----------|----------|
| 1 | "O que é a margem de segurança segundo Benjamin Graham?" | Extrair conceito central do Value Investing. |
| 2 | "Quais as diferenças entre poupança e investimento?" | Comparar conceitos fundamentais. |
| 3 | "Como funciona o Tesouro Direto?" | Entender investimento em títulos públicos. |
| 4 | "Qual o papel da CVM e da B3?" | Compreender regulação e mercado. |

### Testes de prompts e ajustes

#### Teste 1 – Prompt original
> *"Explique o conceito de margem de segurança de Benjamin Graham."*

**Resposta:** Conceito claro, mas sem citação de página.

**Ajuste:** Adicionei *"cite a fonte com página e parágrafo"*.

---

#### Teste 2 – Prompt com exigência de citação
> *"Com base no PDF do livro 'O Investidor Inteligente', explique a margem de segurança e cite a página."*

**Resposta:** Resposta com citação precisa (Capítulo 20, p. 215).

**Aprendizado:** Especificar a fonte e pedir citação melhora a rastreabilidade.

---

#### Teste 3 – Prompt comparativo
> *"Compare os conceitos de investimento do Banco Central com a visão de Benjamin Graham."*

**Resposta:** Síntese comparativa entre as duas fontes.

**Dificuldade:** Inicialmente veio só a visão do BC; precisei reforçar *"compare com Graham"*.

---

#### Teste 4 – Prompt com formato definido
> *"Liste em tópicos os 5 principais ensinamentos do Tesouro Direto para iniciantes."*

**Resposta:** Lista objetiva com dados extraídos do site.

**Aprendizado:** Especificar o formato (*"liste em tópicos"*) organiza a resposta.

---

## 📖 Miniguia de Estudo

### Resumos estruturados

#### 1. Educação Financeira (Banco Central)
O Caderno de Cidadania Financeira aborda:
- Relação com o dinheiro e hábitos financeiros.
- Gestão de orçamento e controle de gastos.
- Diferença entre poupança e investimento.
- Prevenção a riscos e fraudes.

#### 2. Mercado de Capitais e Regulação (CVM + B3)
- **CVM:** Regula o mercado; oferece guias e o Portal do Investidor.
- **B3:** Bolsa de valores; mantém a plataforma B3 Educação com cursos gratuitos.

#### 3. Tesouro Direto
- Programa do Tesouro Nacional para pessoas físicas.
- Tipos: Tesouro Selic, IPCA e Prefixado.
- Investimento mínimo: R$ 30,00.
- Taxa de custódia: 0,2% a.a. (isenção para Tesouro Selic até R$ 10.000,00).

#### 4. Value Investing (Benjamin Graham)
- **Margem de segurança:** comprar abaixo do valor intrínseco.
- **Investidor defensivo vs. empreendedor:** diferentes perfis de risco.
- **Análise fundamentalista:** foco em balanços e lucros.
- **Longo prazo:** evitar especulação.

---

### Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **Margem de segurança** | Diferença entre preço de mercado e valor intrínseco; quanto maior, menor o risco. |
| **Value Investing** | Estratégia de comprar ativos subvalorizados com base em análise fundamentalista. |
| **Tesouro Direto** | Programa de venda de títulos públicos federais a pessoas físicas. |
| **Selic** | Taxa básica de juros da economia brasileira. |
| **IPCA** | Índice de inflação oficial do Brasil. |
| **CVM** | Comissão de Valores Mobiliários — órgão regulador. |
| **B3** | Brasil, Bolsa, Balcão — bolsa de valores oficial. |

---

### Prompts Reutilizáveis

| # | Prompt |
|---|--------|
| 1 | *"Explique o conceito de [termo] com base nas fontes carregadas, citando o documento e a página."* |
| 2 | *"Compare a visão de [autor A] com a de [autor B] sobre [tema]."* |
| 3 | *"Liste em tópicos os principais pontos sobre [tema] extraídos das fontes."* |
| 4 | *"Com base no PDF [título], descreva [tema] e cite a página e o parágrafo."* |
| 5 | *"Simule um investimento de R$ X em [ativo] por Y meses, considerando as regras da fonte."* |

---

## 📂 Estrutura do Repositório
