# Mural das Disciplinas

- [Link dos slides - aula inaugural](https://docs.google.com/presentation/d/1RbEM4AyDXNAtJfMlo-lWEWMNexcngyNeC-RVq-oPaWY/edit?usp=sharing)
- [Slides projeto](https://docs.google.com/presentation/d/1WhcmPL6o3zCwUjxxyQNF7d44-AmTVTR8ej00qzn1UnQ/edit?usp=sharing)
- [Design Kit - Bulbe (CÓPIA)](https://www.figma.com/design/TKymmHHAUIIoJZnhp52Ijz/Bulbe----IBMEC--Copy-?node-id=46-388&t=dkSu0yUhdN1Rn0aj-1)
- [Modelos de Relatório Scrum](https://github.com/ibmec-tech-2-periodo-2025-2/.github)

## Objetivos

- Apresentar aos alunos conhecimentos para que as seguintes habilidades possam ser desenvolvidas:
- Desenvolver aplicação para consumo/envio de dados de/para APIs web;
- Implementar ambiente de desenvolvimento e teste de front­end;
- Utilizar metologia e práticas de desenvolvimento ágil;
- Controlar versões e atualização coletiva do código da aplicação de forma automatizada.

## Repositórios de Aulas

## Avaliação (Desenvolvimento Web)

| Avaliação             | Peso | Observações                                                           |
|-----------------------|------|-----------------------------------------------------------------------|
| Prova – AP1           | 40%  | Avaliação Parcial 1, individual e sem consulta.                       |
| Prova – AP2           | 40%  | Avaliação Parcial 2, individual e sem consulta. |
| Avaliação Contínua - AC | 20%  | Atividades em sala.                               |

## Avaliação (Projeto em Ciência de Dados I)

| Avaliação             | Peso | Observações                                                           |
|-----------------------|------|-----------------------------------------------------------------------|
| Prova – AP1           | 40%  | Avaliação Parcial 1, individual e sem consulta.                       |
| Prova – AP2           | 40%  | Avaliação Parcial 2, individual e sem consulta. Metade da pontuação vai para a avaliação do projeto. |
| Avaliação Contínua - AC | 20%  | Avaliação do trabalho extensionista.       |

## 📌 Estrutura e Organização do Repositório

### 1. Proteção da Branch `main`

A branch `main` representa a versão mais estável do projeto e **não deve receber commits diretos**. Ela deve ser atualizada **apenas via pull requests (PRs)**, que serão revisadas por colegas e aprovadas antes de serem mescladas.

**Regras para proteger a `main`:**

- Não realizar `push` diretamente na `main`.
- Toda nova funcionalidade ou correção deve ser desenvolvida em uma branch separada e depois enviada via **pull request**.
- Ativar a opção de **proteção da branch main** nas configurações do repositório:
  - Impedir push direto.
  - Exigir revisões de código (code review).
  - Exigir que os checks de CI estejam passando (caso estejam sendo utilizados).

---

## 🌿 Padrão de Nomes de Branches

Para manter o repositório organizado e fácil de navegar, siga a convenção de nomes para branches:

```
tipo/descricao-breve
```

**Tipos comuns:**

- `feature/` → Nova funcionalidade
- `fix/` → Correção de bug
- `refactor/` → Refatoração de código (sem mudança de comportamento)
- `docs/` → Alterações em documentação
- `test/` → Inclusão ou modificação de testes

**Exemplos:**

- `feature/formulario-login`
- `fix/erro-na-responsividade`
- `refactor/componente-header`

---

## 📝 Padrão de Commits

Cada commit deve ser claro e objetivo. Utilize o padrão abaixo:

```
tipo: descrição do que foi feito
```

**Tipos recomendados:**

- `feat:` → Adição de nova funcionalidade
- `fix:` → Correção de bug
- `docs:` → Documentação
- `refactor:` → Refatoração
- `style:` → Formatação de código (espaços, ponto e vírgula etc)
- `test:` → Testes adicionados ou modificados
- `chore:` → Tarefas menores (ex: atualizações de dependência)

**Exemplos:**

- `feat: criar componente de navbar`
- `fix: corrigir erro ao submeter formulário`
- `docs: atualizar README com instruções de instalação`

---

## 🚀 Pull Requests (PRs)

Todo código novo deve ser adicionado por meio de **pull requests**, que devem seguir o seguinte fluxo:

1. Criar uma branch a partir da `main`.
2. Fazer os commits com boas mensagens.
3. Enviar a pull request com uma descrição clara do que foi feito.
4. Solicitar revisão de outro colega.
5. Após aprovação, realizar o merge.

**Dicas:**

- Nomeie a PR com o que foi desenvolvido: `feat: adicionar carousel de imagens`.
- Use o campo de descrição para detalhar mudanças e links para tarefas do projeto (caso estejam usando o painel).

---

## 📋 Painel de Projetos no GitHub

Utilizaremos o **GitHub Projects** para organizar as tarefas do time de forma visual (como um Kanban). Este painel ajuda a:

- Visualizar o que precisa ser feito, o que está em andamento e o que foi finalizado.
- Distribuir tarefas entre os membros da equipe.
- Facilitar o planejamento semanal.

**Colunas recomendadas:**

- 📌 A Fazer (To Do)
- 🔨 Em Progresso (In Progress)
- ✅ Concluído (Done)

**Prática recomendada:** associe cada pull request a uma tarefa do painel. Isso cria rastreabilidade entre o que foi planejado e o que foi entregue.

---

## 🧠 Dicas de Engenharia de Software

- **Commits pequenos e frequentes:** evite grandes blocos de código enviados de uma vez só.
- **Revisão de código:** revise e aprenda com os colegas.
- **Naming claro:** nomeie arquivos, funções e variáveis de forma descritiva.
- **Responsabilidade única:** cada componente/função deve ter um objetivo bem definido.

