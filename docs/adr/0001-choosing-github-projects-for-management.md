# ADR 0001: Escolha do GitHub Projects para Gerenciamento de Tarefas

**Data:** 2025-08-23

**Contexto**:
Precisamos de uma ferramenta para gerenciar nosso Product Backlog e Sprints, seguindo a metodologia Scrum. A ferramenta deve ser acessível,
permitir a criação de Histórias de Usuário e tarefas, e ser de fácil visualização para toda a equipe. As opções consideradas foram Trello, Jira e GitHub Projects.

**Decisão**:
Escolhemos usar o **GitHub Projects**.

## Consequências

**Positivas:**
* **Integração Total:** As tarefas (Issues) ficam no mesmo local que o código-fonte, permitindo vincular tarefas a commits e pull requests.
* **Custo Zero:** A ferramenta é gratuita para nosso caso de uso.
* **Fluxo de Trabalho Unificado:** Mantém a equipe dentro do ecossistema do GitHub, simplificando o acesso e a gestão.

**Negativas:**
* Pode ser menos intuitivo para pessoas não-técnicas do que o Trello.
* Não possui relatórios avançados de agilidade (como gráficos de Burndown) nativamente, como o Jira.
