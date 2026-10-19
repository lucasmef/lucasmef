[← Voltar ao perfil](../README.md#user-content-projetos)

# BuilderFlow

## Templates e CLI para desenvolvimento com agentes

CLI em Node.js para instalar arquivos de contexto, templates de especificação e registros de decisões de arquitetura. A documentação no repositório mantém o contexto do trabalho entre sessões de agentes de IA.

### O que ele instala

| Arquivo ou pasta | Uso |
| :--- | :--- |
| `AGENTS.md` | Instruções de trabalho para o agente. |
| `docs/CONTEXT.md` | Contexto do projeto. |
| `specs/` | Especificações das funcionalidades e registro do andamento. |
| `docs/ADR.md` | Decisões de arquitetura. |
| `specs/artifacts/` | Capturas e outras evidências de validação. |

O instalador cria os arquivos ausentes e preserva os documentos existentes por padrão.

### Fluxo de trabalho

Cada funcionalidade parte de uma especificação de comportamento. Decisões, testes e pendências ficam no mesmo registro para permitir a continuidade entre sessões.

<picture>
  <source media="(max-width: 600px)" srcset="../assets/workflow-mobile.svg">
  <img src="../assets/workflow.svg" alt="Etapas do BuilderFlow: contexto, especificação, implementação, revisão e publicação" width="100%">
</picture>


`Node.js` `JavaScript` `Markdown` `CLI`

[Ver o código e a instalação](https://github.com/lucasmef/builder-flow)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
