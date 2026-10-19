[← Voltar ao perfil](../README.md#projetos)

# doit.md

## Notas, tarefas e calendário em um aplicativo PWA

Desenvolvi o doit.md para reunir notas, tarefas, projetos e calendário em um aplicativo web. A interface se adapta ao computador e ao celular, com instalação como PWA.

**Desenvolvimento em pausa e versão hospedada fora do ar.** O código-fonte permanece público. As imagens desta página mostram a aplicação com dados de teste.

[Consultar o código e a arquitetura](https://github.com/lucasmef/doit.md)

### Notas, tarefas e progresso

<img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-09-corrigir-137-138-progresso-visual-icone-modificacao/01-notas-folder-lista-desktop.png" alt="doit.md em desktop: pastas, notas, tarefas concluídas e barras de progresso com dados de teste" width="100%">

O editor inclui Markdown, checklists, histórico de versões e restauração. A organização por pastas e as visualizações de tarefas permitem acompanhar o progresso.

### Uso no celular

<p align="center"><img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-10-reajustar-editor-notas-foco-mobile-recentes/doitmd-notas-progresso-mobile-2026-06-10.png" alt="doit.md em celular: lista de notas e tarefas com progresso, busca e navegação inferior" width="300"></p>

No celular, a navegação reúne criação rápida de notas e acesso às áreas principais. O manifesto PWA define ícones, atalhos e abertura em janela própria.

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

### Manutenção

As GitHub Actions estão desativadas durante a pausa. A retomada depende da revisão das dependências e das pendências técnicas.

### Tecnologias

`Next.js` `React` `TypeScript` `Node.js` `PWA` `SQLite` `PostgreSQL` `Google APIs` `Markdown`

[Ver o Meu Negócio Fácil](./meu-negocio-facil.md) · [Ver o Salomão](./salomao.md) · [Voltar ao perfil](../README.md)
