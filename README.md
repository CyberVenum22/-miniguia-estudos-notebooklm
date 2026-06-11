# 📘 Miniguia de Estudos: Finanças Pessoais e Investimentos na Era Digital com NotebookLM

## 🎯 Contexto e Objetivos
Este repositório foi criado como parte de um desafio prático da Digital Innovation One (DIO). O objetivo principal é construir um **Caderno Temático no NotebookLM** focado em **Finanças Pessoais e Introdução aos Investimentos**, explorando o uso da Inteligência Artificial como uma ferramenta de aprendizagem ativa e curadoria de conhecimento.

**Objetivos de Estudo:**
* Compreender os pilares da organização financeira pessoal e do orçamento doméstico.
* Entender a diferença entre renda fixa e renda variável no cenário atual.
* Analisar o impacto e os cuidados com a segurança digital (fraudes, golpes) ao gerenciar finanças por aplicativos e bancos digitais.
* Criar uma base de consulta rápida (glossário e resumos) para revisões futuras.

---

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM, foram selecionadas **4 fontes abertas de alta credibilidade** em formato de texto/PDF. O foco foi unir a base tradicional de finanças com a realidade tecnológica atual:

1. **BCB - Caderno de Educação Financeira (Gestão de Finanças Pessoais):** Guia oficial do Banco Central do Brasil sobre orçamento e administração de recursos.
2. **CVM - Guia de Introdução aos Investimentos:** Material didático da Comissão de Valores Mobiliários explicando conceitos de risco, retorno e tipos de ativos.
3. **Guia de Segurança Digital para Usuários de Apps Financeiros (Artigo Técnico/Febraban):** Documento focado em boas práticas de cibersegurança, prevenção de phishing e engenharia social em transações bancárias digitais.
4. **Relatório de Tendências de Open Finance no Brasil:** Texto analítico sobre como o compartilhamento de dados financeiros pode ser usado para otimizar investimentos pessoais.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Documentação do processo de iteração com o NotebookLM para extrair as melhores respostas.

### Prompt Teste 1: Abordagem Direta (Genérico)
* **Prompt:** *"Me explica o que é renda fixa e o que é renda variável baseado nas fontes."*
* **Resultado da IA:** A IA trouxe uma resposta correta, porém muito longa e em formato de blocos de texto densos, o que dificultava a leitura rápida.
* **Crítica/Ajuste:** Faltou estrutura visual e uma tabela comparativa para facilitar o aprendizado ativo.

### Prompt Teste 2: Abordagem Estruturada (Engenharia de Prompt)
* **Prompt:** *"Atue como um especialista em educação financeira. Com base exclusivamente nos documentos da CVM e do Banco Central fornecidos, crie uma tabela comparativa entre Renda Fixa e Renda Variável. A tabela deve conter: Definição, Nível de Risco Típico, Exemplos Comuns e Liquidez. Cite as fontes ao final."*
* **Resultado da IA:** Excelente. A IA organizou os dados estritamente dentro das fontes, gerando uma tabela clara e sem alucinações.
* **Referência Gerada:** *Conforme Guia de Introdução aos Investimentos (CVM, Seção 3.2).*

### 🛠️ Cicatrizes e Desafios (Troubleshooting)
* **O Problema:** Ao perguntar sobre "como proteger meu dinheiro de golpes no Pix", o NotebookLM inicialmente tentou usar dados gerais da internet em vez de focar apenas no PDF de Segurança Digital fornecido.
* **A Solução:** Foi necessário aplicar uma **restrição estrita** no prompt: *"Utilize APENAS as informações presentes no documento 'Guia de Segurança Digital...'. Se a informação não estiver lá, diga que não sabe."* Isso calibrou a IA para manter a fidelidade total às fontes curadas.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados

#### 1. Planejamento Financeiro e Orçamento
* **Regra de Ouro:** O sucesso financeiro não depende de quanto se ganha, mas da relação entre receitas e despesas. O primeiro passo é o diagnóstico financeiro (mapeamento de gastos por categorias).
* **Reserva de Emergência:** Deve cobrir de 3 a 6 meses de despesas fixas, alocada em ativos de altíssima liquidez (saque rápido) e baixo risco.

#### 2. Renda Fixa vs. Renda Variável
* **Renda Fixa:** O investidor conhece as regras de remuneração (taxa prefixada ou pós-fixada) no momento da aplicação. Considerada mais segura.
* **Renda Variável:** O retorno não pode ser previsto. Depende de fatores de mercado (ações, fundos imobiliários). Maior potencial de ganho, porém com maior risco de perda.

#### 3. Segurança Digital nas Finanças
* **Fator Humano:** A maioria das fraudes atuais utiliza engenharia social (indução da vítima ao erro).
* **Práticas Recomendadas:** Nunca clicar em links recebidos por SMS/WhatsApp alegando "atualização de chave Pix" e ativar a autenticação de dois fatores (2FA) em todos os aplicativos bancários.

### 📕 Glossário de Conceitos Chave
* **Liquidez:** A velocidade e facilidade com que um investimento pode ser convertido em dinheiro em conta corrente sem perda significativa de valor.
* **Selic:** A taxa básica de juros da economia brasileira, que influencia o rendimento da maioria das aplicações de Renda Fixa.
* **Phishing:** Técnica de fraude digital que utiliza mensagens e sites falsos para roubar dados bancários e senhas de usuários.
* **Diversificação:** Estratégia de alocação de recursos em diferentes tipos de investimentos para diluir riscos de perda.
### 🔄 Prompts Reutilizáveis para Revisão
Copie e cole estes prompts no seu NotebookLM para realizar revisões rápidas:

Prompt 1 (Simulado de Questões):
"Com base nos resumos e fontes sobre investimentos, gere 3 perguntas de múltipla escolha para testar meu conhecimento sobre a diferença entre risco e liquidez. Não dê a resposta imediatamente; aguarde eu responder."

Prompt 2 (Explicação Simples):
"Explique o conceito de Open Finance e como ele afeta a segurança dos meus dados para uma pessoa que não é da área de tecnologia. Use uma metáfora simples."
