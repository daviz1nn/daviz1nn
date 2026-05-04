<h1 align="center">Davi Figueiredo Martins</h1>

<p align="center">
  <b>Computer Science @ FEI</b> · São Paulo, Brazil
  <br/>
  Construindo agentes de IA, sistemas de automação e percepção para veículos autônomos
  <br/>
  <br/>
  <a href="https://www.linkedin.com/in/davi-figueiredo-martins-a00525262/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/daviz1nn/projeto-ic-veiculo-autonomo"><img src="https://img.shields.io/badge/Featured%20repo-IC%20Ve%C3%ADculo%20Aut%C3%B4nomo-22314E?logo=ros" alt="Featured repo"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Freelance%20%26%20Roles-success" alt="Open to work"/>
</p>

---

## 👋 Sobre

Sou estudante de Ciência da Computação na **FEI (São Paulo)**, atualmente em Iniciação Científica desenvolvendo um sistema completo de navegação para veículo autônomo em escala 1/10 (chassis F1TENTH, ROS 2 Jazzy, Gazebo Harmonic, pipeline próprio de gêmeo digital em Blender + Phobos).

Em paralelo, atuo como **freelancer**: construo agentes de IA, automações de processos e SaaS multi-tenant para clientes reais. Nos últimos 6 meses entreguei um chatbot de IA em produção 24/7, um sistema multi-tenant fiscal-completo para importadoras e um site institucional para barbearia — todos do zero.

Stack favorita: **Python + TypeScript + ROS 2**, com integração de **Claude API**, **Supabase**, **OpenCV**, **Blender + Phobos**, **n8n** e infraestrutura serverless.

---

## 🛠️ Stack

**AI / Automation**
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

**Web / SaaS**
<br/>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000)
![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)

