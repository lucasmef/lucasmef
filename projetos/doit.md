[← Voltar ao perfil](../README.md#user-content-projetos)

# doit.md

## Notas, tarefas e calendário no mesmo aplicativo

PWA de produtividade com editor Markdown, checklists, indicadores de progresso e organização de notas e tarefas por pastas. Aplicação Next.js e CLI Node.js organizadas em monorepo, com pacotes compartilhados.

É uma PWA, com interface para computador e celular e opção de instalação pelo navegador. **A versão online saiu do ar e o desenvolvimento está em pausa.** O código e as capturas do aplicativo continuam públicos.

[Ver o código](https://github.com/lucasmef/doit.md)

### No computador

<img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-09-corrigir-137-138-progresso-visual-icone-modificacao/01-notas-folder-lista-desktop.png" alt="doit.md em desktop: pastas, notas, tarefas concluídas e barras de progresso com dados de teste" width="100%">

As notas podem ter checklists e indicadores de progresso. O editor salva o conteúdo e mantém versões anteriores, que podem ser recuperadas. A imagem mostra o aplicativo com dados de teste.

### No celular

<p align="center"><img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-10-reajustar-editor-notas-foco-mobile-recentes/doitmd-notas-progresso-mobile-2026-06-10.png" alt="doit.md em celular: lista de notas e tarefas com progresso, busca e navegação inferior" width="300"></p>

A interface adapta a navegação à tela menor, com acesso às notas, ao calendário e à captura de novos itens. O manifesto PWA define os ícones, atalhos e a abertura do aplicativo em janela própria.

### Calendário e arquivos locais

<img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-05-22-calendario-adicao-eventos/01-calendar-desktop.png" alt="Calendário mensal da PWA doit.md, em uma captura histórica com ambiente de teste" width="100%">

O projeto tem integração com Google Calendar e permite anexar arquivos pelo Google Drive. A CLI sincroniza o conteúdo com arquivos Markdown locais. As mudanças nesses arquivos passam por revisão antes de voltar ao aplicativo.

### Arquitetura

O monorepo separa a aplicação Next.js, a CLI em Node.js e os pacotes compartilhados. Há módulos para persistência, Markdown, calendário, sincronização e revisão das alterações. O banco pode usar SQLite local ou PostgreSQL, conforme o ambiente.

As telas desta página são registros históricos de teste. Uma retomada do projeto começa pela revisão das dependências e das pendências técnicas; as Actions permanecem desativadas.

`Next.js` `React` `TypeScript` `Node.js` `PWA` `SQLite` `PostgreSQL` `Google APIs`

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
