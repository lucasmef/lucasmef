<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/header-dark-mobile.svg">
  <source media="(max-width: 600px)" srcset="./assets/header-light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img src="./assets/header-light.svg" alt="Lucas Fernandes. Desenvolvedor full stack. Também estou do outro lado da tela." width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/lucasmef"><strong>LinkedIn</strong></a> ·
  <a href="mailto:lucasmef@gmail.com">E-mail</a> ·
  <a href="#projetos">Projetos</a> ·
  <a href="#codigo-publico">Código público</a>
</p>

## Desenvolvimento full stack para problemas de negócio

Desenvolvo aplicações com **TypeScript, React, Python e PostgreSQL**. Tenho mais de 15 anos de experiência no varejo e curso **Sistemas de Informação na PUC Minas**. Essa experiência aparece nos sistemas que construo: gestão financeira, estoque, vendas e integrações.

**Busco uma oportunidade em desenvolvimento de software.** Trabalho no frontend, backend e nas regras que conectam a aplicação à operação de quem usa o sistema.

<a id="projetos"></a>

## Projetos selecionados

### [Salomão · gestão financeira](./projetos/salomao.md)

Sistema que desenvolvo e mantenho para cobranças, conciliação bancária, planejamento de compras e fluxo de caixa. Atuo nas telas, API, modelagem dos dados e operação em VPS, com integrações com Banco Inter e Linx.

`React` `TypeScript` `FastAPI` `PostgreSQL` `Redis` `GitHub Actions`

[Minha contribuição e decisões técnicas →](./projetos/salomao.md) · Código operacional privado

### [Smart Shop · e-commerce por look](./projetos/smart-shop.md)

Loja em desenvolvimento para a Raquel Talita. A compra parte de combinações de roupas e segue por peças, tamanhos e disponibilidade. Trabalho no catálogo, checkout, reserva de estoque e integrações de pagamento e frete. A operação comercial ainda exige homologação.

`Next.js` `React` `TypeScript` `PostgreSQL` `Supabase`

[Experiência de compra e desafios de estoque →](./projetos/smart-shop.md) · Código privado

### [Send Mail · fila de e-mails](./projetos/send-mail.md)

CLI local com fila persistente em SQLite, envio SMTP com TLS e credenciais no Keychain do macOS. O projeto trata idempotência, retomada e falhas após possível aceitação da mensagem para evitar reenvios automáticos indevidos.

`Python` `SQLite` `SMTP` `IMAP` `Testes automatizados`

[Consultar o código](https://github.com/lucasmef/send-mail) · [Arquitetura e tratamento de falhas](./projetos/send-mail.md)

<a id="codigo-publico"></a>

## Código público

| Projeto | O que desenvolvi | Estado |
| :--- | :--- | :--- |
| [Reel Transcribe](https://github.com/lucasmef/reel-transcribe) | CLI para baixar conteúdo autorizado e transcrever ou traduzir áudio com Gemini, com testes de erros HTTP, limites e redirecionamentos. | Ferramenta local |
| [BuilderFlow](https://github.com/lucasmef/builder-flow) | Instalador de templates de contexto, specs e decisões para desenvolvimento assistido por IA. | Fluxo de trabalho reutilizável |
| [doit.md](https://github.com/lucasmef/doit.md) | Aplicativo de notas, tarefas e calendário com CLI de sincronização Markdown e revisão das alterações. | Em pausa; código preservado como histórico; Actions desativadas |

## Ferramentas e experimentos

Também desenvolvo ferramentas locais para áudio, vídeo e produtividade. As apresentações explicam o escopo, as decisões e os limites; os repositórios permitem consultar o código.

| Projeto | Trabalho técnico | Estado | Código |
| :--- | :--- | :--- | :--- |
| [LookPrint](./projetos/lookprint.md) | Extração de quadros de composições de moda com AVFoundation e Vision. | App local para macOS | [Repositório](https://github.com/lucasmef/print-videos) |
| [Proxies Maker](./projetos/proxies-maker.md) | Geração de previews de vídeo com Swift, Python e FFmpeg. | Ferramenta local | [Repositório](https://github.com/lucasmef/proxies-maker) |
| [Sinal IA](./projetos/sinal-ia.md) | Leitura local de declarações de IA e credenciais de procedência em metadados. | Scanner; não valida assinaturas C2PA | [Repositório](https://github.com/lucasmef/anti-ia) |
| [Rosto Natural](./projetos/rosto-natural.md) | Processamento facial em C++, máscaras e estabilização temporal. | Experimental; integração Adobe em desenvolvimento | [Repositório](https://github.com/lucasmef/rosto-natural) |
| [Voz Neural](./projetos/voz-neural.md) | Pipeline local de redução de ruído e tratamento de voz. | Integração Adobe em desenvolvimento | [Repositório](https://github.com/lucasmef/voz-neural) |
| [Editor Viral](./projetos/editor-viral.md) | Composições Remotion e fluxo de montagem rastreável para vídeos digitais. | Piloto em validação | [Repositório](https://github.com/lucasmef/editor-viral) |

## Trabalho em equipe

**Loja de Jogos Usados**, projeto acadêmico em equipe. Fiquei responsável pelos módulos de clientes e vendas, incluindo cadastro, registro de pagamento e baixa de estoque. Também organizei especificações e contratos entre módulos para orientar a integração. O repositório tem acesso restrito à equipe da faculdade.

`JavaScript` `HTML` `CSS` `ES Modules` `localStorage` `Testes com Node.js`

<a id="ia-e-specs"></a>

## Como trabalho

Uso especificações para definir o comportamento esperado e agentes de IA para apoiar implementação e revisão. Confiro as mudanças com testes e verificações dos fluxos, conforme a tarefa. Mantenho o contexto e as decisões perto do código; o [BuilderFlow](./projetos/builderflow.md) reúne os templates que utilizo nesse processo.

## Tecnologias

- **Stack principal:** TypeScript, JavaScript, React, Next.js, Python, FastAPI e PostgreSQL.
- **Dados e operação:** SQLAlchemy, Prisma, Supabase, Redis, GitHub Actions, Linux, Docker e Nginx.
- **Ferramentas de áudio e vídeo:** Swift, C++, NumPy, MediaPipe, Metal, FFmpeg e Adobe UXP, conforme o projeto.

<details>
  <summary><strong>Formação e cursos</strong></summary>

Sistemas de Informação · PUC Minas · em andamento.<br>
Tecnólogo em Marketing · Unisul · 2022.

AWS Academy: Cloud Foundations, Cloud Developing e Generative AI Foundations.<br>
Vercel: Next.js App Router Fundamentals e React Foundations for Next.js.

</details>

Para conversar sobre uma oportunidade: [LinkedIn](https://www.linkedin.com/in/lucasmef) ou [lucasmef@gmail.com](mailto:lucasmef@gmail.com).
