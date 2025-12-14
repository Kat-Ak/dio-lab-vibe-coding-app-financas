<h1 align="center"> 💰 App de Finanças Pessoais por chat | Vibe Coding com IA 🤖 </h1>
</div>
<p align="center"> <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>
<p align="center">
Este projeto foi desenvolvido como parte de um Desafio da DIO de Vibe Coding, utilizando somente o Copilot Web, exercitando a habilidade de transformar intenções em instruções claras e testando os limites da IA como parceira criativa.
<p align="center">A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural, sem escrever uma única linha de código.

---

## 📄 PRD Refinado no Copilot Web

### Tópicos 

:small_blue_diamond: [Contexto](#1. Contexto)

:small_blue_diamond: [Problema](#funcionalidades)

:small_blue_diamond: [Deploy da Aplicação](#deploy-da-aplicação-dash)

:small_blue_diamond: [Pré-requisitos](#pré-requisitos)

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

... 

### 1. Contexto
Aplicativo de organização de finanças pessoais baseado em conversas em linguagem natural, com foco em Design Universal e acessibilidade.  
Objetivo: simplificar o controle financeiro, tornando-o natural, autoexplicativo e inclusivo.

---

### 2. Problema
**Problema:** Usuários abandonam o controle financeiro por acharem os apps complexos, exigindo entradas manuais e sem orientação personalizada.  
**Solução:** Experiência de conversa acessível, recomendações educativas automáticas, metas e relatórios simples, com foco em clareza visual e conforto cognitivo.

---

### 3. Público-Alvo
- Iniciantes em controle financeiro que buscam simplicidade.  
- Usuários com baixa alfabetização digital que preferem voz ou botões.  
- Pessoas com necessidades de acessibilidade (visuais, cognitivas, motoras).

---

### 4. KPIs
- **Retenção:** 40% dos usuários registram uma segunda despesa em até 3 dias.  
- **Engajamento:** Tempo médio para primeiro registro < 90 segundos.  
- **Acessibilidade:** ≥ 15% dos usuários usam voz ou ajustes de acessibilidade.  
- **Satisfação:** NPS ≥ 7 após 30 dias.  
- **Classificação:** ≥ 75% das categorias sugeridas aceitas sem correção.

---

### 5. Funcionalidades-Chave
#### Entrada de Dados
- Registro flexível via chat/voz/botões.  
- Classificação automática com confirmação.  
- Atalhos para categorias e valores frequentes.

#### Planejament
- Criação e acompanhamento de metas financeiras.  
- Dicas educativas do Agente Financeiro.

#### Visualização
- Relatórios simples: Receitas vs Despesas, Gastos por Categoria, Extrato filtrável.  
- Gráficos acessíveis (cores daltônicas-amigáveis, legendas textuais).

#### Configuações
- Ajustes de acessibilidade (fonte, contraste, modo claro/escuro).  
- Privacidade: exportar histórico, apagar conta, consentimento de dados.

---

### 6. Fluxos Essenciais
- **Registro rápido:** “gastei R$45 no mercado” → extração → cartão de confirmação → salvar.  
- **Correção:** editar transação no extrato.  
- **Metas:** criar meta → definir valor/prazo → acompanhar progresso.  
- **Relatórios:** acessar gráficos e extrato filtrável.

---

### 7. Critérios de Aceitação
- Registro: extração correta em ≥ 90% das entradas simples; confirmação ≤ 2 toques.  
- Classificação: sugestão correta em ≥ 75%; opção de correção sempre disponível.  
- Metas: cálculo de progresso correto; notificação em até 5 segundos após desvio.  
- Relatórios: carregamento < 2s para 12 meses de dados; gráficos legíveis com legendas.  
- Acessibilidade: todos os botões compatíveis com leitores de tela.

---

### 8. Princípios de Design Universal
- Interface clara e legível.  
- Navegação simples e sem sobrecarga.  
- Compatibilidade com leitores de tela e comandos por voz.  
- Feedback multimodal (visual + sonoro, com opção de desativar).

---

### 9. MVP – Entregáveis e Recursos
#### Telas Principais
- Tela inicial (chat).  
- Tela de registro rápido.  
- Tela de metas.  
- Tela de relatórios (Resumo, Categorias, Histórico).  
- Tela de dicas do Agente Financeiro.

#### Recursos Necessários
- Motor de NLP para chat/voz.  
- Algoritmo de classificação automática.  
- Biblioteca de gráficos acessíveis.  
- Sistema de notificações educativas.

---

### 10. Riscos e Mitigação
- **Erro de classificação:** confirmação rápida e histórico editável.  
- **Respostas vagas da IA:** prompts controlados e opções por botão.  
- **Baixa adesão inicial:** onboarding gamificado e dicas iniciais.  
- **Limitações de NLP em português:** fallback para botões pré-definidos.

---

# 📱 Wireframes Textuais – MVP

## Tela Inicial
![Tela Inicial](assets/wireframes/tela-inicial.png)

## Tela de Registro de Gasto
![Tela Registro](assets/wireframes/tela-registro.png)

## Tela de Metas Financeiras
![Tela Metas](assets/wireframes/tela-metas.png)

## Tela de Relatórios
![Tela Relatórios](assets/wireframes/tela-relatorios.png)

## Tela de Dicas do Agente Financeiro
![Tela Dicas](assets/wireframes/tela-dicas.png)

---

## Fluxo Simplificado
1. Início → Chat Financeiro  
2. Registrar gasto → Confirmação de categoria  
3. Definir meta → Barra de progresso  
4. Ver relatórios → Gráficos acessíveis / Extrato  
5. Receber dicas → Ações simples

---

## 💰 Resumo do App de Finanças Pessoais

Um aplicativo simples e acessível para **organizar gastos e metas financeiras via chat e voz**, com foco em **Design Universal, acessibilidade e educação financeira**.  
Transforma o controle de finanças em uma **experiência de conversa natural e inclusiva**, sem planilhas ou interfaces complexas.

### O que o app faz:
- 📌 **Registro de gastos** por texto, voz ou botões, com extração automática de valor, data e categoria.  
- 🧠 **Classificação inteligente** das despesas, com sugestões automáticas e opção de correção rápida.  
- 🎯 **Metas financeiras**: criação de objetivos, acompanhamento de progresso e alertas simples.  
- 📊 **Relatórios acessíveis**: gráficos de Receitas vs Despesas, Gastos por Categoria e extrato filtrável.  
- 🎓 **Dicas educativas** do Agente Financeiro para incentivar hábitos de economia.  
- ♿ **Ajustes de acessibilidade**: fonte legível, contraste alto, cores daltônicas-amigáveis e compatibilidade com leitores de tela.  
- 🔒 **Privacidade garantida**: exportação de histórico e opção de apagar conta.
##
🪄 Em resumo: o app transforma o controle financeiro em uma **experiência de conversa simples, inclusiva e educativa**, ajudando usuários a entender e melhorar sua relação com o dinheiro.

---

## 💭 Reflexão sobre o Processo

### ✅ O que funcionou bem
- A estruturação do PRD em etapas claras e objetivas.
- O uso de linguagem simples e acessível, alinhado ao conceito de Design Universal.  
- A organização dos wireframes textuais, que ajudaram a visualizar o fluxo do app sem precisar de protótipos gráficos.

### ⚠️ O que não funcionou como o esperado
- Algumas respostas iniciais da IA precisaram de ajustes de formatação para se adequar ao estilo do README. 
- A geração de imagens em PNG teve limitações técnicas, exigindo alternativas externas para exportação. 
- Nem todas as sugestões iniciais da IA estavam diretamente aplicáveis ao desafio, sendo necessário filtrar e adaptar.  

### 💡 O que aprendi sobre conversar com IAs
- A IA é ótima para estruturar e revisar documentos, mas precisa de **contexto claro** para entregar resultados relevantes.  
- O processo é **colaborativo**: quanto mais feedback e contexto fornecido, mais útil e preciso é o retorno.
- Conversar com IA não substitui o olhar crítico humano — ela organiza, sugere e provoca reflexões, mas cabe ao usuário decidir o que faz sentido para o projeto.  

---

## 🌟 Conclusão

O **App de Finanças Pessoais por Chat** demonstra como é possível unir **simplicidade, acessibilidade e inteligência artificial** para transformar o controle financeiro em uma experiência mais natural e inclusiva.  

Ao longo do desenvolvimento, o projeto mostrou que:
- É viável criar soluções financeiras sem depender de interfaces complexas ou planilhas tradicionais.  
- O foco em **Design Universal** garante que pessoas com diferentes níveis de alfabetização digital ou necessidades de acessibilidade possam usar o aplicativo.  
- A integração de **IA** permite oferecer dicas educativas e personalizadas, tornando o processo não apenas funcional, mas também motivador.  

Este MVP cumpre o objetivo de ser um **ponto de partida sólido** para evoluções futuras, como integração com bancos digitais, gamificação leve e relatórios mais avançados.  
Mais do que um app, ele representa uma **nova forma de conversar sobre dinheiro**: simples, prática e inclusiva.

---

# Índice 
* [Título e Imagem de capa](#Título-e-Imagem-de-capa)
* [Badges](#badges)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Licença](#licença)
* [Conclusão](#conclusão)

```
> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

```txt

```
> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.
