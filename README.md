# HelpDesk Fácil

Sistema simples de chamados de suporte técnico feito com **HTML, CSS e JavaScript puros**, tudo em um único arquivo (`index.html`). Projeto acadêmico que demonstra as estruturas de dados **Fila (FIFO)** e **Pilha (LIFO)**.

## Como abrir

Abra o `index.html` no navegador. Não precisa instalar nada.

Online (GitHub Pages): `https://SEU-USUARIO.github.io/helpdesk-facil/`

## Funcionalidades

- Dashboard com chamados pendentes, atendidos, total e ações no histórico
- Cadastro de chamados (solicitante, título e descrição)
- Atendimento do próximo chamado
- Histórico de operações com opção de visualizar e desfazer a última ação
- Dados salvos no LocalStorage

## Estruturas de dados

| Estrutura | Array | Inserção | Remoção |
|-----------|-------|----------|---------|
| Fila (`fila`) | `push` | `enqueue` (fim) | `dequeue` (início, com `shift`) |
| Pilha (`historico`) | `push` | `push` (topo) | `pop` (topo) |
