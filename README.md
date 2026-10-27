# 💸 App de Finanças Pessoais do Leandro com Vibe Coding

````markdown
# PRD - Agente Financeiro

## Visão do Produto

### Nome Provisório
Agente Financeiro

### Proposta de Valor

O Agente Financeiro é um aplicativo de finanças pessoais baseado em conversação em linguagem natural.

Seu objetivo é permitir que qualquer pessoa registre receitas, despesas, acompanhe metas financeiras e receba orientações personalizadas através de uma experiência semelhante a uma conversa com um assistente pessoal.

O produto deve minimizar a necessidade de formulários complexos e reduzir a fricção normalmente associada ao controle financeiro.

---

## Pilares do Produto

### 1. Conversação Natural

O usuário deve conseguir realizar a maior parte das ações por meio de mensagens em linguagem natural.

### 2. Educação Financeira

O sistema deve ensinar conceitos financeiros de maneira leve, contextual e não intimidadora.

### 3. Design Universal

A experiência deve ser acessível, inclusiva e intuitiva para o maior número possível de pessoas, independentemente de idade, experiência tecnológica, limitações funcionais ou conhecimento financeiro.

---

## Problema

Muitas pessoas abandonam o controle financeiro porque os aplicativos atuais exigem:

- Cadastro manual excessivo;
- Interfaces complexas;
- Conhecimento financeiro prévio;
- Pouca personalização.

Como consequência, os usuários perdem visibilidade sobre seus gastos e têm dificuldade para atingir seus objetivos financeiros.

---

## Objetivo do MVP

Validar se uma experiência conversacional reduz a fricção do controle financeiro e aumenta a frequência de registro de transações.

### Hipóteses

- Usuários preferem registrar gastos via conversa em vez de formulários tradicionais.
- A categorização automática reduz esforço operacional.
- Recomendações personalizadas aumentam o engajamento.
- Metas financeiras simples incentivam hábitos financeiros saudáveis.

---

## Público-Alvo

### Público Primário

Pessoas entre 18 e 45 anos que:

- Nunca utilizaram aplicativos financeiros;
- Possuem dificuldade em manter disciplina financeira;
- Desejam uma solução simples e prática.

### Público Secundário

Pessoas que já utilizam planilhas ou aplicativos financeiros e buscam uma experiência mais rápida e intuitiva.

---

## Funcionalidades do MVP

### F1 - Registro de Transações por Chat

O usuário poderá registrar movimentações utilizando linguagem natural.

Exemplos:

"Gastei R$ 35 com Uber"

"Recebi R$ 2.500 de salário"

"Paguei R$ 120 de internet"

O sistema deverá identificar automaticamente:

- Valor;
- Data;
- Tipo da transação;
- Categoria.

---

### F2 - Classificação Automática

O sistema deverá categorizar automaticamente as movimentações.

Categorias iniciais:

- Alimentação;
- Transporte;
- Moradia;
- Saúde;
- Educação;
- Lazer;
- Compras;
- Outros.

O usuário poderá corrigir classificações sempre que desejar.

---

### F3 - Metas Financeiras

Permitir criação e acompanhamento de metas.

Exemplos:

- Reserva de emergência;
- Viagem;
- Entrada de imóvel;
- Compra de veículo.

Cada meta deverá possuir:

- Nome;
- Valor-alvo;
- Prazo;
- Percentual de progresso.

---

### F4 - Agente Financeiro

Assistente virtual responsável por analisar os dados financeiros do usuário e gerar recomendações.

Exemplos:

"Você gastou 20% mais com delivery este mês."

"Se economizar R$ 10 por dia poderá guardar aproximadamente R$ 300 por mês."

"Sua meta de viagem está 60% concluída."

---

### F5 - Dashboard Simplificado

Apresentar uma visão geral da situação financeira.

Indicadores:

- Saldo atual;
- Receitas do mês;
- Despesas do mês;
- Maiores categorias de gasto;
- Evolução financeira;
- Progresso das metas.

---

## Fluxos Principais

### Primeiro Acesso

1. Criar conta.
2. Informar objetivo financeiro principal.
3. Receber explicação rápida sobre o funcionamento do aplicativo.
4. Registrar primeira movimentação.

### Uso Diário

