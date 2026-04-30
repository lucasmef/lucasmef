<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=270&color=0:0F172A,35:1D4ED8,70:0F766E,100:14B8A6&text=Lucas%20Fernandes&fontColor=FFFFFF&fontSize=48&fontAlignY=36&desc=Full%20Stack%20Engineer%20%7C%20ERP%20%7C%20Financeiro%20%7C%20Backoffice%20%7C%20IA%20em%20produ%C3%A7%C3%A3o&descAlignY=58&descSize=16&animation=fadeIn" alt="Lucas Fernandes banner" />
</div>

<div align="center">
  <h3>Software para operação real, com regra de negócio densa, segurança e entrega em produção.</h3>
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/lucasmef">
    <img src="https://img.shields.io/badge/LinkedIn-Lucas%20Fernandes-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:lucasmef@gmail.com">
    <img src="https://img.shields.io/badge/Email-lucasmef%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/lucasmef?tab=followers">
    <img src="https://img.shields.io/github/followers/lucasmef?style=for-the-badge&label=Followers&color=0F172A" alt="GitHub followers" />
  </a>
  <img src="https://img.shields.io/badge/Tubar%C3%A3o-SC-0F766E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Localização" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/ERP-0F172A?style=flat-square" alt="ERP" />
  <img src="https://img.shields.io/badge/Financeiro-0F172A?style=flat-square" alt="Financeiro" />
  <img src="https://img.shields.io/badge/Backoffice-0F172A?style=flat-square" alt="Backoffice" />
  <img src="https://img.shields.io/badge/Integra%C3%A7%C3%B5es%20Banc%C3%A1rias-0F172A?style=flat-square" alt="Integrações bancárias" />
  <img src="https://img.shields.io/badge/VPS%20%2B%20CI%2FCD-0F172A?style=flat-square" alt="VPS e CI/CD" />
  <img src="https://img.shields.io/badge/AI%20Workflow-0F172A?style=flat-square" alt="AI workflow" />
</div>

---

## Sobre mim

Trabalho com web desde 2003 e venho do varejo e do e-commerce. Meu foco é transformar regra operacional em especificação, arquitetura, código testável e software rodando em produção.

No dia a dia, construo produtos com **TypeScript / React / Next.js** no front e **Python / FastAPI / PostgreSQL** no back. Uso Codex, Claude Code e Gemini como aceleradores de exploração, implementação, revisão e documentação, sem terceirizar responsabilidade de arquitetura, segurança e operação.

## O que eu construo

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>Produtos internos</strong><br />
      ERP, financeiro, dashboards, backoffice e ferramentas operacionais.
    </td>
    <td width="33%" valign="top">
      <strong>Fluxos críticos</strong><br />
      Autenticação, auditoria, conciliação, importação, cobrança e analytics.
    </td>
    <td width="33%" valign="top">
      <strong>Entrega completa</strong><br />
      Frontend, backend, banco, deploy, observabilidade e rotina operacional.
    </td>
  </tr>
</table>

## Projeto em destaque

<div align="center">
  <a href="https://github.com/lucasmef/salomao">
    <img src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=lucasmef&repo=salomao&hide_border=true&theme=transparent" alt="Salomão repo card" />
  </a>
</div>

### Salomão

Sistema financeiro full stack em produção, rodando em VPS, com cobrança, conciliação, compras, fluxo de caixa, DRE/DRO, projeções, analytics e integração com o Banco Inter para extrato, boleto, baixa, cancelamento e PDF.

<div align="center">
  <img src="https://img.shields.io/badge/React%2018-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React 18" />
  <img src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-111827?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
</div>

> Produto financeiro com frontend moderno, backend estruturado, persistência relacional, integrações bancárias, segurança de autenticação, cache analítico, testes, documentação, CI/CD e operação em Linux.

<details>
  <summary><strong>Domínio e módulos</strong></summary>
  <br />

- Dashboard executivo, leituras gerenciais, aniversariantes e indicadores financeiros.
- Lançamentos, contas, categorias, relatórios, fluxo de caixa e regras financeiras.
- Importações históricas, OFX, Linx, liquidação de recebíveis e API-first refresh.
- Boletos, cobrança C6, planejamento de compras, devoluções e recebíveis.
</details>

<details>
  <summary><strong>Segurança e operação</strong></summary>
  <br />

- MFA, dispositivos confiáveis, cookies HttpOnly, rate limit, criptografia de campos e audit logs.
- Headers defensivos e proteção contra path traversal no static serving.
- HTTPS atrás de Nginx, UFW, fail2ban e SSH restrito ao Tailscale.
- Healthchecks em deploy e auditoria de serviço, portas, TLS, SSH, banco e componentes críticos.
- Segredos fora do repositório, com exemplos versionados apenas para referência.
</details>

