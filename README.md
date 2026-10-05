<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/header-dark-mobile.svg">
  <source media="(max-width: 600px)" srcset="./assets/header-light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img src="./assets/header-light.svg" alt="Lucas Fernandes. Desenvolvedor full stack. Também estou do outro lado da tela." width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/lucasmef"><strong>LinkedIn ↗</strong></a>
  &nbsp; · &nbsp;
  <a href="mailto:lucasmef@gmail.com">E-mail</a>
  &nbsp; · &nbsp;
  <a href="#projetos">Projetos</a>
  &nbsp; · &nbsp;
  <a href="#ia-e-specs">Como uso IA</a>
</p>

### O varejo faz parte do meu jeito de desenvolver

Trabalho com varejo há mais de 15 anos. Quando desenvolvo um sistema de vendas ou uma integração bancária, penso também em quem precisa usar aquilo durante o expediente. É um trabalho que conheço de perto e que aparece em boa parte dos meus projetos.

Curso Sistemas de Informação na PUC Minas e desenvolvo aplicações full stack. Cuido tanto das telas quanto do backend e das integrações. Uso agentes de IA durante o desenvolvimento, com especificações no repositório para acompanhar as decisões e conferir o que foi implementado.

<a id="projetos"></a>

## 01 / Projetos

### Loja de Jogos Usados

**Vender um jogo não pode bagunçar o estoque.**

Projeto da faculdade, desenvolvido em equipe. Fiquei responsável pela parte de **clientes e vendas**. Implementei o cadastro de clientes e o fluxo de venda, incluindo a baixa de estoque e o registro da forma de pagamento. Cada venda mantém seu histórico, e uma confirmação repetida não pode baixar o mesmo item duas vezes.

Também organizei as specs e os contratos entre módulos para orientar a implementação com agentes de IA. Minha parte está concluída e revisada; a integração com as outras partes do sistema continua em andamento.

`JavaScript` `HTML & CSS` `ES Modules` `localStorage` `Testes com Node.js`

<sub>Repositório privado. O link da demonstração será incluído quando o projeto estiver publicado.</sub>
<!-- Quando a demo estiver publicada, incluir aqui o link público confirmado do GitSites. -->

---

### Smart Shop

**Escolher pelo look, comprar por peça.**

E-commerce que desenvolvo para a loja de moda feminina Raquel Talita. A cliente pode escolher peças a partir de um look e seguir com elas para o checkout. O projeto também envolve reserva de estoque e integrações de pagamento e frete.

`Next.js` `TypeScript` `Supabase` `PostgreSQL` `Vercel`

<sub>Em desenvolvimento · Código privado</sub>

---

### [Salomão ↗](https://github.com/lucasmef/salomao)

**O financeiro não acaba quando a venda fecha.**

Sistema de gestão financeira com cobranças, conciliação bancária, planejamento de compras e fluxo de caixa. Desenvolvo as integrações com Banco Inter e Linx, além das telas e regras do financeiro.

Também cuido da publicação em VPS. O projeto tem autenticação com MFA e registros de auditoria, com ambientes separados para homologação e produção.

`React` `FastAPI` `PostgreSQL` `Redis` `Linux`

[Documentação de segurança](https://github.com/lucasmef/salomao#segurança-em-destaque)

---

### [doit.md ↗](https://github.com/lucasmef/doit.md)

**Para a tarefa não ficar perdida nas anotações.**

Aplicativo de notas e tarefas com calendário integrado. Uma CLI sincroniza o conteúdo com arquivos Markdown locais, que podem ser editados por agentes de IA. As alterações passam por revisão antes de voltar para o aplicativo, e o histórico permite recuperar versões anteriores.

`Next.js` `TypeScript` `Node.js` `Google APIs`

[Como funciona a revisão das alterações](https://github.com/lucasmef/doit.md#auditoria-e-ia)

---

### [Growth Agent ↗](https://github.com/lucasmef/growth-agent)

**Você aprova o que a IA escreve.**

Base de um SaaS para planejar e produzir conteúdo para redes sociais com IA. Os rascunhos passam por aprovação humana antes da publicação nas contas de clientes. Há uma área separada para experimentar configurações de geração e acompanhar os resultados.

`Next.js` `Prisma` `AI SDK` `Trigger.dev`

[Funcionalidades e arquitetura](https://github.com/lucasmef/growth-agent#principais-funcionalidades)

<a id="ia-e-specs"></a>

## 02 / Como trabalho com IA

**A spec é o combinado antes do código.**

Uso **Codex, Claude Code e Antigravity** no desenvolvimento. Escrevo specs para definir o comportamento esperado antes de implementar uma funcionalidade. Na loja de jogos, por exemplo, isso inclui o que deve acontecer quando alguém confirma a mesma venda duas vezes ou quando o navegador não consegue salvar os dados.

Quando uso mais de um agente, delimito o que cada um pode alterar e quais partes dependem de outras. A revisão fica separada da implementação. Depois, confiro o funcionamento com testes e verificações no navegador, conforme a mudança.

Mantenho o contexto em arquivos como `AGENTS.md` e crio skills para instruções que preciso reutilizar. Registro decisões de arquitetura em ADRs quando necessário. Isso ajuda a retomar o trabalho em outra sessão sem ter que explicar o projeto inteiro de novo.

### [BuilderFlow ↗](https://github.com/lucasmef/builder-flow)

**Para continuar de onde parei.**

Criei o BuilderFlow para levar essa organização aos meus repositórios. Ele instala uma estrutura de contexto e especificações, com uma spec por funcionalidade. Durante o desenvolvimento, atualizo esse documento com as decisões e o que ainda falta fazer.

<picture>
  <source media="(max-width: 600px)" srcset="./assets/workflow-mobile.svg">
  <img src="./assets/workflow.svg" alt="Etapas do BuilderFlow: contexto, especificação, implementação, revisão e publicação." width="100%">
</picture>

## 03 / Tecnologias que uso

| Área | Tecnologias |
| :--- | :--- |
| **Frontend** | TypeScript · JavaScript · React · Next.js · HTML · CSS · Vite |
| **Backend** | Python · FastAPI · Node.js · APIs REST |
| **Dados** | PostgreSQL · Supabase · Redis · Prisma · SQLAlchemy |
| **IA e automação** | Codex · Claude Code · Antigravity · AI SDK · Trigger.dev |
| **Infraestrutura** | GitHub Actions · Vercel · Linux · Docker · Nginx |

<details>
  <summary><strong>Formação e cursos</strong></summary>

**Sistemas de Informação · PUC Minas**, em andamento.<br>
**Tecnólogo em Marketing · Unisul**, 2022.

**AWS Academy:** Cloud Foundations, Cloud Developing e Generative AI Foundations.<br>
**Vercel:** Next.js App Router Fundamentals e React Foundations for Next.js.

</details>

---

### Vamos trabalhar no seu próximo projeto?

Para conversar sobre uma oportunidade de trabalho, pode me chamar pelo [LinkedIn](https://www.linkedin.com/in/lucasmef) ou escrever para [lucasmef@gmail.com](mailto:lucasmef@gmail.com).
