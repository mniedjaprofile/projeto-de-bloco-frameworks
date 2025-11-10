
# Descrição

<p><b>Prof: </b>Thiago Vieira de Aguiar</p>
<p><b>Aluno: </b>Mayara Araujo</p>
<p><b>Disciplina: </b>Projeto de Bloco Framework - TP1</p>
<p><b>Descrição: </b> Conteúdo autoral conforme análise realizada dos materiais disponiveis de apoio para a atividade.
<p><b>Ferramentas de apoio: </b>Chat GPT e DeepSeek para refinamentos e modelagem do .md</p>
<p><a href="https://github.com/mniedjaprofile/projeto-de-bloco-frameworks" target="_blank">Link GitHub</a></p>


<br>

# 📋 Escopo inicial

<p>Foi escolhido o projeto EventUp, que é uma plataforma web para divulgação/publicação de eventos locais/comunitários (feiras, mutirões, workshops, eventos esportivos etc.).
<p>O sistema terá como propósito principal conectar organizadores e participantes de eventos para um maior engajamento local fortalecendo assim a comunidade.

<br>

# 🎯 Visão Geral do Produto

O principal objetivo da aplicação EventUp é facilitar a divulgação e a participação em eventos locais promovidos pela comunidade fortalecendo o engajamento e a colaboração entre organizadores e participantes de forma automatizada.

Procurando resolver problemas como: <br>

* Baixa visibilidade de eventos relevantes para o público local;

* Comunicação limitada entre organizadores e participantes;

* Ausência de mecanismos automáticos de divulgação e lembretes, que mantenham a comunidade informada;

* Falta de mecanismo para o gerenciamento de eventos pagos e gratuitos.

<br>

# 📍 Marcos Principais

| Marco | Descrição |   |
|-------------|-------------|-------------|
|M1     | Projeto e design system prontos.    | 
|M2     | Autenticação funcionando.      | 
|M3     | CRUD de eventos funcional.      |
|M4     | Busca/filtros implementados      |
|M5     | Notificações e mobile gestures básicos prontos      |
|M6     | Release do MVP      |

<br>

* 📲 ⚛️ Front-end

Interações básicas (Web & Mobile).
<br>

- Clique/tap em cards para ver detalhes.
- Botões: Participar / Favoritar / Compartilhar / Inscrever.
- Modais: formulário de criação/edição de evento; confirmação de exclusão.
- Feedback visual: loaders, toasts/alerts, validação inline de formulários.
- Filtros dinâmicos com debounce em busca.
- Drag & drop (opcional) para reordenar imagens em criação de evento.
- Notificações: in-app + push (mobile).
- Gestos mobile: swipe right = favoritar; swipe left = quick actions; pull-to-refresh na listagem de eventos; long-press para opções contextuais (ex: salvar offline).  

Para interações fluídas

- Minimizar cargas sincronas (lazy loading, skeletons);
- Transições e microinterações suaves (CSS/Framer Motion);
- Indicação clara de estados (offline, carregando, erro);
- Aderência a padrões de acessibilidade (contrast ratio, focus order, aria labels).

<br>

# ⚙️ Funcionalidades Mínimas (MVP)

Entregar uma plataforma que permita a realização de ações básicas nesta primeira fase e esteja preparada para receber novas funcionalidades ao longo do tempo (arquitetura escalável).

* Criar e gerenciar eventos;
* Autenticação de usuário<br>   
    - Organizador<br>
    - Participante 
* Filtros dinâmicos para busca de eventos;
* Promover engajamento entre membros da comunidade. 

<br> 

# 📁 Gestão Ágil do Projeto

<b> 💼 Estratégia de Sprints</b><br>
* <b>Sprints: </b><br> 
Quinzenais (2 semanas) - Facilitar entregas incrementais com feedback frequente.

<br>

<b> 📈 Planejamento</b><br>
* <b>Eventos Scrum</b><br> 
Sprint Planning, Daily Scrum (15min), Sprint review, Sprint Retrospective, Backlog Refinement (contínuo): detalhamento de histórias.

<br>

<b>🏗️ Sprint Planning</b><br>

* Equipe quebra Epicos em Histórias de Usuário + tasks técnicas (frontend, backend, infra, testes)

<br>

<b>✍ Definições de tarefas</b>

* Task: Descrição, critério de aceitação, estimativa (story points ou ideal hours), responsável e "Definition od Done".

<br>

<b>📊 Métricas e DOR e DoD</b><br>

Critérios de aceitação claros, estimativas e limitações de WIP; integração continua; revisão de deploys frequentes para colher feedback real.

* <b>Definição de Pronto (Ready) - DoR</b><br>
 User Story bem escrita e compreensível<br>
 Critérios de aceitação definidos<br>
 Dependências identificadas<br>
 Design/wireframe disponível<br>
 Aceite do PO <br>

