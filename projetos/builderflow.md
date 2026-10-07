[← Voltar ao portfólio](../README.md#ia-e-specs)

# BuilderFlow

## Para continuar de onde parei.

Uma nova sessão com um agente de IA não deveria exigir que eu explicasse o projeto inteiro de novo. Criei o BuilderFlow para manter o contexto no repositório e acompanhar cada funcionalidade em uma especificação que evolui junto com o código.

É um fluxo de desenvolvimento assistido por IA pensado para projetos individuais e equipes pequenas. O instalador é uma CLI em Node.js; o processo fica descrito em arquivos Markdown que podem ser lidos e revisados junto do projeto.

### O que ele organiza

| Arquivo ou pasta | Para que serve |
| :--- | :--- |
| `AGENTS.md` | Orientações para o agente trabalhar naquele repositório. |
| `docs/CONTEXT.md` | Contexto que precisa continuar disponível entre sessões. |
| `specs/` | Uma especificação por funcionalidade, atualizada durante o trabalho. |
| `docs/ADR.md` | Registro das decisões de arquitetura. |
| `specs/artifacts/` | Evidências de validação, como capturas das telas alteradas. |

### A spec acompanha a implementação

Antes da mudança, ela define o comportamento esperado. Durante o desenvolvimento, recebe as decisões e as pendências. Ao encerrar, registra o que foi validado e o próximo passo. A documentação continua perto do código e pode ser retomada por outra sessão.

<picture>
  <source media="(max-width: 600px)" srcset="../assets/workflow-mobile.svg">
  <img src="../assets/workflow.svg" alt="Etapas do BuilderFlow: contexto, especificação, implementação, revisão e publicação." width="100%">
</picture>

### Um instalador que respeita o projeto existente

Desenvolvi a CLI para criar a estrutura que falta e acrescentar a seção do BuilderFlow ao `AGENTS.md`. Por padrão, ela preserva os documentos existentes. Instruções específicas de cada domínio continuam no próprio repositório.

### Código e uso

O instalador pode ser executado a partir de uma cópia local do repositório. As instruções estão no [README do BuilderFlow](https://github.com/lucasmef/builder-flow#install-into-a-repository).

`Node.js` `JavaScript` `Markdown` `CLI` `Specs` `ADRs`

[Consultar o código →](https://github.com/lucasmef/builder-flow) · [Conversar comigo](https://www.linkedin.com/in/lucasmef)

---

[Voltar ao portfólio](../README.md)
