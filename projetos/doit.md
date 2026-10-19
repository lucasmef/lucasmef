[← Voltar ao perfil](../README.md#projetos)

# doit.md

## Notas, tarefas e calendário em um aplicativo PWA

Desenvolvi o doit.md para organizar o trabalho em um único lugar, combinando notas, tarefas, projetos e calendário. A interface adapta a navegação ao desktop e ao celular, e o aplicativo usa um manifesto PWA para instalação em modo independente do navegador.

**Estado atual:** a versão hospedada foi retirada do ar e o desenvolvimento está em pausa. O código-fonte e as capturas históricas permanecem públicos. As imagens abaixo são registros reais da aplicação com dados de teste, não mockups.

[Consultar o código e a arquitetura](https://github.com/lucasmef/doit.md)

### Notas, tarefas e progresso

<img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-09-corrigir-137-138-progresso-visual-icone-modificacao/01-notas-folder-lista-desktop.png" alt="doit.md em desktop: pastas, notas, tarefas concluídas e barras de progresso com dados de teste" width="100%">

O editor trabalha com Markdown e checklists, com histórico de versões e restauração. Pastas e diferentes visualizações ajudam a organizar o conteúdo e acompanhar o progresso das tarefas.

### Uso no celular

<p align="center"><img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-10-reajustar-editor-notas-foco-mobile-recentes/doitmd-notas-progresso-mobile-2026-06-10.png" alt="doit.md em celular: lista de notas e tarefas com progresso, busca e navegação inferior" width="300"></p>

A navegação mobile oferece captura rápida e acesso às áreas principais do aplicativo. O manifesto PWA define nome, ícones, atalhos e abertura em modo standalone.

### Calendário e integrações

<img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-05-22-calendario-adicao-eventos/01-calendar-desktop.png" alt="Calendário mensal da PWA doit.md, em uma captura histórica com ambiente de teste" width="100%">

O projeto inclui integração com Google Calendar por OAuth e anexos pelo Google Drive. Uma CLI sincroniza os itens com arquivos Markdown locais. Alterações podem passar por revisão antes de voltar ao aplicativo, e o histórico permite recuperar versões anteriores.

### Arquitetura e trabalho técnico

| Camada | Implementação |
| :--- | :--- |
| Aplicação | Next.js, React, TypeScript e interface responsiva. |
| PWA | Manifesto, ícones, atalhos e service worker. |
| Dados | SQLite local ou PostgreSQL, conforme o ambiente. |
| Integrações | Google Calendar e Google Drive por OAuth. |
| Sincronização | CLI Node.js e arquivos Markdown com revisão das mudanças. |

O monorepo separa aplicação web, CLI e pacotes de domínio, persistência, Markdown, calendário e auditoria. As instruções e os detalhes estão no [README do repositório](https://github.com/lucasmef/doit.md#estrutura-do-repositorio).

### Preservação do projeto

O projeto é apresentado como uma aplicação desenvolvida que ficou em pausa. Não há demonstração online ativa. As Actions continuam desativadas, e uma retomada exige revisar dependências e pendências técnicas antes de voltar à produção.

### Tecnologias

`Next.js` `React` `TypeScript` `Node.js` `PWA` `SQLite` `PostgreSQL` `Google APIs` `Markdown`

[Ver o Meu Negócio Fácil](./meu-negocio-facil.md) · [Ver o Salomão](./salomao.md) · [Voltar ao perfil](../README.md)
