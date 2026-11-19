# ⚡ PEDRO LOPES // WEB & NETWORKS (PL19)

[![Website](https://img.shields.io/badge/LIVE_PORTFOLIO-pdsl19.github.io-D2FF00?style=for-the-badge&labelColor=070709)](https://pdsl19.github.io)
[![GitHub](https://img.shields.io/badge/GITHUB-pdsl19-FFFFFF?style=for-the-badge&logo=github&labelColor=070709)](https://github.com/pdsl19)

Portfólio pessoal e dossier técnico interativo focado em **Desenvolvimento Web Full-Stack**, **Bases de Dados Relacionais** e **Infraestrutura de Redes**. Construído com uma arquitetura *zero-bloat*, interface de telemetria *dark mode* de alto contraste, física reativa e suporte bilingue (`PT ⇄ EN`) adaptado a PC e Mobile.

🔗 **Live Demo:** [https://pdsl19.github.io](https://pdsl19.github.io)

---

## 🛠️ Engine, Telemetria & Stack

- **Core:** HTML5 Semântico, JavaScript (ES6+) & Canvas 2D API
- **Styling:** Tailwind CSS (Temas dinâmicos: *LN4 Neon Volt `#D2FF00`*, *Papaya*, *Crimson* e *Cyber Cyan*) + `@media print`
- **Motion & Physics:** [GSAP](https://gsap.com/) (`ScrollTrigger` + `ScrollToPlugin`) para *3D Pitch/Yaw Tilt*, *Matrix Text Scramble*, inércia no *Marquee* e transições de câmara
- **Smooth Scroll:** [Lenis](https://lenis.darkroom.engineering/) sincronizado com o ticker do GSAP e *Scroll-Spy* automático
- **APIs & Áudio:** GitHub REST API (telemetria real de repositórios), Web Audio API (sintetizador SFX sem ficheiros externos), Performance/Paint API & Network Information API
- **Tipografia:** `Space Grotesk` (Display), `Inter` (Leitura) e `JetBrains Mono` (Telemetria/HUD)

---

## 🚀 Funcionalidades & Módulos Interativos

- **Terminal CLI Integrado (`Ctrl + K`):** Consola estilo Linux / Cisco IOS com comandos `whois`, `projects`, `stack`, `ping`, `ipconfig`, `cv`, `email` e atalhos de toque para mobile.
- **Simuladores nos Cartões de Projeto:**
  - *ISPGUIA — Student Hub:* Monitor de telemetria cíclico (`SYS_MONITOR // ISPGUIA.NODE`) e modal de arquitetura.
  - *Sistema de Gestão Integrado (PAP):* Consola de queries SQL/MariaDB em tempo real e diagrama relacional.
  - *Topologias LAN & Subnetting:* Simulação visual de pacotes ICMP salto-a-salto (`PC0 ── SW0 ── RTR0 ── SW1 ── PC1`) e plano VLSM.
- **Inspetor Raio-X da Stack (`STACK_XRAY`):** Diagnóstico interativo na secção técnica que detalha a aplicação prática de cada tecnologia em contexto real (Printgal, ISPGUIA, PAP e ISPGAYA).
- **Motor Bilingue Instantâneo (`PT ⇄ EN`):** Tradução dinâmica sem recarregamento de página com descodificação *Matrix* e persistência em `localStorage`.
- **Telemetria de Sistema & Hardware:** Medidor de FPS em tempo real, latência HTTP (`RTT Ping`), osciloscópio `<canvas>` reativo, auditoria DOM/FCP e *Smart Fast-Boot* no preloader.
- **Utilitários Rápidos:** Gerador dinâmico de cartão de contacto `vCard (.vcf)`, dispatcher de email pré-preenchido, modal de QR Code para sincronização mobile (`Tecla Q`), modo wireframe *CAD Blueprint* (`Tecla B`) e menu tático de clique direito.

---

## ⌨️ Atalhos de Teclado (Desktop)

| Tecla | Ação |
| :--- | :--- |
| **`1` – `4`** | Navegação rápida entre secções (`Projetos`, `Percurso`, `Stack`, `Contacto`) |
| **`5`** | Abrir / fechar visor de Currículo (`PDF`) |
| **`Ctrl + K`** | Abrir / fechar Terminal Interativo (`PL19_SHELL`) |
| **`E`** | Alternar idioma (`PT ⇄ EN`) |
| **`L`** | Alternar *Livery* (esquema de cores do HUD) |
| **`M`** | Ligar / silenciar sintetizador de som tático (`SFX`) |
| **`B`** | Ativar / desativar grelha técnica *CAD Blueprint* |
| **`D`** | Abrir painel de diagnóstico de hardware, rede e auditoria DOM/FCP |
| **`Q`** | Abrir modal de QR Code para *Mobile Handoff* |
| **`H` / `?`** | Abrir mapa completo de controlos |

---

## 📂 Projetos em Destaque no Site

1. **ISPGUIA — Student Hub:** Plataforma web interativa de apoio aos estudantes do ISPGAYA com horários, guias académicos e monitorização analítica em tempo real via GoatCounter.
2. **Sistema de Gestão Integrado (PAP):** Aplicação web full-stack em PHP e MySQL/MariaDB desenvolvida para o Centro Social Paroquial N. Sra. da Boavista (autenticação RBAC, gestão de permissões e CRUD completo).
3. **Topologias LAN & Subnetting:** Planeamento e simulação de redes empresariais no Cisco Packet Tracer (VLSM, VLANs 802.1Q, Routing & Switching via Cisco IOS CLI).

---

## 📁 Estrutura do Repositório

```text
├── index.html               # Aplicação Single-Page (UI, Engine GSAP/Lenis, Terminal CLI & Telemetria)
├── 404.html                 # Página personalizada de erro de rota (ICMP_ERROR // PACKET DROPPED)
├── pdfs/
│   └── CV_PedroLopes.pdf    # Currículo oficial em PDF para pré-visualização e download direto
└── README.md                # Documentação do repositório
```

---

## 📬 Contacto

* **Nome:** Pedro Dinis Lopes
* **Localização:** Vila Nova de Gaia, Portugal
* **Email:** [pedrodinislopes@gmail.com](mailto:pedrodinislopes@gmail.com)
* **GitHub:** [github.com/pdsl19](https://github.com/pdsl19)