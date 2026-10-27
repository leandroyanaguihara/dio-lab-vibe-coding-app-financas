# 💸 App de Finanças Pessoais do Leandro com Vibe Coding

## Sobre o Desafio

Este projeto foi desenvolvido como exercício prático de Vibe Coding utilizando o Lovable.

A proposta foi criar um aplicativo de finanças pessoais baseado em inteligência artificial e linguagem natural, permitindo que usuários registrem receitas, despesas e metas financeiras por meio de conversas simples e intuitivas.

---

## Resultado Final

Acesse a aplicação:

https://financas-pessoais-leandro.lovable.app

---

## Demonstração

![Agente Financeiro](https://github.com/user-attachments/assets/256dc7bb-3092-4eb9-b23a-cd46c397a89c)

---

# Prompt Final (PRD)

<details>
<summary>Clique para expandir o PRD completo</summary>

## PRD - Agente Financeiro

### Visão do Produto

#### Nome Provisório

Agente Financeiro

#### Proposta de Valor

O Agente Financeiro é um aplicativo de finanças pessoais baseado em conversação em linguagem natural.

Seu objetivo é permitir que qualquer pessoa registre receitas, despesas, acompanhe metas financeiras e receba orientações personalizadas através de uma experiência semelhante a uma conversa com um assistente pessoal.

O produto deve minimizar a necessidade de formulários complexos e reduzir a fricção normalmente associada ao controle financeiro.

### Pilares do Produto

#### 1. Conversação Natural

O usuário deve conseguir realizar a maior parte das ações por meio de mensagens em linguagem natural.

#### 2. Educação Financeira

O sistema deve ensinar conceitos financeiros de maneira leve, contextual e não intimidadora.

#### 3. Design Universal

A experiência deve ser acessível, inclusiva e intuitiva para o maior número possível de pessoas, independentemente de idade, experiência tecnológica, limitações funcionais ou conhecimento financeiro.

### Problema

Muitas pessoas abandonam o controle financeiro porque os aplicativos atuais exigem:

- Cadastro manual excessivo;
- Interfaces complexas;
- Conhecimento financeiro prévio;
- Pouca personalização.

Como consequência, os usuários perdem visibilidade sobre seus gastos e têm dificuldade para atingir seus objetivos financeiros.

### Objetivo do MVP

Validar se uma experiência conversacional reduz a fricção do controle financeiro e aumenta a frequência de registro de transações.

#### Hipóteses

- Usuários preferem registrar gastos via conversa em vez de formulários tradicionais;
- A categorização automática reduz esforço operacional;
- Recomendações personalizadas aumentam o engajamento;
- Metas financeiras simples incentivam hábitos financeiros saudáveis.

### Público-Alvo

#### Público Primário

Pessoas entre 18 e 45 anos que:

- Nunca utilizaram aplicativos financeiros;
- Possuem dificuldade em manter disciplina financeira;
- Desejam uma solução simples e prática.

#### Público Secundário

Pessoas que já utilizam planilhas ou aplicativos financeiros e buscam uma experiência mais rápida e intuitiva.

### Funcionalidades do MVP

#### F1 - Registro de Transações por Chat

O usuário poderá registrar movimentações utilizando linguagem natural.

Exemplos:

- "Gastei R$ 35 com Uber"
- "Recebi R$ 2.500 de salário"
- "Paguei R$ 120 de internet"

O sistema deverá identificar automaticamente:

- Valor;
- Data;
- Tipo da transação;
- Categoria.

#### F2 - Classificação Automática

Categorias iniciais:

- Alimentação;
- Transporte;
- Moradia;
- Saúde;
- Educação;
- Lazer;
- Compras;
- Outros.

#### F3 - Metas Financeiras

Permitir criação e acompanhamento de metas financeiras.

#### F4 - Agente Financeiro

Assistente virtual responsável por analisar os dados financeiros do usuário e gerar recomendações.

#### F5 - Dashboard Simplificado

Apresentar uma visão geral da situação financeira.

Indicadores:

- Saldo atual;
- Receitas do mês;
- Despesas do mês;
- Maiores categorias de gasto;
- Evolução financeira;
- Progresso das metas.

### Design Universal

Garantir que o produto possa ser utilizado por diferentes perfis de usuários com o mínimo de barreiras possível.

Diretrizes:

- Linguagem simples;
- Alto contraste;
- Tipografia legível;
- Interfaces focadas;
- Navegação intuitiva;
- Mobile-first;
- Compatibilidade com tecnologias assistivas.

### Requisitos Não Funcionais

#### Usabilidade

- Curva de aprendizado mínima;
- Navegação intuitiva;
- Feedback imediato.

#### Performance

- Resposta média do chat inferior a 3 segundos;
- Atualização de dados em tempo real.

#### Segurança

- Autenticação segura;
- Criptografia de dados;
- Conformidade com LGPD.

### Métricas de Sucesso

#### Engajamento

- Usuários ativos semanais (WAU);
- Registros por usuário.

#### Retenção

- Retenção em 7 dias;
- Retenção em 30 dias.

#### Valor Percebido

- Quantidade de metas criadas;
- Quantidade de metas concluídas;
- Avaliação do agente financeiro.

### Estratégia de Validação

#### Experimento 1

Validar se o chat é mais intuitivo do que formulários tradicionais.

#### Experimento 2

Monitorar a quantidade de registros realizados durante a primeira semana.

#### Experimento 3

Coletar feedback sobre:

- Facilidade de uso;
- Clareza dos insights;
- Utilidade das recomendações.

</details>

---

# Interações com o Lovable

## Prompt Inicial

```text
Crie um App de Finanças Pessoas com base no seguinte PRD (Product Requirements Document): {PRD}
```

## Refinamento Realizado

```text
Criei uma meta de emergencia, porém quando falei que ganho 2000 de salário e depositei 200 reais pra reserva de emergencia, ele não fez como despesas que saiu dessa conta
```

---

# O Que o Aplicativo Faz

O Agente Financeiro é um aplicativo de finanças pessoais baseado em inteligência artificial e linguagem natural.

Através de uma experiência conversacional, o usuário consegue organizar sua vida financeira sem depender de planilhas ou formulários complexos.

## Funcionalidades Principais

### Registro de Receitas e Despesas via Chat

Permite cadastrar movimentações financeiras utilizando linguagem natural.

Exemplos:

```text
Gastei R$ 100 com videogame
Recebi R$ 2.000 de salário
Paguei R$ 120 de internet
```

O sistema identifica automaticamente:

- Valor;
- Tipo da transação;
- Categoria;
- Data.

### Classificação Automática

As movimentações são categorizadas automaticamente.

Categorias disponíveis:

- Alimentação;
- Transporte;
- Moradia;
- Saúde;
- Educação;
- Lazer;
- Compras;
- Outros.

### Assistente Financeiro Inteligente

O sistema também atua como um agente financeiro virtual.

Capacidades:

- Responder dúvidas sobre finanças pessoais;
- Explicar conceitos de investimentos;
- Fornecer orientações educativas;
- Gerar insights financeiros contextualizados.

### Dashboard Financeiro

Apresenta indicadores financeiros resumidos:

- Receitas do mês;
- Despesas do mês;
- Saldo disponível;
- Resumo financeiro mensal;
- Evolução financeira.

### Histórico de Movimentações

Exibe todas as transações registradas de forma organizada.

### Metas Financeiras

Permite criar e acompanhar objetivos financeiros, como:

- Reserva de emergência;
- Viagem;
- Compra de veículo;
- Entrada de imóvel.

---

# Tecnologias e Conceitos Aplicados

- Inteligência Artificial
- Processamento de Linguagem Natural (NLP)
- Finanças Pessoais
- Assistente Conversacional
- Design Universal
- Mobile First
- Experiência Centrada no Usuário

---

# Reflexão

## O que funcionou bem?

O refinamento do PRD previamente realizado no Copilot ajudou bastante na geração do aplicativo. As instruções ficaram suficientemente claras para que o Lovable gerasse uma primeira versão funcional sem consumir muitos créditos.

## O que não funcionou como o esperado?

Durante o desenvolvimento, a aplicação apresentou erros em alguns momentos e precisou recompilar o projeto para identificar e corrigir problemas antes de continuar a execução.

## O que aprendi sobre conversar com IAs?

As IAs são extremamente úteis quando conseguimos descrever com clareza o problema, o contexto e o comportamento esperado da solução. Quanto mais detalhado e objetivo foi o prompt, melhores foram os resultados gerados.
