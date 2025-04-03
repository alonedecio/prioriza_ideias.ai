# 💡 Sistema Inteligente de Priorização e Categorização de Ideias com IA

Este projeto utiliza **LangChain** com **OpenAI** para automatizar a avaliação, categorização e priorização de ideias estratégicas, com foco em empresas do setor de **mineração e construção civil**. O objetivo é transformar uma planilha de ideias brutas em um documento estruturado, classificado e pronto para tomada de decisão.

## 🚀 Funcionalidades

- ✅ Leitura de ideias a partir de planilha Excel
- ✅ Classificação automática por critérios quantitativos:
  - Alcance (`reach`)
  - Impacto (`impact`)
  - Confiança (`confidence`)
  - Valor de negócio
  - Urgência no tempo
  - Redução de risco
- ✅ Categorização estratégica por área (ex: Operações, Sustentabilidade, RH)
- ✅ Avaliação do impacto (Alto, Médio, Baixo ou Ver e Agir) com base no modelo **Cynefin**
- ✅ Cálculo de valor composto para priorização das ideias
- ✅ Identificação de ideias semelhantes por:
  - Embeddings semânticos com **FAISS + LangChain**
  - Comparação textual com **FuzzyWuzzy** (sem IA)
- ✅ Geração automática de novo Excel com todas as colunas estruturadas

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10
- [LangChain](https://www.langchain.com/)
- [OpenAI GPT-4o-mini](https://platform.openai.com/)
- FAISS (Vector Store para busca semântica)
- Pandas
- Matplotlib (visualização opcional)
- FuzzyWuzzy (matching textual)
- GPT-2 Tokenizer (para divisão de texto inteligente)

---

## 📂 Estrutura de Arquivos

