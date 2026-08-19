<div align="center">

# Lucas Camargo Stivan

### Engenheiro de Software Full Stack · Arquiteto de Sistemas · DevOps

Construo produtos e plataformas resilientes combinando **engenharia de software**, **arquitetura distribuída**, **automação** e **cibersegurança**.

<p>
  <a href="mailto:lucamargostivan@gmail.com">
    <img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Enviar e-mail">
  </a>
  <a href="https://wa.me/5543999171501">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Conversar pelo WhatsApp">
  </a>
  <a href="https://github.com/Stivan-Lucas">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Perfil no GitHub">
  </a>
</p>

![Disponível para projetos](https://img.shields.io/badge/Disponível%20para%20projetos-0078D4?style=flat-square)
![Localização](https://img.shields.io/badge/Ivaiporã--PR%20%7C%20Brasil-2ea44f?style=flat-square)

</div>

---

## Sobre mim

Sou **Engenheiro Full Stack** e **Arquiteto de Sistemas**, com foco na criação de soluções escaláveis, seguras e sustentáveis. Gosto de transformar problemas complexos em sistemas bem estruturados, com APIs consistentes, automação de entrega e observabilidade desde o início do projeto.

Atualmente, concentro meus estudos e projetos em **sistemas RMM (Remote Monitoring and Management)**, **telemetria de endpoints**, **cibersegurança**, **microsserviços** e **sistemas distribuídos**. Minha abordagem combina pragmatismo de produto com rigor técnico: decisões simples quando possível, arquitetura robusta quando necessário.

| Perfil | Detalhes |
| --- | --- |
| **Localização** | Ivaiporã, Paraná — Brasil |
| **Idiomas** | Português nativo · Inglês profissional · Espanhol básico |
| **Especialidades** | Full Stack · Arquitetura de sistemas · DevOps · RMM · Cibersegurança |
| **Principais ecossistemas** | Node.js · TypeScript · Bun · Rust · React |
| **Disponibilidade** | Projetos, parcerias técnicas e oportunidades globais |

---

## Projeto em destaque: OmniNexus

O **OmniNexus** é um ecossistema de monitoramento e gerenciamento remoto de endpoints. A solução é organizada em componentes independentes para agente, backend e dashboard, permitindo evoluir cada camada sem perder clareza arquitetural. [1] [2] [3]

### Arquitetura em alto nível

```mermaid
flowchart LR
    A[Endpoints Windows<br/>OmniNexus Agent<br/>Rust] -->|HTTPS / JSON| B[OmniNexus Backend<br/>Bun + Fastify + TypeScript]
    B --> C[(PostgreSQL<br/>Drizzle ORM)]
    B --> D[(Redis)]
    B --> E[Dashboard Web<br/>Next.js + React]
```

### Componentes do ecossistema

| Repositório | Responsabilidade | Tecnologias em destaque |
| --- | --- | --- |
| [**omninexus-agent**](https://github.com/Stivan-Lucas/omninexus-agent) | Agente para Windows responsável por enrollment, inventário, telemetria, heartbeat, fila offline e execução de comandos autorizados. | Rust · Windows Service · `sysinfo` · PowerShell/CMD |
| [**omninexus-backend**](https://github.com/Stivan-Lucas/omninexus-backend) | Core da plataforma para receber, validar, persistir e disponibilizar dados de telemetria e comandos. | Bun · Fastify · TypeScript · Zod · Drizzle ORM · PostgreSQL · Redis |
| [**omninexus-frontend**](https://github.com/Stivan-Lucas/omninexus-frontend) | Dashboard responsivo para acompanhar agentes e visualizar telemetria em tempo real. | Next.js · React · Tailwind CSS · Radix UI · Lucide |

### Desafios técnicos explorados

O projeto reúne problemas práticos de engenharia, como comunicação confiável entre agentes e servidor, operação offline, identidade por dispositivo, controle de comandos, persistência de telemetria, segurança de endpoints e visualização de dados em tempo real.

---

## Stack e competências

### Linguagens e runtimes

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white" alt="Bun">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js">
</p>

### Desenvolvimento de aplicações

| Camada | Tecnologias e práticas |
| --- | --- |
| **Backend** | Fastify · Express · NestJS · APIs REST · autenticação · validação de dados · microsserviços |
| **Frontend** | React · Next.js · Angular · Tailwind CSS · Radix UI · dashboards responsivos |
| **Mobile** | React Native · Expo · Flutter |
| **Dados** | PostgreSQL · MySQL · MongoDB · SQLite · Redis · Drizzle ORM · Prisma |
| **Sistemas** | Rust · Windows Services · telemetria · comunicação HTTP/JSON · filas offline |
| **Qualidade** | Testes unitários · testes E2E · linting · formatação · Conventional Commits · Semantic Release |

### Infraestrutura e DevOps

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

Tenho especial interesse em **entrega contínua**, **automação operacional**, **hardening**, **observabilidade**, **documentação técnica** e na construção de sistemas que permaneçam fáceis de manter à medida que crescem.

---

## GitHub em números

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Stivan-Lucas&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true&rank_icon=github&locale=pt-br" alt="Estatísticas do GitHub de Lucas Camargo Stivan">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Stivan-Lucas&layout=compact&theme=transparent&hide_border=true&langs_count=8&locale=pt-br" alt="Linguagens mais utilizadas por Lucas Camargo Stivan">
</p>

---

## Vamos conversar?

Se você procura alguém para **projetar uma arquitetura**, **desenvolver uma plataforma**, **estruturar uma API** ou **automatizar uma operação**, será um prazer conversar sobre o problema e encontrar uma solução objetiva.

<p align="center">
  <a href="mailto:lucamargostivan@gmail.com"><strong>lucamargostivan@gmail.com</strong></a>
  &nbsp;·&nbsp;
  <a href="https://wa.me/5543999171501"><strong>WhatsApp</strong></a>
</p>

<p align="center">
  <sub>Construindo sistemas melhores, uma decisão técnica de cada vez.</sub>
</p>

---

## Referências

[1]: https://github.com/Stivan-Lucas/omninexus-agent "OmniNexus Agent — repositório oficial"
[2]: https://github.com/Stivan-Lucas/omninexus-backend "OmniNexus Backend — repositório oficial"
[3]: https://github.com/Stivan-Lucas/omninexus-frontend "OmniNexus Frontend — repositório oficial"
