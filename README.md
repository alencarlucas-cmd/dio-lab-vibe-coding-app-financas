# 💸 App Finanças Pessoais com Vibe Coding do Lucas Felix Alencar

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



# Meu prompt final foi esse (Lucas Felix Alencar:

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

- Seu **prompt final** (PRD);

# Contexto
Quero criar um aplicativo MVP de Organização de Finanças Pessoais com experiência conversacional (chat). O app deve permitir que usuários registrem gastos e receitas por mensagem em linguagem natural, classificar automaticamente transações, criar metas acionáveis via chat (com botão/ação para confirmar criação), oferecer gráficos de despesas por categoria e um agente especialista em investimentos (incluindo consórcio). Público-alvo: iniciantes financeiros no Brasil (BRL), smartphone-first, prefere interação por chat. Manter o código/estrutura já definida; apenas incluir as dicas de melhoria listadas abaixo.

# Problema
Usuários desistem de controlar finanças porque apps exigem muita entrada manual e formulários complexos. Precisamos reduzir fricção com conversas simples, automações e sugestões personalizadas, mantendo clareza sobre método de pagamento (cartão crédito, débito, PIX, dinheiro).

# Público-Alvo
- Primário: Adultos 18–45, iniciantes em finanças, smartphone-first, prefere chat.
- Localização: Brasil (BRL).
- Preferência visual: paleta principal em roxo estilo Nubank (usar hex #8A05BE como cor primária).

# Funcionalidades Obrigatórias (MVP)
1. Registro por chat (valor, categoria, método, data).
2. Classificação automática com correção inline.
3. Resumo e gráficos (pizza e barras) por categoria e método; filtros 7/30/90 dias.
4. Metas via chat com botão "Criar meta" e modal de confirmação.
5. Agente especialista em investimentos e consórcio (explicações e simulações simples).
6. Aba Gastos no Cartão com agrupamento por fatura e previsão de vencimento.
7. Onboarding conversacional (salário, periodicidade, notificações).
8. Privacidade: dados locais/DB; sem integrações bancárias no MVP.

# UX e Interação
- Chat com quick-actions (marcar método, editar categoria, criar meta, ver gráfico).
- Gráficos interativos com drill-down que disparam sugestões no chat.
- Paleta primária: #8A05BE; dark mode; microinterações sutis.

# Entregáveis da IA
- Fluxo de telas; microinterações; persona do agente; backlog priorizado; 10 exemplos de conversas; especificação dos gráficos.

# Métricas
- Precisão de interpretação ≥ 90% (teste 20 usuários).
- Adoção: ≥ 30% registro diário por 7 dias.
- Aceitação de metas: ≥ 50% após 7 dias.
- CSAT ≥ 70.

<img width="532" height="677" alt="image" src="https://github.com/user-attachments/assets/a8acc970-8ae9-4fe0-a963-5f8e3e5b90e2" />
<img width="730" height="937" alt="image" src="https://github.com/user-attachments/assets/35e5627e-5686-4660-a9a6-56cc72dc6c3d" />
<img width="705" height="944" alt="image" src="https://github.com/user-attachments/assets/3b95a293-22de-402f-a8bc-76476e8206d8" />
<img width="710" height="946" alt="image" src="https://github.com/user-attachments/assets/ff07ad20-008d-4ad1-b77b-f07bd6b51dcd" />

#Link do app:  https://grana-papo.lovable.app/

# Resumo

O app é um Organizador Conversacional de Finanças Pessoais (MVP) mobile‑first em português (BRL) que permite registrar gastos e receitas por mensagens em linguagem natural, classificar automaticamente transações, criar e acompanhar metas acionáveis via chat e consultar um agente especialista em investimentos e consórcio. A interface é centrada em chat com quick‑actions, gráficos interativos (pizza e barras) e destaque claro do método de pagamento (Crédito, Débito, PIX, Dinheiro). Foco em reduzir fricção para iniciantes financeiros, usando microinterações e paleta roxa #8A05BE.

Principais funcionalidades (resumido)

Registro por chat: extrai valor, categoria, método e data a partir de mensagens naturais.

Classificação automática com correção inline via quick‑actions.

Metas conversacionais com botão Criar meta e modal de confirmação.

Resumos e gráficos interativos (7/30/90 dias) com drill‑down que geram sugestões no chat.

Agente especialista em investimentos e consórcio com explicações e simulações simples.

Aba de Gastos no Cartão: agrupamento por fatura e previsão de vencimento.

Onboarding conversacional para salário, periodicidade e notificações.

Privacidade: dados locais/DB; sem integrações bancárias no MVP.



# Reflexão

O desenvolvimento do MVP mostrou que conversas simples são a melhor forma de reduzir fricção: transformar formulários em mensagens acelera a adoção.
Manter a estrutura de código existente e adicionar uma camada de NLP permite iterar rápido sem grandes reescritas.

Principais aprendizados

Foco no usuário iniciante: linguagem clara e onboarding guiado aumentam confiança.

#  - O que funcionou bem?  

O app funcionou muito bem: a experiência conversacional reduziu drasticamente a fricção e aumentou a velocidade de registro;
Quero transformar essa solução em produto comercial — a ideia ficou muito boa e tem potencial de mercado. Recomendo começar com um modelo freemium (recursos básicos grátis; premium por assinatura) e testar ofertas pagas de alto valor percebido, como relatórios avançados, simulações de investimento/consórcio detalhadas e metas inteligentes. Paralelamente, validar parcerias educativas ou afiliadas com transparência para o usuário.

 # - O que não funcionou como o esperado?

 Consegui ir corrigindo os bugs, agora é testar com meus amigos e consertar os bugs futuros

 # -O que aprendi sobre conversar com IAs

Concisão e contexto importam  
Mensagens curtas e com contexto (valor, data, método) geram respostas mais precisas. Frases longas e vagas aumentam ambiguidade.

Seja específico sobre o formato esperado  
Dizer exatamente o que quer extrair ou o formato de retorno (ex.: “responda com: valor, categoria, método, data”) melhora a consistência.

 

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