**Robotics / 3D / Simulation**
<br/>
![ROS 2](https://img.shields.io/badge/ROS_2_Jazzy-22314E?logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo_Harmonic-0288D1)
![Blender](https://img.shields.io/badge/Blender_4.2-F5792A?logo=blender&logoColor=white)
![Phobos](https://img.shields.io/badge/Phobos_2.0-7E57C2)
![Three.js](https://img.shields.io/badge/Three.js-000?logo=three.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![WSL2](https://img.shields.io/badge/WSL2-4D4D4D?logo=linux&logoColor=white)

---

## 🚗 Featured

### [`projeto-ic-veiculo-autonomo`](https://github.com/daviz1nn/projeto-ic-veiculo-autonomo) — IC FEI 2026/2027

Sistema completo de navegação autônoma em escala 1/10 (F1TENTH + câmera estéreo ZED). Quatro módulos integrados — percepção (OpenCV), localização (EKF), planejamento (A*) e controle (pure pursuit + PID) — em arquitetura modular ROS 2.

**Diferencial:** o **gêmeo digital é construído do zero** dentro do repo, no Blender 4.2 com Phobos. Geometria, massa, inércia e juntas são modeladas no `.blend`, exportadas como URDF e simuladas no Gazebo Harmonic antes de qualquer teste físico.

```
Blender 4.2  →  Phobos 2.0  →  Gazebo Harmonic  →  ROS 2 Jazzy
 modelagem      URDF + meshes   simulação física    perception/control
```

🌐 Site público com **visualizador 3D interativo** em Three.js: [projeto-ic-veiculo-autonomo.vercel.app](https://projeto-ic-veiculo-autonomo.vercel.app)

---

## 💼 Case studies (repos privados)

Projetos em produção ou entregues a clientes reais. Código sob NDA — disponíveis para review **sob demanda em entrevista**.

### Agente de IA no WhatsApp para vendas B2B
> **Contexto:** cliente do setor náutico precisava qualificar e atender leads 24/7 sem perder o tom humano da marca.
> **Stack:** Node.js · Baileys · **Claude API** · Supabase (RLS, ~30 migrations) · React 18 + Tailwind v4 admin · Pino · Express
> **Outcome:** chatbot em produção no Railway com regressão automática (~95% de cobertura nos fluxos críticos), painel admin para handoff humano e persona definida por documento canônico.

### SaaS multi-tenant para importadora B2B
> **Contexto:** importadora em SP precisa unificar viagens, compras, estoque, vendas, motor fiscal e portal do cliente em um único produto.
> **Stack:** **TypeScript** · Vite · React 18 · TanStack Router/Query/Table · Radix UI · Tailwind 4 · **Supabase** (Postgres + RLS multi-tenant + Edge Functions) · 5 regimes fiscais brasileiros + classificador NCM.
> **Outcome:** plataforma operacional em sprints, com isolamento por tenant, motor fiscal customizado e portal externo para o cliente final. Em desenvolvimento ativo.

### Site institucional para cliente local — concluído
> **Contexto:** barbearia em SP queria presença digital com agendamento e identidade visual própria.
> **Stack:** Next.js · TypeScript · Tailwind · Supabase.
> **Outcome:** site entregue, em produção, projeto encerrado.

### Automação de mandados judiciais
> **Contexto:** sistema interno para automação de pós-diligência em documentos jurídicos digitalizados.
> **Stack:** **Python** · FastAPI · PostgreSQL · OCR + regex com classificação por confidence score · pytest.
> **Outcome:** V1 operacional consolidando casos a partir de PDFs escaneados → extração de campos → banco → planilha.

### 1K.AI — iniciativa própria
> **Contexto:** ecossistema de marca com vertente B2B (SaaS de IA aplicada) e vertente editorial. Em refundação.
> **Trabalho:** definição de produto, estratégia de marca, prototipagem de prompts e pipelines, brand books reutilizáveis.

---

## 🧊 Crossover Engenharia × 3D

Um diferencial em relação a CVs típicos de CC: **modelagem 3D para robótica e simulação**.

No IC, o veículo inteiro é modelado em Blender e exportado para URDF via Phobos — não é um modelo pronto baixado da internet. Isso significa controlar geometria de colisão (convex hull), inércia automática, eixos de junção (Ackermann) e materiais visuais, e validar tudo com `check_urdf` antes de subir no Gazebo.

Em projetos não-acadêmicos, a stack 3D também aparece em geração de criativos (Three.js no site do IC, prompts Blender + Firefly + FLUX em pipelines de marca).

### Próximo capítulo: game engines & VR

A simulação física que faço no Gazebo é, conceitualmente, o que motores de jogo (PhysX no Unreal, Havok no Unity) fazem. O pipeline Blender → URDF é equivalente a asset pipelines de tools engineers em estúdios. Three.js é WebXR um passo distante. C++17 já uso para nós críticos do ROS — é a linguagem nativa do Unreal.

A direção próxima é estender essa stack para **Unity, Unreal Engine 5 e VR (Meta Quest 2 disponível no laboratório)** — começando por portar o digital twin do veículo do IC para Unreal, e depois construir uma cena VR de visualização imersiva da simulação. Aberto a oportunidades em jogos, VR e R&D de simulação.

---

## 🎓 Academic

- **Centro Universitário FEI** — Bacharelado em Ciência da Computação (em curso)
- **Iniciação Científica 2026/2027** — Sistema Computacional de Navegação Autônoma em Miniatura, sob orientação do Prof. Dr. Fagner de Assis Moura Pimentel (Departamento de Ciência da Computação)
- Vinculado à equipe **Robo FEI**, com vista à competição RoboCar Race
- Ambição de publicação em workshops de IROS / ICRA / CVPR-AD e SBR/CBR durante a IC

---

## 📫 Contato

- **LinkedIn:** [davi-figueiredo-martins-a00525262](https://www.linkedin.com/in/davi-figueiredo-martins-a00525262/)
- **GitHub:** [@daviz1nn](https://github.com/daviz1nn)
- **Email:** dfmartins0710@gmail.com
- **Disponibilidade:** aberto a projetos freelance e oportunidades em IA aplicada / automação / robótica / game development / VR

---

<details>
<summary><b>🇬🇧 English version</b></summary>

### About

Computer Science student at **FEI University (São Paulo, Brazil)**, currently in undergraduate research building a full autonomous-navigation stack for a 1/10-scale vehicle (F1TENTH chassis, ROS 2 Jazzy, Gazebo Harmonic, with an in-house digital-twin pipeline in Blender + Phobos).

In parallel I work as a **freelancer**: I build AI agents, process automations and multi-tenant SaaS for real clients. In the last 6 months I shipped a 24/7 production AI chatbot, a fully-fiscal multi-tenant SaaS for a B2B importer, and an institutional website for a local business — all from scratch.

### Featured

**[projeto-ic-veiculo-autonomo](https://github.com/daviz1nn/projeto-ic-veiculo-autonomo)** — Complete autonomous-driving stack on a 1/10 F1TENTH chassis. Four integrated modules — perception (OpenCV), localization (EKF), planning (A*), control (pure pursuit + PID) — in modular ROS 2 architecture. The vehicle's **digital twin is built from scratch** in Blender 4.2, exported via Phobos as URDF, and simulated in Gazebo Harmonic before any field test. Public site with interactive 3D viewer at [projeto-ic-veiculo-autonomo.vercel.app](https://projeto-ic-veiculo-autonomo.vercel.app).

### Selected client work (private repos, available under NDA on request)

- **B2B WhatsApp AI agent** — Node.js + Baileys + Claude API + Supabase + React admin. In production at Railway, ~95% regression coverage on critical flows.
- **Multi-tenant SaaS for an importer** — TypeScript + React 18 + TanStack + Supabase (Postgres + RLS + Edge Functions). Five Brazilian tax regimes + NCM classifier.
- **Institutional website for a local client** — Next.js + TypeScript + Tailwind + Supabase. Project shipped and closed.
- **Judicial document automation** — Python + FastAPI + PostgreSQL + OCR with confidence scoring.

### Engineering × 3D crossover

A differentiator from typical CS CVs: **3D modeling for robotics and simulation**. The entire research vehicle is modeled in Blender and exported to URDF via Phobos — collision convex hulls, auto-inertia, Ackermann joints, all validated with `check_urdf` before reaching Gazebo. The 3D stack also appears in creative pipelines (Three.js on the project's public site).

### Next chapter: game engines & VR

The physics simulation I run in Gazebo is conceptually the same problem game engines solve (PhysX in Unreal, Havok in Unity). The Blender → URDF pipeline mirrors what tools engineers build at studios. Three.js is one step from WebXR. I already use C++17 for critical ROS nodes — Unreal's native language.

Next direction: extend this stack into **Unity, Unreal Engine 5, and VR (Meta Quest 2, available in the lab)** — starting by porting the IC digital twin into Unreal, then building an immersive VR visualization of the Gazebo simulation. Open to opportunities at game studios, VR projects and simulation R&D.

### Reach out

- **LinkedIn:** [davi-figueiredo-martins-a00525262](https://www.linkedin.com/in/davi-figueiredo-martins-a00525262/)
- **GitHub:** [@daviz1nn](https://github.com/daviz1nn)
- **Email:** dfmartins0710@gmail.com
- **Open to:** freelance projects and roles in applied AI, automation, robotics, game development and VR.

</details>
