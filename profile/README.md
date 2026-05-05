# 🤖 Agents IA CMSOL

Na organização **Agents IA CMSOL**, você encontrará tudo relácionado ao projeto inteligência artificial da CMSOL.  
Nosso objetivo é desenvolver e manter **agentes inteligentes**, **fluxos automatizados** e **soluções integradas** que otimizem processos internos e melhorem a experiência dos usuários.

---

## 🚀 Projetos em Andamento

### - [RosAnI](https://github.com/agentes-ia-cmso/RosAnI-)
Agente de suporte **helpdesk da CMFLEX**, treinado para fornecer respostar completas e inteligentes a dúvidas usando os manuais da empresa.  
- Treinado via **Langflow**
- Integrado ao **n8n** para automação de processamento de interações
- Utiliza banco **PostgreSQL**

### - [Dashboard de feedbacks](https://github.com/agentes-ia-cmso/app-dashboard)
Dashboard em tempo real de estatísticas de feedbacks, acomapnhado de gráficos e página de controle de feedbacks
- Criado via **Antigravity**
- Transformado em container docker com imagem hosteada no github
- Acessa dados em tempo reais do banco de dados **PostgreSQL**

## ⚙️ Fluxos automatizados

### - [Feedback-ordenado](https://github.com/agentes-ia-cmso/Feedback-ordenado)
Fluxo do **n8n** responsável por **ordenar os feedbacks** de interações, seguindo o fluxo:  
**Pergunta → Resposta → Feedback → Agradecimento**  
Auxilia no monitoramento de qualidade e melhoria contínua das respostas do agente.

### - [Revisar Feedback](https://github.com/agentes-ia-cmso/Revisar-Feedback)
Fluxo de análise que revisa e classifica automaticamente os feedbacks dos usuários em Bom, Razoavel ou Ruim, usando um agente de analise de **sentimento** para entender o gráu de satisfação do usuário.

### - [Estatísticas de Menságens](https://github.com/agentes-ia-cmso/ContadorDeMensagem)
Fluxo de estatísticas de uso, por meio desse fluxo são enviados dados em tempo real através do telegram para o nosso time.

### - [Backups Automáticos](https://github.com/agentes-ia-cmso/backups_automaticos)
Fluxos de Backups automáticos do n8n e do LangFlow, inspirado na automação do [Canal do Oskar](https://www.youtube.com/watch?v=dNuVuoPD0Jo).

### - [Reestruturação do banco de dados](https://github.com/agentes-ia-cmso/reestruturacao-banco-de-dados)
Fluxos de manipulação de dados que transformam interações do LangFlow em dados úteis estruturados e organizados, acessados pelo app de dashboard


## 🛑 Projetos Parados

### - [Agente Query Feedback](https://github.com/agentes-ia-cmso/AgenteQueryFeedback)
Agente Capaz de acessar a tabela de interações da RosAnI e fazer querys. **ESSE AGENTE NÃO FUNCIONA CORRETAMENTE**

### - (WIP) [Agente PowerBI](https://github.com/agentes-ia-cmso/Agente-power-BI)
Agente Capaz de acessar a API do Contas a Pagar da CM. **ESSE AGENTE NÃO FUNCIONA CORRETAMENTE**
---

## 🧠 Tecnologias Utilizadas
- **Langflow** – criação e treinamento de agentes IA  
- **n8n** – automação de fluxos e integração de dados  
- **PostgreSQL** – banco de dados relacional  
- **GitHub Projects** – gerenciamento de tarefas e versionamento
- **Antigravity** - IDE de desenvolvimento com IA

---

## 📊 GitHub Projects

A **Agents IA CMSOL** utiliza o **GitHub Projects** como ferramenta central de planejamento e acompanhamento das atividades.  
Nele, organizamos as Features e tarefas em issues que ajudam a gerenciar o ciclo de vida dos fluxos e agentes.

### 🗂️ Estrutura das Colunas

| Coluna | Descrição |
|:--|:--|
| 🕐 **Backlog** | Tarefas planejadas, ainda não priorizadas. |
| 🧾 **Todo** | Atividades aprovadas e prontas para iniciar. |
| ⚙️ **In Progress** | Tarefas atualmente em desenvolvimento. |
| ✅ **Done** | Entregas concluídas e testadas recentemente. |
| 📁 **Done (old)** | Históricos de entregas anteriores, mantidos para referência. |
| 🔧 **Features** | Issues principais, todas as tarefas são sub issues das Features, seguindo a lógica de numeração pai.filho (ex: 10.2). |

---

### 🔄 Fluxos de Trabalho

Cada tarefa segue um fluxo padrão:
1. Criação da **issue** no Backlog como tarefa planejada.  
2. Movimentação para Todo quando for prioridade.  
3. Movimentação para In Progress quando estiver sendo feita no momento (cada pessoa só deve ter uma issue em progress por vez).
  3.1. Enquanto estiver em progresso, os comentários da issue são utilizadas para documentar as atividades, progresso, dificuldades e soluções.
4. Revisão final antes da migração para **Done**.
5. Com o tempo as tarefas antigas são movidas para **Done(old)** a fim de manter a coluna **Done** organizada com foco nas tarefas atuais. 

Esse processo garante **rastreabilidade**, **organização** e **visibilidade** sobre todas as tarefas do time do Proejto IA.

---

## 📬 Contato
Para dúvidas, sugestões ou colaborações, entre em contato com o Pedro (pcxavier@cmsol.net.br) ou com o Flávio (fxavier@cmsol.net.br).
