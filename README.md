<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/header-dark-mobile.svg">
  <source media="(max-width: 600px)" srcset="./assets/header-light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img src="./assets/header-light.svg" alt="Lucas Fernandes. Desenvolvedor full stack. Aplicações web, APIs e automação." width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/lucasmef"><strong>LinkedIn</strong></a> ·
  <a href="mailto:lucasmef@gmail.com">E-mail</a> ·
  <a href="#user-content-projetos">Projetos</a> ·
  <a href="#user-content-codigo-publico">Código público</a>
</p>

## Desenvolvedor full stack

Aplicações web, APIs e ferramentas de automação com **TypeScript, React, Next.js, Python e PostgreSQL**. Meus projetos incluem um ERP acadêmico, um sistema financeiro em operação, uma PWA de produtividade e ferramentas de processamento de áudio e vídeo.

Curso **Sistemas de Informação na PUC Minas** e tenho mais de 15 anos de experiência no varejo, com vivência em vendas, estoque e gestão financeira. **Busco uma oportunidade em desenvolvimento de software.**

<a id="projetos"></a>

## Projetos em destaque

### Meu Negócio Fácil · ERP acadêmico

ERP para pequenos negócios, entregue em equipe na PUC Minas com **JavaScript, HTML e CSS**, sem IA na implementação. Integra cadastros, vendas de produtos e serviços, estoque, financeiro, agenda e relatórios em uma SPA com persistência em LocalStorage.

**Minha contribuição:** arquitetura SPA, autenticação, PDV, gestão de insumos, dashboard e relatórios. Atuação como Scrum Master na organização do backlog e no acompanhamento das entregas.

<a href="./projetos/meu-negocio-facil.md"><img src="https://raw.githubusercontent.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2025-2-pe1-t1-pmv-si-2025-2-pe1-projmeunegociofacil/934e3b4f6bca44352bde104486054fb00de4383f/docs/img/tests/05.jpeg" alt="Meu Negócio Fácil: painel do ERP acadêmico com navegação para cadastros, faturamento, agenda, financeiro e relatórios" width="100%"></a>

`JavaScript` `HTML` `CSS` `LocalStorage` `SPA`

