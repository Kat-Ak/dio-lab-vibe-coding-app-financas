<h1 align="center">💵 App de Finanças Pessoais por chat | Vibe Coding com IA 🤖</h1>
</div>
<p align="center"> <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=yellow&style=for-the-badge"/>
<p align="center">
<div align="center">

>
> <p align="center">Este projeto foi desenvolvido como parte de um Desafio da DIO de Vibe Coding, utilizando somente o Copilot Web, exercitando a habilidade de transformar > intenções em instruções claras e testando os limites da IA como parceira criativa.
> <p align="center">A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural, sem escrever uma única linha de código.

---

 <div align="center">
📄![PRD Refinado no Copilot Web](img.shields.io)
</div>




### 📄 PRD Refinado no Copilot Web
##
#### 1. Contexto
Aplicativo de organização de finanças pessoais baseado em conversas em linguagem natural, com foco em Design Universal e acessibilidade.  
Objetivo: simplificar o controle financeiro, tornando-o natural, autoexplicativo e inclusivo.

---

#### 2. Problema
**Problema:** Usuários abandonam o controle financeiro por acharem os apps complexos, exigindo entradas manuais e sem orientação personalizada.  
**Solução:** Experiência de conversa acessível, recomendações educativas automáticas, metas e relatórios simples, com foco em clareza visual e conforto cognitivo.

---

#### 3. Público-Alvo
- Iniciantes em controle financeiro que buscam simplicidade.  
- Usuários com baixa alfabetização digital que preferem voz ou botões.  
- Pessoas com necessidades de acessibilidade (visuais, cognitivas, motoras).

---

#### 4. KPIs
- **Retenção:** 40% dos usuários registram uma segunda despesa em até 3 dias.  
- **Engajamento:** Tempo médio para primeiro registro < 90 segundos.  
- **Acessibilidade:** ≥ 15% dos usuários usam voz ou ajustes de acessibilidade.  
- **Satisfação:** NPS ≥ 7 após 30 dias.  
- **Classificação:** ≥ 75% das categorias sugeridas aceitas sem correção.

---

#### 5. Funcionalidades-Chave
##### Entrada de Dados
- Registro flexível via chat/voz/botões.  
- Classificação automática com confirmação.  
- Atalhos para categorias e valores frequentes.

##### Planejamento
- Criação e acompanhamento de metas financeiras.  
- Dicas educativas do Agente Financeiro.

##### Visualização
- Relatórios simples: Receitas vs Despesas, Gastos por Categoria, Extrato filtrável.  
- Gráficos acessíveis (cores daltônicas-amigáveis, legendas textuais).

##### Configuações
- Ajustes de acessibilidade (fonte, contraste, modo claro/escuro).  
- Privacidade: exportar histórico, apagar conta, consentimento de dados.

---

#### 6. Fluxos Essenciais
- **Registro rápido:** “gastei R$45 no mercado” → extração → cartão de confirmação → salvar.  
- **Correção:** editar transação no extrato.  
- **Metas:** criar meta → definir valor/prazo → acompanhar progresso.  
- **Relatórios:** acessar gráficos e extrato filtrável.

---

#### 7. Critérios de Aceitação
- Registro: extração correta em ≥ 90% das entradas simples; confirmação ≤ 2 toques.  
- Classificação: sugestão correta em ≥ 75%; opção de correção sempre disponível.  
- Metas: cálculo de progresso correto; notificação em até 5 segundos após desvio.  
- Relatórios: carregamento < 2s para 12 meses de dados; gráficos legíveis com legendas.  
- Acessibilidade: todos os botões compatíveis com leitores de tela.

---

#### 8. Princípios de Design Universal
- Interface clara e legível.  
- Navegação simples e sem sobrecarga.  
- Compatibilidade com leitores de tela e comandos por voz.  
- Feedback multimodal (visual + sonoro, com opção de desativar).

---

#### 9. MVP – Entregáveis e Recursos
##### Telas Principais
- Tela inicial (chat).  
- Tela de registro rápido.  
- Tela de metas.  
- Tela de relatórios (Resumo, Categorias, Histórico).  
- Tela de dicas do Agente Financeiro.

##### Recursos Necessários
- Motor de NLP para chat/voz.  
- Algoritmo de classificação automática.  
- Biblioteca de gráficos acessíveis.  
- Sistema de notificações educativas.

