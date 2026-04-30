<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:020617,45:111827,100:0F766E&text=Lucas%20Fernandes&fontColor=FFFFFF&fontSize=46&fontAlignY=37&desc=Full%20Stack%20Engineer%20%7C%20ERP%2C%20Financeiro%2C%20Backoffice%20e%20IA%20em%20produ%C3%A7%C3%A3o&descAlignY=58&descSize=16&animation=fadeIn" alt="Lucas Fernandes banner" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/lucasmef">
    <img src="https://img.shields.io/badge/LinkedIn-Lucas%20Fernandes-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:lucasmef@gmail.com">
    <img src="https://img.shields.io/badge/Email-lucasmef%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/lucasmef?tab=followers">
    <img src="https://img.shields.io/github/followers/lucasmef?style=for-the-badge&label=Followers&color=111827" alt="GitHub followers" />
  </a>
  <img src="https://img.shields.io/badge/Tubar%C3%A3o-SC-0F766E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Localização" />
</div>

<br />

<table>
  <tr>
    <td width="58%" valign="top">
      <h2>Olá, sou o Lucas</h2>
      <p>
        Full Stack Engineer focado em sistemas de operação real: ERP, financeiro, backoffice,
        dashboards, automações e produtos com IA aplicada ao fluxo de engenharia.
      </p>
      <p>
        Trabalho com web desde 2003 e venho do varejo e do e-commerce. Isso me ajuda a transformar
        regra operacional em especificação, arquitetura, código testável e software rodando em produção.
      </p>
      <p>
        Hoje meu stack diário é <strong>TypeScript / React / Next.js</strong> no front e
        <strong>Python / FastAPI / PostgreSQL</strong> no back, com Codex, Claude Code e Gemini como
        aceleradores de exploração, implementação, revisão e documentação.
      </p>
    </td>
    <td width="42%" valign="top">
      <h3>Foco técnico</h3>
      <ul>
        <li>Produtos financeiros e sistemas administrativos.</li>
        <li>APIs, integrações bancárias e rotinas operacionais.</li>
        <li>Segurança, autenticação, auditoria e deploy em VPS.</li>
        <li>Frontend moderno para fluxos densos de negócio.</li>
        <li>IA como apoio, com responsabilidade humana sobre arquitetura e produção.</li>
      </ul>
    </td>
  </tr>
</table>

## Case principal: Salomão

<a href="https://github.com/lucasmef/salomao">
  <img align="right" width="395" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=lucasmef&repo=salomao&hide_border=true&theme=transparent" alt="Salomão repo card" />
</a>

Sistema financeiro full stack em produção, rodando em VPS, com módulos de cobrança, conciliação, compras, fluxo de caixa, DRE/DRO, projeções, analytics e integração com o Banco Inter para extrato, boleto, baixa, cancelamento e PDF.

**Produto e domínio**

- Dashboard executivo, leituras gerenciais, aniversariantes e indicadores financeiros.
- Lançamentos, contas, categorias, relatórios, fluxo de caixa e regras financeiras.
- Importações históricas, OFX, Linx, liquidação de recebíveis e API-first refresh.
- Boletos, cobrança C6, planejamento de compras, devoluções e recebíveis.

**Engenharia e arquitetura**

- Frontend em React 18, TypeScript e Vite.
- Backend em FastAPI, SQLAlchemy, Pydantic, PostgreSQL e Alembic.
- Redis para cache de analytics, dashboard e snapshots históricos.
- Testes cobrindo autenticação, financeiro, bancos, importações, analytics e relatórios.

**Segurança e operação**

- MFA, dispositivos confiáveis, cookies HttpOnly, rate limit, criptografia de campos e audit logs.
- Headers defensivos e proteção contra path traversal no static serving.
- HTTPS atrás de Nginx, UFW, fail2ban e SSH restrito ao Tailscale.
- Healthchecks em deploy e auditoria de serviço, portas, TLS, SSH, banco e componentes críticos.
- Segredos fora do repositório, com exemplos versionados apenas para referência.

**Deploy e governança**

| Workflow | Trigger | Função |
| --- | --- | --- |
| `Deploy Dev` | push em `dev` + manual | deploy automático de homologação |
| `Deploy Prod` | manual | deploy manual de produção a partir de SHA imutável |
| `Quality` | push/PR | backend, frontend e validações de qualidade |
| `Security Checks` | workflow dedicado | verificações de segurança do repositório |
| `Refresh Dev DB` | manual | cópia prod para dev e aplica modo seguro |
| `Sanitize Dev DB` | manual | anonimiza dados sensíveis no dev |
| `Set Dev Safety Mode` | manual | alterna dev entre `safe` e `validate` |

