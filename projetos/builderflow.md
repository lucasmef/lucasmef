[← Voltar ao portfólio](../README.md#ia-e-specs)

# BuilderFlow

## Desenvolvimento assistido por IA com especificações no repositório

Criei o BuilderFlow para organizar o contexto, as especificações e as decisões técnicas de projetos desenvolvidos com apoio de agentes de IA. O fluxo é voltado a projetos individuais e equipes pequenas.

O instalador é uma CLI em Node.js. O processo fica documentado em arquivos Markdown, que podem ser consultados e revisados junto do código.

### Estrutura de documentação

| Arquivo ou pasta | Função |
| :--- | :--- |
| `AGENTS.md` | Orientações para o agente trabalhar no repositório. |
| `docs/CONTEXT.md` | Contexto para consulta entre sessões de trabalho. |
| `specs/` | Uma especificação por funcionalidade, atualizada durante o desenvolvimento. |
| `docs/ADR.md` | Registro das decisões de arquitetura. |
| `specs/artifacts/` | Evidências de validação, como capturas das telas alteradas. |

### Especificações durante o desenvolvimento

Cada especificação começa pelo comportamento esperado. Durante a implementação, recebe decisões e pendências. Ao encerrar a mudança, registra a validação e os próximos passos. Essas informações ficam no repositório para consulta em outras sessões.

<picture>
  <source media="(max-width: 600px)" srcset="../assets/workflow-mobile.svg">
  <img src="../assets/workflow.svg" alt="Etapas do BuilderFlow: contexto, especificação, implementação, revisão e publicação." width="100%">
</picture>

### Instalação

Desenvolvi a CLI para criar a estrutura ausente e acrescentar a seção do BuilderFlow ao `AGENTS.md`. Por padrão, ela preserva os documentos existentes. As instruções específicas de cada domínio permanecem no próprio repositório.

### Código e uso

O instalador pode ser executado a partir de uma cópia local do repositório. As instruções estão no [README do BuilderFlow](https://github.com/lucasmef/builder-flow#install-into-a-repository).

`Node.js` `JavaScript` `Markdown` `CLI` `Specs` `ADRs`

[Consultar o código →](https://github.com/lucasmef/builder-flow) · [Conversar comigo](https://www.linkedin.com/in/lucasmef)

---

[Voltar ao portfólio](../README.md)
