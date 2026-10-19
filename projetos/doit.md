[← Voltar ao perfil](../README.md#user-content-projetos)

# doit.md

## Notas, tarefas e calendário no mesmo aplicativo

Aplicativo de produtividade que reúne notas, tarefas e calendário. O editor Markdown oferece checklists e indicadores de progresso, com organização do conteúdo por pastas.

A interface se adapta a computadores e celulares, com instalação pelo navegador como PWA. **A versão online saiu do ar e o desenvolvimento está em pausa.** O código e as capturas do aplicativo continuam públicos.

[Ver o código](https://github.com/lucasmef/doit.md)

### No computador

<img src="../assets/doit-demo.png" alt="doit.md: demonstração visual com notas e tarefas ilustrativas" width="100%">

<sub>Demonstração visual: captura da interface editada com dados ilustrativos.</sub>

As notas podem ter checklists e indicadores de progresso. O editor salva o conteúdo e mantém versões anteriores, que podem ser recuperadas. A demonstração usa exemplos de organização de um portfólio.

### No celular

A interface adapta a navegação à tela menor, com acesso às notas, ao calendário e à captura de novos itens. O manifesto PWA define os ícones, atalhos e a abertura do aplicativo em janela própria.

### Calendário e arquivos locais

O projeto tem integração com Google Calendar e permite anexar arquivos pelo Google Drive. A CLI sincroniza o conteúdo com arquivos Markdown locais. As mudanças nesses arquivos passam por revisão antes de voltar ao aplicativo.

### Arquitetura

O monorepo separa a aplicação Next.js, a CLI em Node.js e os pacotes compartilhados. Há módulos para persistência, Markdown, calendário, sincronização e revisão das alterações. O banco pode usar SQLite local ou PostgreSQL, conforme o ambiente.

A imagem de apresentação foi editada a partir de uma captura do aplicativo e usa conteúdo ilustrativo. O projeto está preservado como portfólio, com as GitHub Actions desativadas.

`Next.js` `React` `TypeScript` `Node.js` `PWA` `SQLite` `PostgreSQL` `Google APIs`

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