---

#### 10. Riscos e Mitigação
- **Erro de classificação:** confirmação rápida e histórico editável.  
- **Respostas vagas da IA:** prompts controlados e opções por botão.  
- **Baixa adesão inicial:** onboarding gamificado e dicas iniciais.  
- **Limitações de NLP em português:** fallback para botões pré-definidos.

---

### 📱 Wireframe Textual – MVP

#### 1️⃣ Tela Inicial (Chat Financeiro)
✨ **Topo:** "Seu Controle Financeiro"  
💬 **Centro:** caixa de conversa (texto grande, contraste alto)  
🎤 **Botão principal:** “Falar gasto” (centralizado e destacado)  
⚡ **Atalhos abaixo:** Registrar gasto | Ver relatórios | Definir meta 

---

#### 2️⃣ Tela de Registro de Gasto
📝 **Mensagem detectada:** “Comprei pão por R$10”  
💳 **Confirmação:**  
- Valor: R$10  
- Categoria sugerida: 🍞 Alimentação  
✅ **Botões:** Confirmar | Alterar  

---

#### 3️⃣ Tela de Metas Financeiras
🎯 **Pergunta inicial:** “Qual meta você quer alcançar?”  
📌 **Sugestões em botões:**  
- 💵 Economizar R$200/mês  
- ✈️ Guardar para viagem  
- 🛠️ Criar meta personalizada  
📊 **Barra de progresso:** visual simples, cores contrastantes, texto “Você já alcançou 20% da meta”  

---

#### 4️⃣ Tela de Relatórios
📂 **Abas superiores:** Resumo | Categorias | Histórico  
📈 **Resumo:** gráfico de barras Receitas vs Despesas (alto contraste, legendas grandes)  
🥧 **Categorias:** gráfico circular ou barras, paleta daltônica-amigável  
📜 **Histórico:** lista de transações com fonte grande, botões “Anterior / Próximo”  

---

#### 5️⃣ Tela de Dicas do Agente Financeiro
💡 **Dica:** “Você pode economizar R$50 se reduzir gastos com delivery.”  
🙂 **Ícone amigável:** personagem simples  
👉 **Botões de ação:** Quero tentar | Me lembre depois  

---

#### 🔄 Fluxo Simplificado
1. 🚀 Início → Chat Financeiro  
2. 📝 Registrar gasto → Confirmação de categoria  
3. 🎯 Definir meta → Barra de progresso  
4. 📊 Ver relatórios → Gráficos acessíveis / Extrato  
5. 💡 Receber dicas → Ações simples  

---

### 📊 Resumo dos Wireframes

| Tela                        | Elementos principais                                                                 | Objetivo                                                                 |
|-----------------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| 🏠 **Tela Inicial**         | Título, caixa de conversa, botão 🎤 “Falar gasto”, atalhos (Registrar, Relatórios, Meta) | Ponto de entrada rápido para registrar gastos e acessar funções principais |
| 📝 **Registro de Gasto**    | Mensagem detectada, cartão de confirmação (valor + categoria), botões Confirmar/Alterar | Facilitar o registro de despesas com categorização automática             |
| 🎯 **Metas Financeiras**    | Pergunta inicial, botões de sugestão, barra de progresso com porcentagem              | Definir e acompanhar metas de economia ou objetivos financeiros           |
| 📊 **Relatórios**           | Abas (Resumo, Categorias, Histórico), gráficos de barras/circular, lista de transações | Visualizar desempenho financeiro e histórico de gastos                    |
| 💡 **Dicas do Agente**      | Mensagem curta de economia, ícone amigável, botões Quero tentar/Me lembre depois       | Oferecer recomendações práticas para melhorar hábitos financeiros         |
| 🔄 **Fluxo Simplificado**   | Sequência: Início → Registrar → Meta → Relatórios → Dicas                            | Mostrar o caminho lógico de uso do aplicativo                             |
---

### 📊 Resumo dos Wireframes