[Abrir o sistema](https://icei-puc-minas-pmv-si.github.io/pmv-si-2025-2-pe1-t1-pmv-si-2025-2-pe1-projmeunegociofacil/) · [Código](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2025-2-pe1-t1-pmv-si-2025-2-pe1-projmeunegociofacil) · [Documentação e mais telas](./projetos/meu-negocio-facil.md)

### Salomão · Gestão financeira

Sistema financeiro em operação no varejo, com frontend em **React**, API em **FastAPI** e banco **PostgreSQL**. Reúne cobranças, conciliação bancária, contas a receber, planejamento de compras e projeções de caixa, com integrações com Banco Inter e Linx.

**Escopo técnico:** frontend, API, modelagem de dados, integrações e manutenção na VPS. O projeto inclui MFA, auditoria, migrações de banco e ambientes separados de homologação e produção.

`React` `TypeScript` `Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Redis` `Linux`

**Status:** em operação · Código privado

[Arquitetura e funcionalidades](./projetos/salomao.md)

### doit.md · PWA de produtividade

Aplicação de notas, tarefas e calendário com **editor Markdown**, checklists, histórico de versões e organização por pastas. Interface responsiva e instalação como PWA em desktop e mobile.

Monorepo com aplicação **Next.js**, CLI em **Node.js** e pacotes compartilhados. Integra Google Calendar e Google Drive e sincroniza notas com arquivos Markdown locais.

<a href="./projetos/doit.md"><img src="https://raw.githubusercontent.com/lucasmef/doit.md/4099abf9f34b8bc70f5e5d25cb281bfb189442b4/specs/artifacts/2026-06-09-corrigir-137-138-progresso-visual-icone-modificacao/01-notas-folder-lista-desktop.png" alt="doit.md: captura histórica da PWA, com pastas, notas, tarefas concluídas e indicadores de progresso usando dados de teste" width="100%"></a>

`Next.js` `React` `TypeScript` `Node.js` `PWA` `SQLite` `PostgreSQL`

**Status:** projeto em pausa, versão online desativada · Código público

[Código](https://github.com/lucasmef/doit.md) · [Telas desktop e mobile e arquitetura](./projetos/doit.md)

### Smart Shop · E-commerce de moda

E-commerce para a loja Raquel Talita, com navegação por looks e seleção de peças e tamanhos na mesma jornada de compra. O escopo inclui catálogo, sacola, checkout, reserva de estoque e painel administrativo.

Aplicação em **Next.js e TypeScript**, com PostgreSQL e Supabase, integrações de pagamento e cotação de frete. As reservas de estoque consideram o saldo comprometido por outros pedidos.

`Next.js` `React` `TypeScript` `PostgreSQL` `Supabase` `Vercel`

**Status:** em desenvolvimento, vendas ainda não abertas · Código privado

[Funcionalidades e estágio do projeto](./projetos/smart-shop.md)

<a id="codigo-publico"></a>

## Ferramentas e automação

### Send Mail · Fila de e-mails via CLI

CLI em **Python** com fila persistida em **SQLite**, credenciais no Keychain e transporte SMTP com TLS. Inclui retomada de execução, histórico, controle de concorrência e tratamento de envios com resultado incerto para evitar duplicidade.

`Python` `SQLite` `SMTP` `IMAP` `macOS Keychain`

[Código](https://github.com/lucasmef/send-mail) · [Persistência e recuperação de falhas](./projetos/send-mail.md)

### Reel Transcribe · Transcrição de vídeos

Ferramenta para download de Reels públicos autorizados e transcrição ou tradução da fala com Gemini.

[Código e instruções](https://github.com/lucasmef/reel-transcribe)

### BuilderFlow · Templates para desenvolvimento com agentes

CLI em **Node.js** para instalar instruções de agentes, contexto do projeto, especificações e registros de decisões de arquitetura. Estrutura reutilizável de documentação, com preservação dos arquivos existentes por padrão.

`Node.js` `JavaScript` `Markdown` `CLI`

[Código](https://github.com/lucasmef/builder-flow) · [Estrutura dos templates](./projetos/builderflow.md)

## Áudio, vídeo e aplicações macOS

### LookPrint · Extração de quadros de vídeos de moda

Aplicativo macOS em **SwiftUI** que identifica estados estáveis de uma composição de roupas e exporta os quadros selecionados. Processamento local com **AVFoundation e Vision**, integração com Finder e preservação do vídeo original.

`Swift` `SwiftUI` `AVFoundation` `Vision`

[Código](https://github.com/lucasmef/print-videos) · [Seleção e exportação de quadros](./projetos/lookprint.md)

### Proxies Maker · Conversão de vídeo em lote

Interface em **Swift** e processamento em **Python com FFmpeg** para gerar versões leves de vídeos. Fila de conversão, progresso, processamento de subpastas e verificação dos arquivos de saída. Variante experimental com VideoToolbox.

`Swift` `Python` `FFmpeg` `VideoToolbox`

[Código](https://github.com/lucasmef/proxies-maker) · [Conversão e validação](./projetos/proxies-maker.md)

### Sinal IA · Inspeção de metadados

Scanner local de **XMP, IPTC e estruturas C2PA** em imagens e vídeos. Exibe declarações de uso de IA presentes no arquivo, com limites de leitura e profundidade no parser. A análise se restringe aos metadados; não classifica a imagem nem valida assinaturas criptográficas.

`Swift` `Parsing binário` `XMP` `IPTC` `C2PA`

[Código](https://github.com/lucasmef/anti-ia) · [Formatos e limites da análise](./projetos/sinal-ia.md)

### Rosto Natural · Processamento facial em vídeo

Núcleo em **C++** para suavização de pele e correções localizadas, com máscaras faciais, rastreamento por **MediaPipe** e estabilização temporal. Inclui processamento de referência em CPU e trabalho de integração com Metal e Adobe UXP.

`C++` `MediaPipe` `Metal` `Python` `Adobe UXP`

**Status:** núcleo avaliado fora do Premiere; integração completa com o editor pendente.

[Código](https://github.com/lucasmef/rosto-natural) · [Processamento e testes de imagem](./projetos/rosto-natural.md)

### Voz Neural · Processamento local de voz

Redução de ruído com **DeepFilterNet**, detecção de atividade vocal com **RNNoise** e ajustes de timbre e nível com processamento de sinal. Referência numérica em Python e NumPy, saída WAV em dual mono e preservação do áudio original.

`Python` `NumPy` `DeepFilterNet` `RNNoise` `C++` `Adobe UXP`

**Status:** núcleo local funcional; painel UXP e ponte C++ para o Premiere em desenvolvimento. Calibração para voz feminina falada.

[Código](https://github.com/lucasmef/voz-neural) · [Processamento e integração](./projetos/voz-neural.md)

### Editor Viral · Edição programática com Remotion

Base local de edição com seleção de trechos, legendas, cartões e zooms em composições **Remotion**. Scripts registram a origem dos cortes e os estados de revisão, com fluxo de transferência para o Adobe Premiere Pro.

`TypeScript` `React` `Remotion` `Python` `FFmpeg`

**Status:** piloto em validação; fluxo completo e transferência de efeitos pendentes de teste no editor.

[Código](https://github.com/lucasmef/editor-viral) · [Estrutura e estágio do projeto](./projetos/editor-viral.md)

## Projetos em equipe

### Loja de Jogos Usados · Projeto acadêmico

Aplicação modular em **JavaScript com ES Modules**. Minha participação abrange cadastro de clientes, vendas, registro de pagamentos e baixa de estoque, além das especificações e dos contratos de integração entre módulos.

`JavaScript` `HTML` `CSS` `ES Modules` `localStorage` `Node.js Test Runner`

**Acesso ao código:** restrito à equipe da faculdade.

<a id="ia-e-specs"></a>

## Práticas de desenvolvimento

- **Requisitos e arquitetura:** regras de negócio, contratos entre módulos e decisões técnicas documentados no repositório.
- **Validação:** testes de regras de negócio, integrações e fluxos da aplicação, conforme o projeto.
- **Operação:** migrações de banco, configuração de serviços e acompanhamento de atualizações em Linux/VPS no Salomão.

Nos projetos atuais, agentes de IA apoiam a implementação e a revisão, com definição de escopo e validação sob minha responsabilidade. O ERP Meu Negócio Fácil foi implementado em equipe sem IA.

## Tecnologias

- **Web e backend:** TypeScript, JavaScript, React, Next.js, Python, FastAPI, HTML e CSS.
- **Dados e infraestrutura:** PostgreSQL, SQLAlchemy, Prisma, Supabase, Redis, GitHub Actions, Linux, Docker e Nginx.
- **Áudio e vídeo:** Swift, C++, NumPy, MediaPipe, Metal, FFmpeg e Adobe UXP, conforme o projeto.

## Formação e cursos

Sistemas de Informação · PUC Minas · em andamento.<br>
Tecnólogo em Marketing · Unisul · 2022.

AWS Academy: Cloud Foundations, Cloud Developing e Generative AI Foundations.<br>
Vercel: Next.js App Router Fundamentals e React Foundations for Next.js.

## Contato

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [lucasmef@gmail.com](mailto:lucasmef@gmail.com)
