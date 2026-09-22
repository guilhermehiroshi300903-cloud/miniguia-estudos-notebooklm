# 🧠 Miniguia de Estudos: Agentes Autônomos de IA

Bem-vindo ao meu Caderno Temático! Este repositório foi criado como parte de um desafio prático da DIO, utilizando o Google NotebookLM (e outras ferramentas de IA) como assistente de aprendizagem ativa para explorar e organizar conhecimento sobre Inteligência Artificial.

---

## 🎯 Contexto e Objetivos

Com a rápida evolução dos Modelos de Linguagem de Grande Escala (LLMs), o foco do mercado está mudando de simples "chatbots" para **Agentes Autônomos** — sistemas capazes de planejar, usar ferramentas e tomar decisões de forma independente para atingir um objetivo. 

**Objetivos de Estudo:**
1. Compreender a arquitetura básica de um Agente de IA (Memória, Planejamento e Ação).
2. Entender a diferença entre um LLM tradicional e um fluxo de trabalho agêntico (Agentic Workflow).
3. Consolidar os principais termos técnicos da área para facilitar estudos futuros práticos com frameworks como LangChain e CrewAI.

---

## 📚 Curadoria de Fontes

Para alimentar a base de conhecimento da IA (NotebookLM) e garantir respostas precisas e fundamentadas, os seguintes materiais abertos foram selecionados e utilizados como contexto:

1. **[LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)** - Artigo clássico de Lilian Weng (OpenAI) que detalha a anatomia de um agente.
2. **[LangChain Concepts: Agents](https://python.langchain.com/docs/concepts/#agents)** - Documentação oficial sobre como frameworks implementam agentes na prática.
3. **[Agentic Design Patterns](https://www.deeplearning.ai/the-batch/how-agents-can-improve-llm-performance/)** - Resumo dos padrões de design agêntico discutidos por Andrew Ng.

---

## 🛠️ Engenharia de Prompts e "Cicatrizes"

Durante o processo de estudo com a IA, documentei a evolução dos meus prompts. Extrair a melhor resposta requer iterar e refinar as perguntas.

| Tentativa | Prompt Utilizado | Resultado / Dificuldade ("Cicatriz") | Lição Aprendida |
| :--- | :--- | :--- | :--- |
| **01 (Básica)** | *"O que é um agente de IA?"* | A IA deu uma resposta genérica de dicionário, misturando com IA de videogames antigos. Faltou contexto atual. | Precisamos ancorar a IA nas fontes específicas fornecidas no upload. |
| **02 (Técnica demais)**| *"Como programar um agente com ReAct no Python?"* | A IA gerou blocos de código complexos sem explicar os conceitos por trás, o que não ajuda no estudo teórico inicial. | O prompt deve focar primeiro em arquitetura e conceitos antes da sintaxe de código. |
| **03 (Estratégica)** | *"Atuando como um professor de IA, baseie-se nos documentos enviados para explicar a arquitetura de um Agente Autônomo. Divida a explicação nos pilares: Planejamento, Memória e Uso de Ferramentas. Use analogias simples."* | **Sucesso absoluto.** A resposta veio bem estruturada, didática e fiel aos documentos de origem. | Fornecer uma "persona" (professor), definir a estrutura desejada e pedir analogias melhora a qualidade da resposta em 100%. |

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

Os **Agentes Autônomos** representam o próximo passo evolutivo da IA. Enquanto um LLM (como o ChatGPT padrão) apenas responde ao que você pergunta com base no seu treinamento estático, um Agente atua como um "cérebro" que coordena tarefas complexas. 

A anatomia de um Agente baseia-se em três pilares fundamentais:
* **Planejamento (Planning):** A capacidade de quebrar um problema grande em passos menores (Task Decomposition) e refletir sobre os próprios erros (Self-Reflection).
* **Memória (Memory):** 
  * *Curto prazo:* O histórico imediato da conversa e do raciocínio atual.
  * *Longo prazo:* Acesso a bases de dados externas ou vetoriais para reter informações por longos períodos.
* **Uso de Ferramentas (Tool Use/Action):** A IA percebe que não sabe algo e decide "chamar" uma API externa (ex: pesquisar na web, rodar código Python, consultar uma calculadora ou calendário).

### 2. Glossário de Conceitos Aprendidos

* **Agentic Workflow:** Fluxo de trabalho onde a IA não apenas gera texto de uma vez, mas itera, revisa seu próprio trabalho e usa ferramentas em múltiplos passos.
* **ReAct (Reasoning and Acting):** Um framework de prompt onde o modelo é forçado a intercalar "pensamento" (raciocínio sobre o que fazer) e "ação" (execução de uma ferramenta).
* **Chain of Thought (CoT):** Técnica que incentiva a IA a "pensar passo a passo" antes de dar a resposta final, reduzindo alucinações.
* **RAG (Retrieval-Augmented Generation):** Técnica onde o agente busca informações em uma base de dados externa antes de gerar uma resposta.

### 3. Prompts Reutilizáveis para Revisão

Para continuar estudando ou revisar o tema no futuro usando o NotebookLM (ou ChatGPT/Claude), utilize estes prompts:

* **Para fixação de conceitos:** *"Gere um quiz de 5 perguntas de múltipla escolha focadas nas diferenças entre Memória de Curto e Longo Prazo em agentes de IA, baseando-se nas fontes fornecidas. Esconda as respostas no final."*
* **Para aprofundamento:** *"Explique detalhadamente o padrão 'ReAct' usando uma analogia de um cozinheiro preparando uma receita complexa."*
* **Para aplicação prática:** *"Proponha a arquitetura de um agente de IA projetado para ajudar um estudante a organizar sua rotina de estudos. Quais ferramentas (APIs) ele precisaria acessar?"*
