# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);:
# PRD: Aplicativo de Finanças Pessoais Conversacional

## 1. Objetivo
Um web app focado em dispositivos móveis onde os usuários gerenciam finanças por meio de chat em linguagem natural, em vez de formulários manuais[cite: 1].

## 2. Funcionalidades Principais (MVP)
### A. Interface Conversacional (Chat)
- Campo de entrada para linguagem natural (ex: "Gastei 50 com pizza" ou "Recebi 2000 de salário")[cite: 1].
- Lógica: Extrair {valor}, {descrição} e {categoria} do texto[cite: 1].
- Feedback visual imediato: Um card de resumo aparece após a entrada para confirmação do usuário[cite: 1].

### B. Dashboard
- Exibição de Saldo em tempo real (Receita Total - Despesas Totais)[cite: 1].
- Gráficos Interativos: Gastos mensais por categoria (Gráfico de Rosca/Pizza) e tendências semanais (Gráfico de barras)[cite: 1].
- Ações Rápidas: Atalhos para entradas comuns[cite: 1].

### C. Categorização Inteligente
- Motor de classificação automática (Alimentação, Transporte, Contas, Lazer, Renda)[cite: 1].
- Usuários podem editar manualmente a categoria se a previsão da IA estiver incorreta[cite: 1].

### D. Metas Financeiras
- Criar e acompanhar metas com barras de progresso (ex: "Reserva de Emergência")[cite: 1].
- Conselhos do "Agente Financeiro": Dicas curtas em texto geradas com base nos dados de gastos[cite: 1].

## 3. Navegação e UI/UX
- Barra de Navegação Inferior: [Dashboard, Chat, Histórico, Metas][cite: 1].
- Tema: Limpo, moderno e de alto contraste (acessível)[cite: 1].
- Layout responsivo para dispositivos móveis[cite: 1].

## 4. Restrições Técnicas
- Tech Stack: React, Tailwind CSS, Lucide Icons, componentes Shadcn/UI[cite: 1].
- Gerenciamento de Dados: Estado local ou Supabase (se disponível) para persistência de transações[cite: 1].
- Processamento: Implementação de um parser robusto para lidar com formatos de moeda brasileira (BRL) e verbos financeiros comuns em português[cite: 1].

## 5. Instruções de Implementação para o Lovable
1. Estruturar um app React com uma barra de navegação inferior persistente[cite: 1].
2. Construir a visualização de 'Chat' como o principal método de entrada usando um histórico de mensagens rolável[cite: 1].
3. Usar um estado compartilhado (Context API) para que as entradas do chat atualizem imediatamente os gráficos na visualização do 'Dashboard'[cite: 1].
4. Aplicar uma paleta de cores profissional: Azul Profundo/Indigo para branding, Esmeralda para receitas e Rosa/Coral para despesas[cite: 1].

- Prints ou pequenos vídeos das interações com a IA;



- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
 De modo geral, o app funcionou muito bem.
  
  - O que não funcionou como o esperado?
 Em alguns casos, o app reconheceu de forma incorreta os valores digitados.
  
  - O que aprendeu sobre conversar com IAs?
A qualidade do prompt é fundamental para atingir os resultados esperados.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