| Tela             | Elementos principais                                  | Objetivo                                    |
|------------------|-------------------------------------------------------|---------------------------------------------|
| 🏠 Inicial       | Título, conversa, botão 🎤, atalhos                   | Entrada rápida e acesso às funções           |
| 📝 Registro      | Mensagem, valor, categoria, botões                    | Registrar despesas com categorização fácil   |
| 🎯 Metas         | Pergunta, botões de sugestão, barra de progresso      | Definir e acompanhar metas financeiras       |
| 📊 Relatórios    | Abas, gráficos, histórico                             | Visualizar desempenho e histórico            |
| 💡 Dicas         | Mensagem curta, ícone, botões                         | Recomendações práticas de economia           |
| 🔄 Fluxo         | Sequência lógica de telas                             | Mostrar caminho de uso do aplicativo         |

---

### 💰 Resumo do App de Finanças Pessoais

Um aplicativo simples e acessível para **organizar gastos e metas financeiras via chat e voz**, com foco em **Design Universal, acessibilidade e educação financeira**.  
Transforma o controle de finanças em uma **experiência de conversa natural e inclusiva**, sem planilhas ou interfaces complexas.

#### O que o app faz:
- 📌 **Registro de gastos** por texto, voz ou botões, com extração automática de valor, data e categoria.  
- 🧠 **Classificação inteligente** das despesas, com sugestões automáticas e opção de correção rápida.  
- 🎯 **Metas financeiras**: criação de objetivos, acompanhamento de progresso e alertas simples.  
- 📊 **Relatórios acessíveis**: gráficos de Receitas vs Despesas, Gastos por Categoria e extrato filtrável.  
- 🎓 **Dicas educativas** do Agente Financeiro para incentivar hábitos de economia.  
- ♿ **Ajustes de acessibilidade**: fonte legível, contraste alto, cores daltônicas-amigáveis e compatibilidade com leitores de tela.  
- 🔒 **Privacidade garantida**: exportação de histórico e opção de apagar conta.
##
📚 Em resumo: o app transforma o controle financeiro em uma **experiência de conversa simples, inclusiva e educativa**, ajudando usuários a entender e melhorar sua relação com o dinheiro.

---

### 💭 Reflexão sobre o Processo

#### ✅ O que funcionou bem
- A estruturação do PRD em etapas claras e objetivas.
- O uso de linguagem simples e acessível, alinhado ao conceito de Design Universal.  
- A organização dos wireframes textuais, que ajudaram a visualizar o fluxo do app sem precisar de protótipos gráficos.

#### ⚠️ O que não funcionou como o esperado
- Algumas respostas iniciais da IA precisaram de ajustes de formatação para se adequar ao estilo do README. 
- A geração de imagens em PNG teve limitações técnicas, exigindo alternativas externas para exportação. 
- Nem todas as sugestões iniciais da IA estavam diretamente aplicáveis ao desafio, sendo necessário filtrar e adaptar.  

#### 💡 O que aprendi sobre conversar com IAs
- A IA é ótima para estruturar e revisar documentos, mas precisa de **contexto claro** para entregar resultados relevantes.  
- O processo é **colaborativo**: quanto mais feedback e contexto fornecido, mais útil e preciso é o retorno.
- Conversar com IA não substitui o olhar crítico humano — ela organiza, sugere e provoca reflexões, mas cabe ao usuário decidir o que faz sentido para o projeto.  

---

### 🌟 Conclusão

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
> boas ideias e prompts em conceitos funcionais que simulam um produto real.
---
###

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

# 📱 Wireframe Textual – MVP com Badges Coloridos