Política operacional: `dev` é a branch normal de trabalho e homologação; `main` representa produção e só é promovida manualmente. Depois de push em `dev`, acompanho o run de deploy até o status final.

<br clear="right" />

## Outros projetos

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lucasmef/growth-agent">
        <img width="100%" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=lucasmef&repo=growth-agent&hide_border=true&theme=transparent" alt="Growth Agent repo card" />
      </a>
      <h3>growth-agent</h3>
      <p>Base SaaS de growth content com IA, automação de publicação e aprovação humana antes de qualquer post sair.</p>
      <ul>
        <li>Next.js 16, React 19 e App Router.</li>
        <li>Prisma, PostgreSQL, Zod e Clerk.</li>
        <li>AI SDK, OpenAI e Trigger.dev para jobs assíncronos.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lucasmef/meu-negocio-facil-next">
        <img width="100%" src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=lucasmef&repo=meu-negocio-facil-next&hide_border=true&theme=transparent" alt="Meu Negócio Fácil repo card" />
      </a>
      <h3>meu-negocio-facil-next</h3>
      <p>ERP acadêmico onde atuei como Lead Developer e Scrum Master, com 225+ commits próprios.</p>
      <ul>
        <li>PDV, estoque, vendas, autenticação e dashboards.</li>
        <li>Estado global e fluxos de backoffice.</li>
        <li>Organização de tarefas, revisão e entrega em equipe.</li>
      </ul>
    </td>
  </tr>
</table>

## Stack

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>Linguagens e frontend</h3>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
        <img src="https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
        <img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
        <img src="https://img.shields.io/badge/PHP-111827?style=flat-square&logo=php&logoColor=777BB4" alt="PHP" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
        <img src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/Vite-111827?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>Backend, dados e infra</h3>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
        <img src="https://img.shields.io/badge/SQLAlchemy-111827?style=flat-square&logo=sqlalchemy&logoColor=D71F00" alt="SQLAlchemy" />
        <img src="https://img.shields.io/badge/Prisma-111827?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
        <img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
        <img src="https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
        <img src="https://img.shields.io/badge/NGINX-111827?style=flat-square&logo=nginx&logoColor=009639" alt="NGINX" />
        <img src="https://img.shields.io/badge/GitHub_Actions-111827?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
        <img src="https://img.shields.io/badge/Pytest-111827?style=flat-square&logo=pytest&logoColor=0A9EDC" alt="Pytest" />
      </p>
    </td>
  </tr>
</table>

## Como eu trabalho

<table>
  <tr>
    <td width="25%" valign="top"><strong>1. Regra</strong><br />Entendo o processo real, as exceções e os riscos.</td>
    <td width="25%" valign="top"><strong>2. Spec</strong><br />Documento contratos, entidades, cálculos e critérios de aceite.</td>
    <td width="25%" valign="top"><strong>3. Execução</strong><br />Quebro em tarefas pequenas, implemento, reviso e testo.</td>
    <td width="25%" valign="top"><strong>4. Produção</strong><br />Valido em ambiente próximo de produção e acompanho operação.</td>
  </tr>
</table>

Uso IA como acelerador, mas decisões de escopo, arquitetura, segurança, auditoria e aprovação final permanecem sob responsabilidade humana.

## Formação

- Bacharelado em Sistemas de Informação - PUC Minas, em andamento, conclusão prevista em 2029.
- Tecnólogo em Marketing - Unisul, 2022.
- AWS Academy: Cloud Foundations, Cloud Developing e Generative AI Foundations.
- Vercel: Next.js App Router Fundamentals e React Foundations for Next.js.

## GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api?username=lucasmef&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=lucasmef&layout=compact&hide_border=true&theme=transparent" alt="Top languages" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=lucasmef&bg_color=00000000&color=64748B&line=0F766E&point=111827&area=true&hide_border=true" alt="GitHub activity graph" />
</p>

## Contato

Encaixo melhor em times que constroem produto com regra de negócio densa: ERP, financeiro, backoffice, retail tech ou ferramentas internas com IA.

<div align="center">
  <a href="mailto:lucasmef@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email contact" />
  </a>
  <a href="https://www.linkedin.com/in/lucasmef">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn contact" />
  </a>
</div>