* <b>Definição de Concluído (Done) - DoD</b></br>
  Código desenvolvido e revisado<br>
  Testes unitários implementados<br>
  Testes de integração passando<br>
  Documentação atualizada<br>
  Deploy em ambiente de teste<br>
  Aceite do PO

<br>

<b>🔧 Ferramentas</b><br>

* Trello  
* Jira
* Notion 

<br>

<b>👥 Caracteristicas do time</b><br>

* Auto-organização - cada um se compromete com alguma tarefa;

* SM fica atendo a qualquer impedimento, auxiliando no desbloqueio das atividades quando necessário.

* Uso de board kanaban/Scrum em uma das ferramentas listadas como permitidas para o projeto, com as seguintes raias: 
    Backlog | To Do (Sprint) | In Progress | In Review | Done.

<br>

<b>🎭 Definição de Papéis</b>

<br>

| Papel | Responsábilidade |   |
|-------------|-------------|-------------|
|Product Owner (PO)     |Responsável por definir a visão do produto, priorizar o backlog e representar o cliente.    | 
| Scrum Master     | Garante o uso correto do framework Scrum, remove impedimentos e facilita o progresso do time.      | 
| Development Team      | Responsável pela implementação técnica das funcionalidades (frontend, backend, integração).      |

<br>

# 📚 Product Backlog

| Épico | Descrição |  |
|-------------|-------------|-------------|
|E1 – Gestão de Usuários e Autenticação     |Cadastro, login e diferenciação entre organizadores e participantes.    |     |
|E2 – CRUD da Gestão de Eventos     | Criar, editar, listar e excluir eventos.      |       |
|E3 – Inscrições e Participação       | Implementar filtros dinâmicos (categoria, local, data).      |      |

<br><br><br>

# 📝 User Stories 

🎪 Épico 1: Gestão de Usuários e Autenticação<br>
🧩 Feature 1.1: Gestão de Usuários e Autenticação

* US-001: Como usuário, quero me cadastrar na plataforma para acessar os recursos do EventUp
  - Critérios de Aceite
    - Formulário com nome, email, senha e tipo de perfil (Organizador/participante)  
    - Validação de email único
    - Validação de complexidade de senha(minimo de 8 caracteres, 1 caracter especial e um numemro).

* US-002: Como usuário, quero fazer login na plataforma para acessar minha conta
  - Critérios de Aceite
    - Login com email e senha
    - Redirecionamento de acordo com perfil

🧩 Feature 1.2: Perfis de Usuário

* US-004: Como organizador, quero ter um perfil específico para criar eventos
* US-005: Como participante, quero ter um perfil para me inscrever em eventos

<br>

🎪 Épico 2: CRUD da Gestão de Eventos<br>
🧩 Feature 2.1: Criação de Eventos

* US-006: Como organizador, quero criar eventos para divulgar minhas atividades.
    - Critérios de Aceite
        - Formulário com: Titulo, descrição, data, hora, local, capacidade máxima, tipo de evento (Gratuito/Pago) e categoria.
        - Upload de imagem do evento
        - Definição de capacidade máxima
        - Definição do tipo de evento (Gratuito/Pago)
        - Definição de categorias (feiras, mutirões, workshops, eventos esportivos etc)

* US-007: Como organizador, quero editar meus eventos para corrigir informações
* US-008: Como organizador, quero cancelar eventos para informar os participantes 

🧩 Feature 2.2: Listagem e busca de Eventos

* US-009: Como participante, quero visualizar eventos próximos para descobrir atividades
    - Critérios de Aceite
        - Listagem paginada de eventos
        - Filtros por data, localização, categoria
        - Busca por palavras-chave
        - Ordenação por relevancia/data

* US-010: Como participante, quero ver detalhes completos do evento para decidir minha participação

🎪 Épico 3: Inscrições e Participação<br>
🧩 Feature 3.1: Sistema de Inscrições

* US-011: Como participante, quero me inscrever em eventos para participar
    - Critérios de Aceite
        - Botão de inscrição em eventos com vagas
        - Confirmação de inscrição
        - Limite de vagas respeitado
        - Lista de eventos que participei

* US-012: Como participante, quero cancelar minha inscrição quando necessário

🧩 Feature 3.2: Gestão de Participantes

* US-013: Como organizador, quero visualizar a lista de inscritos no meu evento
* US-014: Como organizador, quero exportar a lista de participantes

<br>

# ⏱️ Sprints Planejadas (Roadmap Resumido/Macro)

<b>📦 Release 1.0</b>

| 🔄🏆 Sprint 0 (Pré-sprint/1 semana) |
|------------------------------------|
| Setup do repositório, configuração de CI/CD básico, ambiente de desenvolvimento, definição de padrões (lint, prettier), roteiros e wireframes iniciais. |

