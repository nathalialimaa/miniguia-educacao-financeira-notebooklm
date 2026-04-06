# 💰 Miniguia de Estudos: Educação Financeira Básica com NotebookLM

> Projeto desenvolvido como parte do desafio prático da [DIO](https://www.dio.me/), explorando o uso do NotebookLM como ferramenta de aprendizagem ativa.

---

## 📌 Contexto e Objetivos

### Sobre o tema escolhido

Educação financeira é uma das habilidades mais importantes para a vida adulta, e uma das menos ensinadas nas escolas. Escolhi esse tema por ser iniciante no assunto e por querer construir uma base sólida antes de tomar decisões financeiras mais sérias.

### Objetivos de estudo

- Compreender os conceitos fundamentais de finanças pessoais (orçamento, poupança, dívidas, investimentos)
- Aprender a diferença entre ativos e passivos
- Entender como juros compostos funcionam na prática
- Criar um vocabulário financeiro básico para continuar aprendendo de forma independente
- Desenvolver o hábito de organizar e revisar conhecimento com auxílio de IA

---

## 📚 Curadoria de Fontes

Abaixo estão as 5 fontes abertas selecionadas e carregadas no NotebookLM. Todas são gratuitas e em português.

| # | Título | Fonte | Formato |
|---|--------|-------|---------|
| 1 | **Caderno de Educação Financeira – Gestão de Finanças Pessoais** | Banco Central do Brasil (BCB) | PDF |
| 2 | **Cartilha de Orientação Financeira** | Senado Federal | PDF |
| 3 | **Como Cuidar de Suas Finanças Pessoais** | Conselho Federal de Administração (CFA) | PDF |
| 4 | **Cartilha de Educação Financeira** | Fundação Banco do Brasil (FBB) | PDF |
| 5 | **Fundamentos de Educação Financeira** | Caixa Econômica Federal | PDF |

### Links para acesso

- 📄 [Banco Central do Brasil – Caderno de Educação Financeira](https://www.bcb.gov.br/pre/pef/port/caderno_cidadania_financeira.pdf)
- 📄 [Senado Federal – Cartilha de Orientação Financeira](https://www2.senado.leg.br/bdsf/bitstream/handle/id/509818/Orienta%C3%A7%C3%A3o%20Financeira.pdf)
- 📄 [Conselho Federal de Administração – Como Cuidar de Suas Finanças Pessoais](http://cfa.org.br/wp-content/uploads/2018/02/10cfa-cartilha-financa-pessoal.pdf)
- 📄 [Fundação Banco do Brasil – Cartilha de Educação Financeira](https://fbb.org.br/wp-content/uploads/2025/01/Cartilha-de-Educacao-Financeira-MUTS.pdf)
- 📄 [Caixa Econômica Federal – Fundamentos de Educação Financeira](https://www.caixa.gov.br/Downloads/educacao-financeira-cartilhas/CARTILHA1_EDUCACAO_FINANCEIRA.pdf)

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Esta seção documenta as perguntas feitas ao NotebookLM, as variações testadas, as respostas reais obtidas e as dificuldades encontradas.

---

### Prompt 1 – Mapeamento inicial do tema

**Pergunta:**
> "Com base nos documentos que carreguei, quais são os 5 conceitos mais importantes para quem está começando a aprender sobre educação financeira?"

**Resposta obtida:**
O NotebookLM identificou os 5 conceitos fundamentais:
1. **Orçamento Pessoal ou Familiar** – ferramenta que registra receitas e despesas com o objetivo de alcançar um saldo superavitário (receitas > despesas)
2. **Diferença entre Necessidades e Desejos** – essencial para o consumo consciente; confundir os dois conceitos é a principal causa de endividamento
3. **Reserva de Emergência e Poupança** – recomendada em pelo menos 1 mês de renda para cobrir imprevistos como doenças, reparos ou desemprego
4. **Uso Consciente do Crédito e Juros** – o crédito tem custo (juros compostos) e pode fazer dívidas pequenas crescerem exponencialmente
5. **Noções Básicas de Investimento** – avaliar todo investimento pelos três pilares: segurança, liquidez e rentabilidade; e conhecer o próprio perfil de investidor

**O que funcionou bem:** A ferramenta cruzou informações de múltiplas fontes e gerou uma lista coesa com referências.

**Dificuldade encontrada:** O prompt sem contexto de nível gerou respostas com vocabulário técnico demais. Adicionar "para quem está começando" foi essencial para calibrar a linguagem da resposta.

---

### Prompt 2 – Aprofundamento em juros compostos

**Pergunta (versão 1 – vaga):**
> "Me explique juros compostos."

**Resultado:** Explicação genérica, sem referência às fontes carregadas.

**Pergunta (versão 2 – refinada):**
> "Com base nos documentos carregados, como os juros compostos são explicados para leigos? Pode dar um exemplo prático com números?"

**Resposta obtida:**
- Diferença entre juros simples (incidem só sobre o valor inicial) e compostos (incidem sobre o valor acumulado a cada período)
- Efeito exponencial: uma taxa de 5% ao mês não equivale a 60% ao ano, mas a 79,6% ao ano
- Exemplo prático: uma dívida de R$ 1.000,00 a 5% ao mês chega a R$ 1.340,10 em 6 meses (nos juros simples seria R$ 1.300,00)
- Dado impactante das fontes: essa mesma dívida de R$ 1.000,00 se tornaria R$ 1.000.000,00 em menos de 24 anos se não fosse paga
- Exemplo positivo: um jovem que poupa R$ 150/mês por apenas 10 anos a partir dos 20 anos acumula o mesmo patrimônio que alguém que poupa por 30 anos a partir dos 30 — porque o tempo é o principal ingrediente dos juros compostos

**Lição aprendida:** Adicionar "para leigos" + "exemplo com números" + "com base nos documentos carregados" são os três modificadores que mais melhoraram a qualidade da resposta.

---

### Prompt 3 – Criação de glossário

**Pergunta:**
> "Liste todos os termos técnicos presentes nos documentos que um iniciante em finanças pode não conhecer. Para cada um, escreva uma definição simples em até 2 linhas."

**Resposta obtida:** Lista com 27 termos — Alavancagem, Amortização, Ativos, Câmbio, CDB, CET, Debêntures, Dividendos, FGC, Fluxo de Caixa, Inadimplência, Inflação, Insolvência, Liquidez, Margem Consignável, Oniomania, Passivos, Patrimônio Líquido, Pós-fixado, Prefixado, Renda Fixa, Renda Variável, Rentabilidade, Risco de Crédito, Selic, Tesouro Direto e Troca Intertemporal — todos com definições claras e referenciados nas fontes.

**Variação testada:**
> "Reescreva a definição de 'liquidez' como se estivesse explicando para uma criança de 12 anos."

**Resposta obtida após refinamento:**
> "Imagine que você tem um brinquedo muito legal e quer transformá-lo em dinheiro para comprar um jogo novo hoje mesmo. Se você conseguir vender esse brinquedo rapidinho e pegar o dinheiro na hora, ele tem alta liquidez. Mas se for um brinquedo difícil de vender e você tiver que esperar meses para achar um comprador, ele tem baixa liquidez. Quanto mais rápido o dinheiro 'corre' para o seu bolso quando você precisa, maior é a liquidez."

**Lição aprendida:** A técnica "explique como para uma criança de 12 anos" é um dos prompts mais eficazes para simplificar qualquer conceito técnico.

---

### Prompt 4 – Geração de resumo estruturado

**Pergunta:**
> "Crie um resumo estruturado em tópicos sobre como montar um orçamento pessoal, usando apenas as informações dos documentos carregados. Organize em: (1) O que é, (2) Por que fazer, (3) Como fazer passo a passo."

**Resposta obtida:**
O NotebookLM respeitou a estrutura pedida e organizou o conteúdo em 4 etapas práticas: (I) Planejamento — estimar receitas e despesas do mês seguinte; (II) Registro — anotar cada gasto diariamente; (III) Agrupamento — categorizar por alimentação, habitação, transporte, lazer, saúde; (IV) Avaliação e Ajuste — verificar se o saldo foi positivo e "pagar-se primeiro", separando a poupança antes de qualquer despesa.

**Resultado:** Foi o prompt mais efetivo de toda a sessão. A estrutura definida no prompt foi respeitada integralmente e o conteúdo foi fiel às fontes.

---

### Prompt 5 – Troubleshooting: quando a IA foi além das fontes

**Situação:**
> "Me informe os melhores investimentos para iniciantes."

O NotebookLM respondeu citando Caderneta de Poupança, Tesouro Direto e CDB, misturando conteúdo das fontes com conhecimento geral sem deixar isso claro.

**Solução encontrada:**
> "Responda apenas com informações presentes nos documentos que carreguei. Se a informação não estiver nas fontes, diga que não encontrou."

**Resposta após correção:** A IA passou a indicar claramente o que estava nas fontes — como o conceito dos três pilares (segurança, liquidez e rentabilidade) e o perfil conservador de investidor — e sinalizou ao final: *"estratégias específicas de investimento em renda variável ou detalhes sobre taxas Selic atuais não foram encontradas de forma detalhada nestas fontes."*

**Lição:** Sempre que o tema envolver dados específicos (taxas, rentabilidade, rankings), incluir a restrição "responda apenas com base nas fontes" é obrigatório para evitar alucinações.

---

## 📖 Miniguia de Estudo – Entrega Final

> Todo o conteúdo abaixo é resultado direto das respostas obtidas nas sessões com o NotebookLM documentadas acima.

---

### 1. Resumos Estruturados

#### O que é Educação Financeira?

Educação financeira é a capacidade de lidar bem com o dinheiro: consumindo de forma consciente e planejada, gerando poupança para emergências e realizando sonhos. Um sonho se torna projeto quando sai do imaginário e ganha início, fim, etapas e metas definidas.

---

#### Os 5 Conceitos Fundamentais para Iniciantes

1. **Orçamento Pessoal** – registrar receitas e despesas para garantir que as receitas superem os gastos
2. **Necessidades vs. Desejos** – necessidades são indispensáveis; desejos são ilimitados. Tratá-los como iguais leva ao endividamento
3. **Reserva de Emergência** – equivalente a pelo menos 1 mês de renda, guardada em aplicação com liquidez diária
4. **Uso Consciente do Crédito** – o crédito tem custo (juros compostos) e deve ser usado apenas quando estritamente necessário
5. **Investimento Básico** – todo investimento é avaliado por três pilares: segurança, liquidez e rentabilidade. Nunca é possível ter os três em níveis altos ao mesmo tempo

---

#### Como Montar um Orçamento Pessoal

**O que é:** Ferramenta que projeta e registra toda movimentação financeira — receitas, despesas e investimentos. Converte seus planos de vida em números concretos.

**Por que fazer:**
- Conhecer a realidade: saber para onde o dinheiro está indo
- Definir prioridades e evitar desperdícios
- Identificar se você gasta mais do que ganha
- Reduzir o estresse financeiro e melhorar a qualidade de vida da família

**Como fazer — 4 etapas:**

**I. Planejamento:** Estime receitas e despesas do mês seguinte com base no histórico. Diferencie fixos (aluguel, salário) de variáveis (luz, alimentação). Inclua gastos sazonais (IPVA, IPTU, matrícula escolar).

**II. Registro:** Anote cada gasto diariamente em caderneta, planilha ou aplicativo. Use extratos e faturas para conferir.

**III. Agrupamento:** Categorize os gastos (alimentação, habitação, transporte, lazer, saúde). Verifique qual porcentagem da renda cada categoria consome.

**IV. Avaliação e Ajuste:** Se sobrou dinheiro, "pague-se primeiro" — separe a poupança antes de qualquer despesa. Se faltou, corte supérfluos e envolva toda a família nas metas.

---

#### Juros Compostos: o maior aliado (ou inimigo)

**O que são:** "Juros sobre juros" — a cada período, os juros gerados são somados ao total e o próximo cálculo incide sobre esse montante maior. O crescimento é exponencial.

**Exemplo prático com números (das fontes):**

Uma dívida de R$ 1.000,00 a 5% ao mês:

| Mês | Juros do mês | Total devido |
|-----|-------------|-------------|
| 1 | R$ 50,00 | R$ 1.050,00 |
| 2 | R$ 52,50 | R$ 1.102,50 |
| 3 | R$ 55,13 | R$ 1.157,63 |
| 4 | R$ 57,88 | R$ 1.215,51 |
| 5 | R$ 60,78 | R$ 1.276,29 |
| 6 | R$ 63,81 | R$ 1.340,10 |

Nos juros simples o total seria R$ 1.300,00. Mas essa mesma dívida de R$ 1.000,00, sem pagamento, se tornaria R$ 1.000.000,00 em menos de 24 anos.

**No investimento:** Um jovem que poupa R$ 150/mês por apenas 10 anos a partir dos 20 anos acumula o mesmo que alguém que poupa por 30 anos a partir dos 30 — o tempo é o principal ingrediente.

---

#### Investimentos para Iniciantes

Antes de investir, as fontes recomendam ter orçamento superavitário e reserva de emergência formada. As opções indicadas para perfil conservador são:

- **Caderneta de Poupança** – a mais simples, com alta liquidez e baixo risco, mas rentabilidade menor
- **Tesouro Direto** – empréstimo ao Governo Federal, um dos ativos de menor risco da economia
- **CDB** – empréstimo a bancos, com proteção do FGC em até R$ 250 mil por instituição

Todo investimento deve ser analisado pelos três pilares: **segurança** (risco de perda), **liquidez** (facilidade de resgate) e **rentabilidade** (retorno esperado). Não é possível ter os três em níveis altos ao mesmo tempo.

---

### 2. Glossário dos Principais Conceitos

Gerado pelo NotebookLM a partir das fontes carregadas (Prompt 3):

| Termo | Definição Simples |
|-------|------------------|
| **Alavancagem** | Usar dinheiro emprestado para tentar obter lucro e aumentar o patrimônio |
| **Amortização** | Pagamento gradual de uma dívida por parcelas, reduzindo o valor total devido |
| **Ativos** | Tudo o que você possui com valor de mercado ou que gera renda (imóveis, investimentos) |
| **Câmbio** | O preço da moeda estrangeira em reais (ex: quantos reais vale um dólar) |
| **CDB** | Título de renda fixa onde você empresta dinheiro a um banco em troca de juros |
| **CET (Custo Efetivo Total)** | Taxa que mostra o custo real de um empréstimo, somando juros, tarifas e impostos |
| **Debêntures** | Título que representa um empréstimo feito a uma empresa (não a um banco) |
| **Dividendos** | Parte do lucro de uma empresa distribuída aos seus acionistas |
| **FGC** | Entidade que garante a devolução de depósitos (poupança, CDB) até R$ 250 mil em caso de quebra do banco |
| **Fluxo de Caixa** | Registro organizado de todas as entradas e saídas de dinheiro ao longo do tempo |
| **Inadimplência** | Situação de quem tem dívidas vencidas e não pagou no prazo acordado |
| **Inflação** | Aumento geral dos preços que faz o dinheiro perder valor com o tempo |
| **Insolvência** | Estado de quem está tão endividado que não tem recursos para pagar o que deve |
| **Juros compostos** | Juros que incidem sobre o valor inicial + os juros já acumulados (crescem exponencialmente) |
| **Juros simples** | Juros que incidem apenas sobre o valor inicial, sem acúmulo |
| **Liquidez** | Facilidade e velocidade para transformar um bem ou investimento em dinheiro vivo |
| **Margem consignável** | Parte do salário ou aposentadoria que pode ser descontada diretamente para pagar empréstimos |
| **Oniomania** | Termo técnico para o consumismo compulsivo — quando o hábito de comprar vira doença |
| **Passivos** | Todas as dívidas e obrigações financeiras que uma pessoa possui |
| **Patrimônio líquido** | Valor de todos os bens (ativos) menos todas as dívidas (passivos) |
| **Pós-fixado** | Investimento cujo rendimento só é conhecido no futuro, pois depende de um indicador econômico |
| **Prefixado** | Investimento com taxa definida no início, permitindo saber exatamente quanto vai render |
| **Renda fixa** | Investimentos com regras de remuneração definidas na aplicação (ex: CDB, Tesouro Direto) |
| **Renda variável** | Investimentos sem retorno garantido, que dependem de valorização (ex: ações) |
| **Rentabilidade** | O retorno financeiro de um investimento, geralmente expresso em percentual |
| **Selic** | Taxa de juros básica da economia brasileira, que influencia todas as outras taxas do mercado |
| **Tesouro Direto** | Programa que permite pessoas físicas investirem em títulos do Governo Federal |
| **Troca intertemporal** | Decisão de consumir hoje (pagando juros) ou poupar hoje para ter mais dinheiro no futuro |

---

### 3. Prompts Reutilizáveis para Revisão Futura

Prompts testados e validados neste projeto, prontos para reutilizar em futuras sessões de estudo:

**Para mapear conceitos-chave de qualquer tema:**
```
"Com base nos documentos que carreguei, quais são os [N] conceitos mais importantes
para quem está começando a aprender sobre [TEMA]?"
```

**Para aprofundar com exemplos práticos:**
```
"Com base nos documentos carregados, como [CONCEITO] é explicado para leigos?
Pode dar um exemplo prático com números?"
```

**Para criar um glossário:**
```
"Liste todos os termos técnicos presentes nos documentos que um iniciante em [ÁREA]
pode não conhecer. Para cada um, escreva uma definição simples em até 2 linhas."
```

**Para simplificar qualquer definição:**
```
"Reescreva a definição de '[TERMO]' como se estivesse explicando para uma criança de 12 anos."
```

**Para gerar resumo estruturado:**
```
"Crie um resumo estruturado em tópicos sobre [TEMA], usando apenas as informações dos
documentos carregados. Organize em: (1) O que é, (2) Por que fazer, (3) Como fazer passo a passo."
```

**Para restringir às fontes e evitar alucinações:**
```
"Responda apenas com informações presentes nos documentos que carreguei.
Se a informação não estiver nas fontes, diga que não encontrou."
```

---

## 📓 Acesso ao Notebook

O caderno temático com todas as fontes carregadas e o histórico de conversas está disponível publicamente:

🔗 [Abrir no NotebookLM](https://notebooklm.google.com/notebook/675204ef-6b77-42c2-9f34-534745de4039)

---

## 🛠️ Ferramentas Utilizadas

- [NotebookLM](https://notebooklm.google.com/) – organização e análise das fontes com IA
- [GitHub](https://github.com/) – versionamento e portfólio do projeto
- [DIO](https://www.dio.me/) – plataforma do desafio

---

## 🎯 Conclusão

Este projeto mostrou que a IA é mais útil quando você sabe o que perguntar. Prompts vagos geram respostas genéricas. Prompts com contexto, restrições e formato definido geram respostas muito mais úteis e confiáveis.

A maior dificuldade foi aprender a desconfiar das respostas quando envolviam dados específicos — e perceber que incluir "responda apenas com base nas fontes" é essencial para manter o estudo fiel ao que foi realmente estudado.

O maior aprendizado foi que o NotebookLM é uma ferramenta de síntese, não de pesquisa: ele brilha quando você traz boas fontes e faz boas perguntas.

---

*Projeto desenvolvido para o desafio de Educação Financeira com NotebookLM — DIO*
