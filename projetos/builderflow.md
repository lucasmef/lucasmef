[← Voltar ao perfil](../README.md#user-content-projetos)

# BuilderFlow

## Contexto de projeto que fica no repositório

Criei o BuilderFlow para retomar o desenvolvimento com um agente de IA sem precisar explicar o projeto inteiro em cada sessão. Ele instala arquivos de contexto, modelos de especificação e um lugar para registrar decisões.

### O que ele instala

| Arquivo ou pasta | Uso |
| :--- | :--- |
| `AGENTS.md` | Instruções de trabalho para o agente. |
| `docs/CONTEXT.md` | Contexto do projeto. |
| `specs/` | Especificações das funcionalidades e registro do andamento. |
| `docs/ADR.md` | Decisões de arquitetura. |
| `specs/artifacts/` | Capturas e outras evidências de validação. |

A CLI foi escrita em Node.js. Ela cria a estrutura que falta e, por padrão, preserva os documentos existentes.

### Como uso

Antes de implementar uma funcionalidade, descrevo o comportamento esperado. Durante o trabalho, atualizo a mesma especificação com decisões, testes e pendências. Na próxima sessão, esse registro ajuda a continuar de onde parei.

<picture>
  <source media="(max-width: 600px)" srcset="../assets/workflow-mobile.svg">
  <img src="../assets/workflow.svg" alt="Etapas do BuilderFlow: contexto, especificação, implementação, revisão e publicação" width="100%">
</picture>

É um conjunto de templates e instruções reutilizáveis, com um instalador pequeno para levá-los a outros repositórios.

`Node.js` `JavaScript` `Markdown` `CLI`

[Ver o código e a instalação](https://github.com/lucasmef/builder-flow)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
