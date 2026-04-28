# Prompts testados no NotebookLM

Este arquivo registra os prompts usados no caderno temático sobre Yann LeCun.

A ideia é demonstrar o processo de engenharia de prompts, incluindo perguntas, ajustes e estratégias usadas para extrair melhores respostas da IA.

---

## Prompt 1 — Visão geral

```text
Com base apenas nas fontes deste caderno, explique quem é Yann LeCun e por que ele é importante para a história da Inteligência Artificial.
```

**Objetivo:**  
Obter uma visão geral sobre a trajetória e importância de Yann LeCun.

**Possível dificuldade:**  
A resposta pode ficar muito genérica.

**Ajuste recomendado:**  

```text
Explique em tópicos e inclua contribuições técnicas, instituições em que trabalhou e impacto no deep learning.
```

---

## Prompt 2 — Linha do tempo

```text
Crie uma linha do tempo da carreira de Yann LeCun, destacando sua formação, passagem pela Bell Labs, contribuições para redes neurais convolucionais, atuação na NYU, trabalho na Meta/FAIR, Turing Award e projetos recentes.
```

**Objetivo:**  
Organizar a trajetória de LeCun em ordem cronológica.

**Possível dificuldade:**  
Misturar datas ou trazer eventos sem fonte clara.

**Ajuste recomendado:**  

```text
Inclua apenas eventos que estejam presentes nas fontes adicionadas e cite a fonte usada para cada marco.
```

---

## Prompt 3 — Conceitos técnicos

```text
Liste os principais conceitos técnicos associados ao trabalho de Yann LeCun. Para cada conceito, explique:
1. Definição simples
2. Importância para IA
3. Relação com Yann LeCun
4. Exemplo prático
```

**Objetivo:**  
Criar uma base de estudos técnicos.

**Possível dificuldade:**  
Explicações muito avançadas para iniciantes.

**Ajuste recomendado:**  

```text
Explique cada conceito em três níveis: iniciante, intermediário e avançado.
```

---

## Prompt 4 — CNNs e LeNet

```text
Explique como as redes neurais convolucionais aparecem no trabalho de Yann LeCun. Relacione CNNs, LeNet, reconhecimento de dígitos manuscritos e visão computacional.
```

**Objetivo:**  
Entender uma das contribuições mais importantes de LeCun.

**Possível dificuldade:**  
A resposta pode ficar abstrata.

**Ajuste recomendado:**  

```text
Use uma analogia simples e depois explique tecnicamente.
```

---

## Prompt 5 — Paper clássico

```text
Resuma o paper "Gradient-Based Learning Applied to Document Recognition" em linguagem simples. Explique o problema resolvido, a abordagem usada, os resultados e por que esse trabalho foi importante para o deep learning.
```

**Objetivo:**  
Compreender o paper relacionado a reconhecimento de documentos.

**Possível dificuldade:**  
O NotebookLM pode resumir sem destacar impacto histórico.

**Ajuste recomendado:**  

```text
Inclua uma seção chamada "Por que este paper foi importante para a IA moderna?".
```

---

## Prompt 6 — Paper moderno

```text
Resuma o paper "A Path Towards Autonomous Machine Intelligence". Explique os conceitos de world models, JEPA, aprendizado autossupervisionado, motivação intrínseca e planejamento.
```

**Objetivo:**  
Estudar a visão atual de LeCun sobre IA autônoma.

**Possível dificuldade:**  
JEPA e world models podem aparecer de forma muito técnica.

**Ajuste recomendado:**  

```text
Explique JEPA e world models com analogias antes da explicação técnica.
```

---

## Prompt 7 — Comparação crítica

```text
Compare a visão de Yann LeCun sobre IA com a abordagem dominante dos grandes modelos de linguagem. Aponte diferenças, vantagens, limitações e perguntas em aberto, usando apenas as fontes do caderno.
```

**Objetivo:**  
Desenvolver pensamento crítico sobre diferentes abordagens de IA.

**Possível dificuldade:**  
A IA pode incluir informações fora das fontes.

**Ajuste recomendado:**  

```text
Não use conhecimento externo. Baseie a comparação apenas nas fontes adicionadas ao caderno.
```

---

## Prompt 8 — Glossário

```text
Crie um glossário técnico com os principais conceitos do caderno. Inclua termos como CNN, LeNet, backpropagation, deep learning, self-supervised learning, JEPA, world model, energy-based model e advanced machine intelligence.
```

**Objetivo:**  
Criar material de revisão rápida.

**Possível dificuldade:**  
Definições podem ficar curtas demais.

**Ajuste recomendado:**  

```text
Para cada termo, inclua definição, exemplo prático e relação com Yann LeCun.
```

---

## Prompt 9 — Perguntas de revisão

```text
Crie 20 perguntas de revisão sobre Yann LeCun e suas contribuições para IA. Separe em nível básico, intermediário e avançado. Inclua respostas curtas baseadas nas fontes.
```

**Objetivo:**  
Criar um sistema de revisão ativa.

**Possível dificuldade:**  
Perguntas podem ficar repetitivas.

**Ajuste recomendado:**  

```text
Evite perguntas repetidas e cubra biografia, CNNs, LeNet, deep learning, JEPA e world models.
```

---

## Prompt 10 — Miniguia final

```text
Com base em todas as fontes deste caderno, crie um miniguia de estudo sobre Yann LeCun e sua importância para a Inteligência Artificial. O guia deve conter:
1. Introdução
2. Linha do tempo
3. Principais contribuições
4. Conceitos técnicos
5. Papers fundamentais
6. Glossário
7. Perguntas de revisão
8. Conclusão
```

**Objetivo:**  
Consolidar o conteúdo final para o README e para estudo.

**Possível dificuldade:**  
O conteúdo pode ficar longo demais.

**Ajuste recomendado:**  

```text
Organize o miniguia em seções curtas e use tabelas quando possível.
```

---

## Prompts reutilizáveis

```text
Explique este conceito como se eu fosse iniciante.
```

```text
Explique este conceito em três níveis: básico, intermediário e avançado.
```

```text
Crie uma analogia para este conceito.
```

```text
Crie flashcards para revisão.
```

```text
Crie perguntas de prova sobre este conteúdo.
```

```text
Compare os conceitos em uma tabela.
```

```text
Resuma este paper em problema, método, resultado e impacto.
```

```text
Monte um plano de estudo de 7 dias.
```