<details>
  <summary><strong>Deploy e governança</strong></summary>
  <br />

| Workflow | Trigger | Função |
| --- | --- | --- |
| `Deploy Dev` | push em `dev` + manual | deploy automático de homologação |
| `Deploy Prod` | manual | deploy manual de produção a partir de SHA imutável |
| `Quality` | push/PR | backend, frontend e validações de qualidade |
| `Security Checks` | workflow dedicado | verificações de segurança do repositório |
| `Refresh Dev DB` | manual | cópia prod para dev e aplica modo seguro |
| `Sanitize Dev DB` | manual | anonimiza dados sensíveis no dev |
| `Set Dev Safety Mode` | manual | alterna dev entre `safe` e `validate` |

Política operacional: `dev` é a branch normal de trabalho e homologação; `main` representa produção e só é promovida manualmente.
</details>

<details>
  <summary><strong>Confiabilidade e stack</strong></summary>
  <br />

- Frontend em React 18, TypeScript e Vite.
- Backend em FastAPI, SQLAlchemy, Pydantic, PostgreSQL e Alembic.
- Redis para cache de analytics, dashboard e snapshots históricos.
- Testes cobrindo autenticação, financeiro, bancos, importações, analytics e relatórios.
</details>

## Outros projetos

<div align="center">
  <a href="https://github.com/lucasmef/growth-agent">
    <img src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=lucasmef&repo=growth-agent&hide_border=true&theme=transparent" alt="Growth Agent repo card" />
  </a>
  <a href="https://github.com/lucasmef/meu-negocio-facil-next">
    <img src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=lucasmef&repo=meu-negocio-facil-next&hide_border=true&theme=transparent" alt="Meu Negócio Fácil repo card" />
  </a>
</div>

### growth-agent

Base SaaS de growth content com IA, automação de publicação e aprovação humana antes de qualquer post sair.

### meu-negocio-facil-next

ERP acadêmico onde atuei como Lead Developer e Scrum Master, com 225+ commits próprios em PDV, estoque, vendas, autenticação, dashboards e fluxos de backoffice.

## Stack

<div align="center">
  <img src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-111827?style=flat-square&logo=php&logoColor=777BB4" alt="PHP" />
  <img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Vite-111827?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
  <img src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
  <img src="https://img.shields.io/badge/SQLAlchemy-111827?style=flat-square&logo=sqlalchemy&logoColor=D71F00" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Prisma-111827?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-111827?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
  <img src="https://img.shields.io/badge/NGINX-111827?style=flat-square&logo=nginx&logoColor=009639" alt="NGINX" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-111827?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Pytest-111827?style=flat-square&logo=pytest&logoColor=0A9EDC" alt="Pytest" />
  <img src="https://img.shields.io/badge/Codex-111827?style=flat-square" alt="Codex" />
  <img src="https://img.shields.io/badge/Claude%20Code-111827?style=flat-square" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Gemini-111827?style=flat-square&logo=googlegemini&logoColor=8E75B2" alt="Gemini" />
</div>

## Como eu trabalho

1. Entendo a regra de negócio e os riscos operacionais.
2. Documento contratos, entidades, cálculos e critérios de aceite.
3. Quebro o escopo em tarefas pequenas, implemento, reviso e testo.
4. Valido em ambiente próximo de produção e acompanho a operação.

## Formação

- Bacharelado em Sistemas de Informação - PUC Minas, em andamento, conclusão prevista em 2029.
- Tecnólogo em Marketing - Unisul, 2022.
- AWS Academy: Cloud Foundations, Cloud Developing e Generative AI Foundations.
- Vercel: Next.js App Router Fundamentals e React Foundations for Next.js.

## GitHub

<div align="center">
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api?username=lucasmef&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=lucasmef&layout=compact&hide_border=true&theme=transparent" alt="Top languages" />
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=lucasmef&bg_color=00000000&color=334155&line=14B8A6&point=0F172A&area=true&hide_border=true" alt="GitHub activity graph" />
</div>

## Contato

<div align="center">
  Encaixo melhor em times que constroem produto com regra de negócio densa: ERP, financeiro, backoffice, retail tech ou ferramentas internas com IA.
  <br /><br />
  <a href="mailto:lucasmef@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email contact" />
  </a>
  <a href="https://www.linkedin.com/in/lucasmef">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn contact" />
  </a>
</div>