## 1️⃣ Tela Inicial
![Tela Inicial](https://img.shields.io/badge/Tela%20Inicial-Entrada%20Rápida-brightgreen)
- 🏷️ "Seu Controle Financeiro"
- 🎤 Botão principal: Falar gasto
- ⚡ Atalhos: Registrar | Relatórios | Meta

---

## 2️⃣ Registro de Gasto
![Registro de Gasto](https://img.shields.io/badge/Registro%20de%20Gasto-Despesa%20Confirmada-blue)
- 📝 Mensagem: "Comprei pão R$10"
- 💳 Confirmação: Valor R$10 | Categoria 🍞 Alimentação
- ✅ Botões: Confirmar | Alterar

---

## 3️⃣ Metas Financeiras
![Metas Financeiras](https://img.shields.io/badge/Metas%20Financeiras-20%25%20Alcançado-orange)
- 🎯 Pergunta: "Qual meta você quer alcançar?"
- 📌 Botões: Economizar R$200/mês | Guardar viagem | Meta personalizada
- 📊 Progresso: 20% alcançado

---

## 4️⃣ Relatórios
![Relatórios](https://img.shields.io/badge/Relatórios-Análise%20Financeira-purple)
- 📂 Abas: Resumo | Categorias | Histórico
- 📈 Gráfico: Receitas vs Despesas
- 🥧 Categorias: Alimentação, etc.
- 📜 Histórico: lista de gastos + navegação

---

## 5️⃣ Dicas do Agente
![Dicas](https://img.shields.io/badge/Dicas%20Financeiras-Economia%20Prática-yellow)
- 💡 Dica: "Economize R$50 reduzindo delivery"
- 🙂 Ícone amigável
- 👉 Botões: Quero tentar | Me lembre depois

---

## 🔄 Fluxo Simplificado
![Fluxo](https://img.shields.io/badge/Fluxo%20Simplificado-Caminho%20do%20App-lightgrey)
1. 🚀 Início → Chat  
2. 📝 Registrar gasto → Confirmação  
3. 🎯 Definir meta → Progresso  
4. 📊 Relatórios → Gráficos / Extrato  
5. 💡 Dicas → Ações simples

# 🎨 Linha de Badges Coloridos

![Verde](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Azul](https://img.shields.io/badge/Registro-OK-blue)
![Laranja](https://img.shields.io/badge/Meta-20%25-orange)
![Cinza](https://img.shields.io/badge/CPR-Cinza-lightgrey)

# 📱 Wireframe Textual – MVP (Badges em uma só cor)

![Tela Inicial](https://img.shields.io/badge/Tela%20Inicial-Entrada%20Rápida-blue)
![Registro de Gasto](https://img.shields.io/badge/Registro%20de%20Gasto-Despesa%20Confirmada-blue)
![Metas Financeiras](https://img.shields.io/badge/Metas%20Financeiras-20%25%20Alcançado-blue)
![Relatórios](https://img.shields.io/badge/Relatórios-Análise%20Financeira-blue)
![Dicas](https://img.shields.io/badge/Dicas%20Financeiras-Economia%20Prática-blue)
![Fluxo](https://img.shields.io/badge/Fluxo%20Simplificado-Caminho%20do%20App-blue)

# 📱 Wireframe Textual – MVP (Badges Verdes)

![Tela Inicial](https://img.shields.io/badge/Tela%20Inicial-Entrada%20Rápida-brightgreen)  
🏠 Ponto de entrada com título, botão 🎤 e atalhos principais.

![Registro de Gasto](https://img.shields.io/badge/Registro%20de%20Gasto-Despesa%20Confirmada-brightgreen)  
📝 Registrar despesas com valor, categoria e botões de confirmação.

![Metas Financeiras](https://img.shields.io/badge/Metas%20Financeiras-20%25%20Alcançado-brightgreen)  
🎯 Definir metas, acompanhar progresso e visualizar barra percentual.

![Relatórios](https://img.shields.io/badge/Relatórios-Análise%20Financeira-brightgreen)  
📊 Gráficos de receitas vs despesas, categorias e histórico de transações.

![Dicas](https://img.shields.io/badge/Dicas%20Financeiras-Economia%20Prática-brightgreen)  
💡 Recomendações rápidas para melhorar hábitos financeiros.

![Fluxo](https://img.shields.io/badge/Fluxo%20Simplificado-Caminho%20do%20App-brightgreen)  
🔄 Sequência lógica: Início → Registro → Metas → Relatórios → Dicas.

![Inicial](https://img.shields.io/badge/-Tela%20Inicial-brightgreen)
![Registro](https://img.shields.io/badge/-Registro%20de%20Gasto-brightgreen)
![Metas](https://img.shields.io/badge/-Metas%20Financeiras-brightgreen)
![Relatórios](https://img.shields.io/badge/-Relatórios-brightgreen)
![Dicas](https://img.shields.io/badge/-Dicas%20Financeiras-brightgreen)
![Dicas](https://img.shields.io/badge/Dicas%20Financeiras-Economia%20Prática-yellow)
```diff
- Texto em vermelho (com um sinal de menos na frente)
+ Texto em verde (com um sinal de mais na frente)
! Texto em laranja (com um ponto de exclamação na frente)
# Texto em cinza
