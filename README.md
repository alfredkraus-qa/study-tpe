# Estudo - Técnica de Partição de Equivalência (TPE)

## Olá família!!! ✨

Este repositório foi criado para documentar meu aprendizado sobre a Técnica de Partição de Equivalência. Espero que seja útil para vocês!

## O que é TPE?

A Técnica de Partição de Equivalência (TPE) é uma abordagem de teste utilizada para dividir os dados de entrada de um sistema em classes ou partições, onde cada classe representa um conjunto de valores que o sistema trata de forma equivalente. O objetivo principal é reduzir o número de casos de teste, garantindo uma cobertura eficiente e representativa sem comprometer a qualidade.

## Para que serve?

Essa técnica é essencial para garantir que o sistema funcione corretamente com diferentes tipos de entradas, otimizando os esforços de teste. Ela ajuda a identificar cenários **positivos** (onde o sistema opera como esperado) e **negativos** (onde o sistema reage adequadamente a entradas inválidas).

## Por que usamos na área de QA?


No contexto de QA, a TPE é uma ferramenta poderosa para melhorar a eficiência dos testes. Ela possibilita:

**1. Reduzir redundâncias:** Testar um representante de cada partição, ao invés de todos os valores possíveis.

**2. Cobertura eficaz:** Identificar e validar comportamentos em situações variadas.

**3.  Foco em cenários críticos:** Priorizar casos de teste com maior probabilidade de revelar defeitos.

## Exemplo Prático

### 1. Regras de Negócio

Vou mostrar de forma simples como aplicar a TPE usando um exemplo prático baseado em uma regra de negócio fictícia para criar seus cenários de teste.

Digamos que, em sua sprint, você receba a seguinte tarefa:

**Task:** 

• Nosso sistema de transferência PIX sofrerá uma alteração: agora, só será possível realizar transferências acima de mil reais entre 7:00 a.m. e 8:00 p.m.

### 2. Estrutura

Com base nessa regra de negócio, vamos organizar os elementos em tópicos para, em seguida, criar um diagrama usando a Técnica de Partição de Equivalência.

**1. Entrada**

• Valor do PIX: R$ 1.000,00

**2. Condição**

• Horário da transferência: entre 7:00 a.m. e 8:00 p.m.

**3. Tipos de Resultado**

• Resultados dos testes: Positivo (transferência permitida) ou Negativo (transferência bloqueada).

### 3. Diagrama 

<img width="1209" alt="Image" src="https://github.com/user-attachments/assets/e64bb22a-2cac-4679-ab46-52caeb77c06e" />


No diagrama acima, podemos visualizar quatro cenários de teste criados com base na estrutura montada. Isso torna mais fácil compreender como desenvolver os principais casos de teste e focar no que realmente importa, priorizando cenários críticos.

Além disso, no exemplo acima, seria possível adicionar mais dois cenários utilizando o valor de entrada **igual** a R$ 1.000,00. A decisão de incluir esses casos dependerá do seu nível de experiência ou do tempo disponível para aplicar essa técnica.

Vale lembrar que a Técnica de Partição de Equivalência (TPE) tem como objetivo extrair os melhores dados possíveis para a criação de cenários de teste. Ela pode ser aplicada em diversas ferramentas de gerenciamento de tarefas ou testes, como Jira, Asana, TestRail, ou até mesmo em planilhas, como Excel ou Google Sheets, para organizar e analisar os testes de forma eficiente.

No exemplo abaixo, vou demonstrar a criação de vários cenários fictício utilizando a ferramenta Trello.


<img width="779" alt="Image" src="https://github.com/user-attachments/assets/0d1588e5-3bdd-4d80-9b70-90bf9b5f5047" />



## Considerações Finais

A Técnica de Partição de Equivalência é uma das ferramentas mais valiosas para um profissional de QA. Ela não apenas otimiza o processo de teste, mas também promove a qualidade ao garantir que cenários críticos e variados sejam abordados de forma eficiente. Dominar essa técnica é essencial para quem busca realizar testes mais estratégicos e eficazes, contribuindo diretamente para o sucesso do produto e a satisfação do cliente.

Obrigado por acompanhar até aqui. Espero que as informações agreguem valor ao seu aprendizado. Tamo junto família! 🚀🌟
