# 🏫👨‍💻 Tech Challenge - Pós Tech (8IADT) FIAP - Fase 3: Assistente virtual de atendimento médico

Este repositório contém o desenvolvimento de um assistente virtual médico especializado em saúde e segurança da mulher. O projeto utiliza técnicas avançadas de Fine-tuning de LLMs e orquestração de fluxos complexos com LangChain e LangGraph para auxiliar profissionais de saúde em condutas clínicas e triagens especializadas.

O sistema foi treinado com dados próprios e protocolos institucionais para oferecer suporte em ginecologia, obstetrícia, saúde mental materna e detecção de violência doméstica, conforme instruções contidas no PDF fornecido [(Tech Challenge - Fase 3.pdf)](https://github.com/marceloklotz/fiap-terceira-fase/blob/main/8IADT-Fase3-TechChallenge-Secretaria.pdf).

O notebook final do grupo foi incluído em:
https://github.com/marceloklotz/fiap-terceira-fase/blob/main/FIAP_Fase_3.ipynb

## 📝 Descrição do Desafio

O objetivo principal é melhorar a precisão e a interpretabilidade dos modelos de diagnóstico desenvolvidos na fase anterior
. Para isso, implementamos:
Otimização de Hiperparâmetros: Uso de Algoritmos Genéticos para encontrar a configuração ideal do modelo
. Interpretabilidade via LLM: Integração com modelos de linguagem para gerar explicações humanizadas sobre os diagnósticos para profissionais de saúde

## 👥 Integrantes do grupo
Os membros do grupo são compostos pelos seguintes servidores da Secretaria de Segurança Pública do Distrito Federal (SSP/DF):

- Alexandre Natã Vicente (**rm370024**) (ale.n.vicente@gmail.com)
- Antônio Cláudio Almeida (**rm370052**) (antonioalmeida@gmail.com)
- Cyd Ferreira Rodrigues (**rm370004**) (cydnelson@gmail.com)
- David Catherink (**rm369997**) (d.catherinck@gmail.com)
- Marcelo Macedo Klotz (**rm370010**) (marceloklotz@gmail.com)

## 🎲 Base de dados

[EDITAR]

## 🛠️ Funcionalidades Principais

Fine-tuning Especializado: Modelo de linguagem ajustado com diretrizes da FEBRASGO, OMS e protocolos de rastreamento de câncer (INCA)


### 🧬 Algoritmos Genéticos (GA)

Para otimizar os hiperparâmetros, o GA foi configurado com:
- Genes: Representação dos hiperparâmetros (ex: learning rate, profundidade de árvore).
- Operadores: Implementação de seleção, cruzamento (crossover) e mutação.
- Função Fitness: Baseada em métricas de desempenho como Recall e F1-Score, priorizando a redução de falsos negativos no contexto médico.

### 🤖 Integração com LLMs

Utilizamoo o GPT-4o mini, que é um modelo de inteligência artificial da OpenAI, projetado para ser uma versão rápida, leve e acessível (barata) do modelo principal para transformar resultados numéricos e estatísticos (SHAP/Feature Importance) em insights acionáveis.  Apesar de ser uma solução mais acessível é robusta o suficiente para o caso proposto.

- Prompt Engineering: Desenvolvimento de instruções específicas para garantir que as explicações sejam precisas e adequadas ao contexto clínico.

## 📒 Relatório técnico

O relatório técnico descreve o desafio proposto e a forma de exploração de dados adotada pelos membros do grupo, explicando as estratégias de pré-processamento e limpeza dos dados, os modelos avaliados e utilizados, os resultados obtidos, a interpretação do dados, além da aplicabilidade prática e as lições aprendidas durante o desenvolvimento da atividade acadêmica.

O download do relatório pode ser feito diretamente pelo seguinte link: 
https://github.com/marceloklotz/breast-cancer-fiap-segunda-fase/blob/main/Relat%C3%B3rio%20T%C3%A9cnico%20-%20Segunda%20Fase.pdf

## 📽️ Vídeo explicativo

O vídeo explicativo sobre a metologia, resultados e notebook em execução foi disponbilizado a partir do seguinte link:

[![Tech Challenge – Fase 2 | Otimização de Modelos de Diagnóstico com Algoritmos Genéticos e LLMs](https://img.youtube.com/vi/SBfUBlP-d4Q/0.jpg)](https://www.youtube.com/watch?v=SBfUBlP-d4Q)

https://www.youtube.com/watch?v=SBfUBlP-d4Q
