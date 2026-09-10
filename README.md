# 📚 Miniguia de Estudos: Engenharia de Prompts com NotebookLM

Projeto prático desenvolvido para o Desafio de Projeto da [DIO](https://dio.me), explorando o uso de IA na aprendizagem ativa.

---

## 🎯 Contexto e Objetivos
O objetivo deste caderno temático é consolidar os fundamentos da Engenharia de Prompts, explorando técnicas para obter respostas precisas e estruturadas de modelos de linguagem (LLMs).

## 🔗 Curadoria de Fontes
Foram utilizadas fontes abertas e de referência no mercado:
1. [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai)
2. [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
3. [Learn Prompting](https://learnprompting.org)

## 💡 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Durante a exploração no NotebookLM, foram testadas variações de prompts:
- **Prompt Vago:** *"O que é Few-Shot Prompting e Chain-of-Thought?"*
  - **Resultado:** Respostas pontuais e separadas em blocos de texto, exigindo leitura dispersa.
- **Prompt Estruturado:** *"Com base exclusivamente nas fontes adicionadas, compare Few-Shot Prompting com Chain-of-Thought (CoT). Apresente a resposta em formato de tabela comparativa..."*
  - **Resultado:** A IA gerou uma tabela organizada por técnica, funcionamento e casos de uso.
- **Aprendizado (Cicatriz):** Restringir o formato de saída (tabelas, tópicos) e delimitar a base de conhecimento evita respostas genéricas e acelera a revisão.

## 📖 Miniguia de Estudo
### Resumo das Principais Técnicas
- **Zero-Shot:** Pedir uma resposta direta sem dar exemplos prévios.
- **Few-Shot:** Fornecer 2 a 3 exemplos de entrada/saída antes de pedir a resposta real.
- **Chain-of-Thought (CoT):** Conduzir a IA a "pensar passo a passo" antes de concluir.

### Glossário Rápido
- **LLM (Large Language Model):** Modelo treinado em grandes volumes de texto.
- **Context Window:** Quantidade máxima de texto que o modelo processa por vez.
- **Alucinação:** Quando o modelo gera informações incorretas com tom de certeza.

### 🛠️ Prompts Reutilizáveis para Estudos
1. *"Explique o conceito [X] como se eu fosse um desenvolvedor iniciante, usando uma analogia do dia a dia."*
2. *"Crie um quiz com 3 perguntas de múltipla escolha sobre [tema], mostrando o gabarito apenas no final."*
3. *"Identifique e resuma as 3 principais boas práticas mencionadas nas fontes sobre [assunto]."*