1. Usuário envia mensagem.
2. Sistema interpreta intenção.
3. Sistema registra movimentação.
4. Categoria é atribuída automaticamente.
5. Saldo é atualizado.
6. Feedback é apresentado ao usuário.

---

## Telas do MVP

### Tela 1 - Onboarding

Objetivo:

Apresentar a proposta do produto e identificar objetivos financeiros iniciais.

Principais Elementos:

- Boas-vindas;
- Objetivo financeiro;
- Explicação resumida do funcionamento.

---

### Tela 2 - Chat Financeiro

Objetivo:

Centralizar a interação principal do usuário.

Principais Elementos:

- Histórico de conversa;
- Campo de mensagem;
- Sugestões rápidas;
- Confirmação de registros.

---

### Tela 3 - Dashboard

Objetivo:

Exibir resumo financeiro de maneira clara.

Principais Elementos:

- Cards de indicadores;
- Resumo mensal;
- Gráficos simples;
- Insights do agente financeiro.

---

### Tela 4 - Metas Financeiras

Objetivo:

Criar e acompanhar objetivos financeiros.

Principais Elementos:

- Lista de metas;
- Barras de progresso;
- Projeção de conclusão.

---

### Tela 5 - Perfil e Configurações

Objetivo:

Personalização da experiência.

Principais Elementos:

- Categorias personalizadas;
- Preferências;
- Configurações de conta.

---

## Design Universal

### Objetivo

Garantir que o produto possa ser utilizado por diferentes perfis de usuários com o mínimo de barreiras possível.

### Diretrizes

#### Linguagem Simples

- Evitar jargões financeiros;
- Utilizar português claro;
- Explicar conceitos quando necessário;
- Priorizar comunicação conversacional.

#### Acessibilidade Visual

- Alto contraste;
- Tipografia legível;
- Hierarquia visual clara;
- Ícones acompanhados por texto.

#### Acessibilidade Cognitiva

- Reduzir carga mental;
- Interfaces focadas;
- Uma ação principal por tela;
- Feedback claro após cada ação.

#### Navegação

- Fluxos previsíveis;
- Poucos passos para concluir tarefas;
- Consistência visual e funcional.

#### Inclusão Digital

O aplicativo deve funcionar bem para:

- Usuários iniciantes;
- Pessoas idosas;
- Pessoas com baixa educação financeira;
- Usuários com pouca familiaridade tecnológica.

#### Compatibilidade

- Mobile-first;
- Responsivo para tablets e desktops;
- Preparado para leitores de tela;
- Compatível com tecnologias assistivas.

---

## Requisitos Não Funcionais

### Usabilidade

- Curva de aprendizado mínima;
- Navegação intuitiva;
- Feedback imediato.

### Performance

- Resposta média do chat inferior a 3 segundos;
- Atualização de dados em tempo real.

### Segurança

- Autenticação segura;
- Criptografia de dados;
- Conformidade com LGPD.

---

## Métricas de Sucesso

### Engajamento

- Usuários ativos semanais (WAU);
- Registros por usuário.

### Retenção

- Retenção em 7 dias;
- Retenção em 30 dias.

### Valor Percebido

- Quantidade de metas criadas;
- Quantidade de metas concluídas;
- Avaliação do agente financeiro.

---

## Estratégia de Validação

### Experimento 1

Disponibilizar o MVP para 10 a 20 usuários.

Objetivo:

Validar se o chat é mais intuitivo do que formulários tradicionais.

### Experimento 2

Monitorar a quantidade de registros realizados durante a primeira semana.

### Experimento 3

Coletar feedback qualitativo sobre:

- Facilidade de uso;
- Clareza dos insights;
- Utilidade das recomendações.

---

## Entregável Esperado da IA

Ao gerar o MVP, a IA deverá entregar:

- Estrutura das telas;
- Fluxos de navegação;
- Componentes da interface;
- Modelo de dados inicial;
- Dados simulados para demonstração;
- Estratégia de validação do MVP.

A experiência deve ser mobile-first, em português, acessível, intuitiva e alinhada aos princípios de Design Universal.
````

Interações com o Lovable:

> Crie um App de Finanças Pessoas com base no seguinte PRD (Product Requirements Document): {PRD}
> Criei uma meta de emergencia, porém quando falei que ganho 2000 de salário e depositei 200 reais pra reserva de emergencia, ele não fez como despesas que saiu dessa conta

Resultado finao no lovable: https://financas-pessoais-leandro.lovable.app

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/256dc7bb-3092-4eb9-b23a-cd46c397a89c" />

# Agente Financeiro

## Sobre o Projeto

O Agente Financeiro é um aplicativo de finanças pessoais baseado em inteligência artificial e linguagem natural.

A proposta é permitir que qualquer pessoa organize sua vida financeira por meio de conversas simples, eliminando a complexidade de planilhas e formulários tradicionais.

O usuário pode registrar receitas, despesas, acompanhar metas financeiras e receber orientações personalizadas através de um assistente conversacional inteligente.

---

## Principais Funcionalidades

### Registro de Receitas e Despesas via Chat

Permite cadastrar movimentações financeiras utilizando linguagem natural.

Exemplos:

```text
Gastei R$ 100 com videogame
Recebi R$ 2.000 de salário
Paguei R$ 120 de internet
```

O sistema identifica automaticamente:

- Valor
- Tipo da transação
- Categoria
- Data

---

### Classificação Automática

As movimentações são categorizadas automaticamente para facilitar a organização financeira.

Categorias disponíveis:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Outros

O usuário pode revisar ou corrigir categorias quando necessário.

---

### Assistente Financeiro Inteligente

Além de registrar movimentações, o sistema atua como um agente financeiro virtual.

Capacidades:

- Responder dúvidas sobre finanças pessoais
- Explicar conceitos de investimentos
- Fornecer orientações educativas
- Gerar insights financeiros contextualizados

Exemplos:

```text
O que é buy and hold?
Como criar uma reserva de emergência?
Quanto preciso guardar para atingir minha meta?
```

---

### Dashboard Financeiro

Visualização resumida da situação financeira do usuário.

Indicadores principais:

- Receitas do mês
- Despesas do mês
- Saldo disponível
- Resumo financeiro mensal
- Evolução financeira

---

### Histórico de Movimentações

Exibe todas as transações registradas de forma organizada.

Informações apresentadas:

- Descrição da movimentação
- Categoria
- Data
- Valor
- Tipo da operação

---

### Metas Financeiras

Permite criar e acompanhar objetivos financeiros.

Exemplos:

- Reserva de emergência
- Viagem
- Compra de veículo
- Entrada de imóvel

Cada meta possui:

- Nome
- Valor-alvo
- Prazo
- Progresso acumulado

---

## Experiência do Usuário

O produto foi concebido com foco em:

- Conversação natural
- Simplicidade de uso
- Educação financeira
- Design Universal
- Inclusão digital
- Acessibilidade

O objetivo é que qualquer pessoa consiga utilizar a aplicação, independentemente do seu nível de conhecimento financeiro ou familiaridade com tecnologia.

---

## Fluxo Principal

1. O usuário envia uma mensagem.
2. A IA interpreta a intenção da conversa.
3. A movimentação financeira é registrada.
4. A categoria é definida automaticamente.
5. Os indicadores financeiros são atualizados.
6. O assistente fornece feedback imediato.

---

## Tecnologias e Conceitos

- Inteligência Artificial
- Processamento de Linguagem Natural (NLP)
- Finanças Pessoais
- Assistente Conversacional
- Design Universal
- Mobile First
- Experiência Centrada no Usuário

---

## Objetivo do MVP

Validar se uma experiência conversacional pode tornar o controle financeiro mais simples, acessível e eficiente do que os métodos tradicionais baseados em formulários e planilhas.

---

## Visão de Produto

Criar um copiloto financeiro pessoal capaz de ajudar usuários a registrar gastos, desenvolver hábitos financeiros saudáveis, acompanhar objetivos e tomar decisões financeiras mais conscientes através de uma conversa simples e natural.

## Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, os créditos do Lovable nem chegaram a acabar com as interações feitas.

### O que não funcionou como o esperado?
O programa deu erro 2 vezes e teve que recompilar e procurar os erros para poder rodar

### O que aprendeu sobre conversar com IAs?
Elas são muito úteis especialmente se você consegue descrever com precisão o que você precisa no seu projeto
