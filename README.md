# ⚡ Estudo Ativo: O Legado de Nikola Tesla com NotebookLM

Este repositório contém o projeto prático desenvolvido para o desafio da DIO sobre **Aprendizagem Ativa com IA**. O objetivo foi utilizar o Google NotebookLM para organizar e aprofundar conhecimentos sobre a vida e as invenções de **Nikola Tesla**.

## 🎯 Contexto e Objetivos
O projeto foca na análise de documentos históricos e técnicos para entender como as invenções de Tesla moldaram o mundo moderno.
- **Objetivo principal:** Explorar a capacidade do NotebookLM de sintetizar patentes e textos biográficos.
- **Assunto:** A revolução da Corrente Alternada e as invenções disruptivas de Nikola Tesla.

---

## 📚 Curadoria de Fontes
As seguintes fontes foram carregadas no NotebookLM para criar a base de conhecimento:

1. **My Inventions: The Autobiography of Nikola Tesla** - Relato em primeira pessoa sobre sua vida e processos criativos.
2. **The War of the Currents (U.S. Dept. of Energy)** - Documento oficial sobre a disputa entre Tesla/Westinghouse e Edison.
3. **Patente US381968A (Electro-Magnetic Motor)** - Documento técnico original do motor de indução.
4. **Apparatus for Transmitting Electrical Energy** - Patente de Tesla sobre os princípios da transmissão de energia sem fio.
5. **War of the Currents: How AC Defeated DC** - Artigo técnico-histórico sobre as vantagens da Corrente Alternada.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"
Esta seção documenta a evolução do raciocínio e os ajustes necessários para transformar respostas genéricas em conhecimento técnico profundo.

### 🔍 Fase 1: Sondagem Geral (Sem fontes específicas)
No início, os testes serviram para entender a base de dados comum da IA:
- **Prompt:** "Quem é Nikola Tesla?"
  - **Resposta:** Explicação biográfica padrão (nascimento, feitos e marcos).
- **Prompt:** "Qual a questão entre Nikola Tesla e Thomas Edison?"
  - **Resposta:** Detalhes sobre a rivalidade e contexto histórico.

### 🛠️ Fase 2: Refinamento com Curadoria (Aprendizado Ativo)
Ao utilizar o NotebookLM com as fontes selecionadas, a precisão aumentou drasticamente:

#### **Exemplo 1: Contextualização Biográfica**
- **Prompt:** *"Com base nos documentos fornecidos, me conte sobre Nikola Tesla."*
- **O que aconteceu:** A resposta tornou-se muito mais rica e fiel aos textos, detalhando os feitos mencionados na curadoria com foco e dedicação superiores às IAs convencionais.

#### **Exemplo 2: Análise de Conflito Histórico**
- **Prompt:** *"Com base nos documentos fornecidos, o que foi a 'Guerra das Correntes'? Tesla saiu vencedor?"*
- **O que aconteceu:** A IA trouxe detalhes técnicos e "sórdidos" da disputa, concluindo que não houve um vencedor isolado, mas uma união de ideais que formou a rede elétrica moderna.

#### **Exemplo 3: Tradução de Conceitos Complexos (Analogias)**
- **Prompt:** *"Com base nos documentos, explique o funcionamento do Campo Magnético Rotativo usando uma analogia simples."*
- **O que aprendi:** A IA extraiu das fontes analogias mecânicas (pêndulo) e hidráulicas (bombas de pistão).
- **Destaque:** *"Assim como dois balanços retos se combinam para criar um círculo suave, as duas correntes elétricas alternadas se combinam para criar um campo magnético que gira de forma contínua."*



#### **Exemplo 4: Análise Comparativa e Dados Financeiros**
- **Prompt:** *"Liste as vantagens da Corrente Alternada (AC) sobre a Corrente Contínua (DC) citadas nos documentos do Departamento de Energia."*
- **Análise Técnica:** Identificação do transformador como chave para a escalabilidade (Cataratas do Niágara -> Buffalo).
- **Dados de Mercado:** A IA identificou a viabilidade econômica (proposta de $399.000 da Westinghouse contra $554.000 da General Electric).



### 🩹 Ajustes e Dificuldades (Cicatrizes de Batalha)
- **Problema de Escopo:** Inicialmente, a IA tendia a usar conhecimentos gerais da internet em vez dos documentos subidos.
- **Solução:** Implementação de uma "âncora" no prompt: *"Responda estritamente com base nos documentos de patentes fornecidos"*. Isso eliminou alucinações e trouxe detalhes técnicos que só constavam nos arquivos de Tesla.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado das Invenções
* **Motor de Corrente Alternada (AC):** Funciona através do campo magnético rotativo, eliminando a necessidade de componentes mecânicos de desgaste como escovas.
* **Bobina de Tesla:** Transformador de oscilação para produção de correntes de altíssima tensão e frequência.
* **Telautomática:** Pioneirismo no controle remoto e robótica via ondas de rádio (barco submersível).
* **Transmissor Amplificador:** Sistema para excitar a Terra eletricamente para transmissão de energia sem fios.

### 2. A "Guerra das Correntes"
O embate tecnológico que definiu o padrão global. A Corrente Alternada (AC) de Tesla venceu pela eficiência técnica na transmissão de longa distância, superando as limitações geográficas da Corrente Contínua (DC) de Edison.

### 3. Glossário Técnico
* **Corrente Alternada (AC):** Fluxo elétrico que inverte a direção, facilitando a alteração de voltagem.
* **Campo Magnético Rotativo:** Fenômeno onde correntes defasadas geram rotação magnética contínua.
* **Descarga Disruptiva:** Centelha elétrica potente usada para gerar altas frequências.
* **Transformador:** Componente vital para elevar ou reduzir a tensão elétrica.

### 4. Prompts Reutilizáveis para Revisão
* *"Crie um questionário de 5 perguntas sobre a Guerra das Correntes com base no texto do Dept. of Energy."*
* *"Explique a importância da Torre de Wardenclyffe para o conceito de energia sem fios moderna."*

---

## 🛠️ Ferramentas Utilizadas
- [Google NotebookLM](https://notebooklm.google/)
- Fontes: Archive.org, Google Patents e Department of Energy (USA).

---
Desenvolvido para o desafio de projeto na **DIO**. 😎