<br>

| 🔄🏆 Sprint 1 (Semanas 2-3) | Objetivo |
|-----------------------------|-----------|
| **Fundação** | Sistema básico de autenticação e estrutura do projeto |

| 🧩 Task | ⏱️ Estimativa | 👩‍💻 Responsável |
|----------|----------------|----------------|
| Configuração do ambiente (Frontend/Backend) | 8h | Dev Team |
| Modelagem do banco de dados | 6h | Backend |
| Implementação cadastro de usuários | 13h | Full Stack |
| Implementação sistema de login | 8h | Full Stack |
| Layout base da aplicação | 12h | Frontend |
| Testes unitários básicos | 5h | QA |

<b>Definição de Feito (done)</b></br>

 ✅ Código revisado e aprovados<br>
 ✅ Tesets de sucesso<br>
 ✅ Documentação atualizada<br>
 ✅ Deploy em ambiente de desenvolvimento

<br>

| 🔄🏆 Sprint 2 (Semanas 4-5) | Objetivo |
|-----------------------------|-----------|
| **CRUD de Eventos** | CRUD de eventos (criar/editar/excluir/listar), formulários reutilizáveis, upload de imagem. |

| 🧩 Task | ⏱️ Estimativa | 👩‍💻 Responsável |
|----------|----------------|----------------|
| Model Event no backend | 4h | Backend |
| API CRUD de eventos | 12h | Backend |
| Interface criação de eventos | 16h | Frontend |
| Listagem de eventos | 10h | Frontend |
| Upload de imagens | 8h | Full Stack |
| Validações e tratamento de erros | 6h | Full Stack |

<br>

| 🔄🏆 Sprint 3 (Semanas 5-6) | Objetivo |
|-----------------------------|-----------|
| **Inscrições e Busca** | Implementação do sistema de inscrições e mecanismos de busca e filtros para eventos. |

| 🧩 Task | ⏱️ Estimativa | 👩‍💻 Responsável |
|----------|----------------|----------------|
| Model Inscrição | 3h | Backend |
| API de inscrições | 10h | Backend |
| Interface de inscrição | 8h | Frontend |
| Sistema de busca e filtros | 12h | Full Stack |
| Dashboard do usuário | 10h | Frontend |
| Testes de integração | 8h | QA |


<br>

#  ⚛️ ReactJS e React Native Frameworks

<b>🌐 ReactJs (web)</b>

- Componentização: facilita criar componentes reutilizáveis (cards, formulários, modais) e um design system consistente.

- Estado previsível: integrável com Redux Toolkit para gerenciar estado global de eventos, autenticação e favoritos.

- Ecosistema forte: roteamento (React Router), testes (Testing Library), storybook, bibliotecas UI (Headless UI / Radix) e suporte a otimizações (memo, lazy, suspense).

- Desempenho e SEO parcial: com SSR/SSG (Next.js) se desejar melhorar indexação e performance inicial.

<br>

<b>📱 React Native (mobile)</b>

- Código compartilhado: lógica de negócio (validações, cliente API) facilmente reaproveitável entre web e mobile.

- Experiência nativa: acesso a notificações push, armazenamento local, permissões, gestos nativos e performance adequada para gestos (react-native-gesture-handler, reanimated).

- Ciclo de desenvolvimento rápido: hot reload, grande comunidade e bibliotecas para autenticação e integração com serviços (Firebase).

- UX consistente: com design system adaptado (tokens de cores/tipografia) possibilita interfaces coerentes entre plataformas.

<br>

#  🚀 **Backlog Futuro – Evolução do Projeto EventUp** 

| **Tema Estratégico** | **Descrição Resumida / Foco de Evolução** |
|----------------------|--------------------------------------------|
| 🧭 **DevOps e Entrega Contínua** | Implementar pipelines automatizados de CI/CD, monitoramento de deploys e integração com ferramentas de versionamento para garantir entregas ágeis e seguras. |
| 📊 **Métricas de Sucesso** | Definir e acompanhar KPIs como taxa de participação em eventos, engajamento dos usuários e tempo médio de uso da plataforma. |
| 📈 **Métricas do Produto** | Analisar comportamento dos usuários e performance do sistema para direcionar melhorias baseadas em dados (data-driven decisions). |

<br>

| 🧩 **Roadmap de Releases** | **Funcionalidades Planejadas** | **Duração Estimada** |
|----------------------------|--------------------------------|----------------------|
| 🔄 **Release 1.1** | Sistema de lembretes, compartilhamento de eventos, favoritos e melhorias de UX. | 4 semanas |
| ⏳ **Release 1.2** | Sistema de pagamentos, notificações push, dashboard analítico e API pública. | 4 semanas |
