# 🏫👨‍💻 Tech Challenge - Pós Tech (8IADT) FIAP - Fase 3: Assistente virtual de atendimento médico

Este repositório contém o desenvolvimento de um assistente virtual médico especializado em saúde e segurança da mulher. O projeto utiliza técnicas avançadas de Fine-tuning de LLMs e orquestração de fluxos complexos com LangChain e LangGraph para auxiliar profissionais de saúde em condutas clínicas e triagens especializadas.

O sistema foi treinado com dados próprios e protocolos institucionais para oferecer suporte em ginecologia, obstetrícia, saúde mental materna e detecção de violência doméstica, conforme instruções contidas no PDF fornecido [(Tech Challenge - Fase 3.pdf)](https://github.com/marceloklotz/fiap-terceira-fase/blob/main/8IADT-Fase3-TechChallenge-Secretaria.pdf).

O notebook final do grupo foi incluído em:
https://github.com/marceloklotz/fiap-terceira-fase/blob/main/FIAP_Fase_3.ipynb

## 📝 Descrição do Desafio

A proposta do desafio foi desenvolver um assistente virtual médico personalizado, treinado com dados próprios da instituição, capaz de apoiar condutas clínicas, responder dúvidas de profissionais e sugerir procedimentos alinhados aos protocolos internos de atendimento feminino. O desafio também envolve a criação de fluxos automatizados, seguros e integrados, utilizando LangChain, para coordenar ações como verificação de exames ginecológicos pendentes, recomendação de tratamentos reprodutivos, emissão de alertas para possíveis casos de violência doméstica e articulação de atendimento multidisciplinar, considerando as particularidades e sensibilidades do cuidado à mulher.

Para tanto, utilizou-se o fine-tuning de LLMs com dados específicos da área e implementando fluxos automatizados de decisão clínica através do LangChain, sempre respeitando protocolos de segurança, privacidade e sensibilidade cultural específicos do atendimento feminino, conforme instruções da disciplina da Pós Tech (8IADT) FIAP [(Tech Challenge - Fase 3.pdf)](https://github.com/marceloklotz/fiap-terceira-fase/blob/main/8IADT-Fase3-TechChallenge-Secretaria.pdf).




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

![FIAP - TECH CHALLENGE (TERCEIRA FASE)](https://i.ytimg.com/vi/4wX8KIxYdJ4/maxresdefault.jpg)

<p align="center"> https://youtu.be/4wX8KIxYdJ4 </p>
