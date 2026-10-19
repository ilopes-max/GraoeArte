# ☕ Grão & Arte - Torrefação e Café Especial

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

Projeto de desenvolvimento front-end para um cliente fictício do segmento de cafés especiais, focando em arquitetura semântica, acessibilidade, padronização via CSS/BEM e responsividade total.

---

## 📌 Visão Geral e Objetivo do Projeto

O objetivo deste projeto é construir a landing page oficial da **Grão & Arte - Torrefação e Café Especial**. A aplicação foi projetada para apresentar a marca, o catálogo de microlotes de café 100% Arábica, o processo artesanal de torra, os planos de clube de assinatura e sanar dúvidas frequentes dos clientes.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** Uso correto de tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<details>`, `<summary>`, `<footer>`) garantindo acessibilidade e estrutura limpa.
- **CSS3 Moderno & Design System:**
  - **Variáveis CSS (`:root`):** Padronização da paleta de cores, tipografia, sombras e raios de borda.
  - **Metodologia BEM (Block Element Modifier):** Nomenclatura organizada para classes e seletores.
  - **Flexbox Layout:** Utilizado para distribuição fluida de componentes e cards.
  - **Escala de Unidades Relativas:** Uso de `rem` para tipografia e espaçamentos (com base ajustada no elemento raiz) e unidades relativas como `%`, `vw` e `vh` para controle do layout.
- **Tipografia Externa:** Importação via Google Fonts (`Merriweather` e `Open Sans`).
- **Recursos Interativos:** Rolagem suave (`scroll-behavior: smooth`), transições com `:hover`, menu superior fixo e botão flutuante de atendimento via API do WhatsApp.

---

## 📂 Organização da Arquitetura de Arquivos

A estrutura do repositório segue rigorosamente a separação de responsabilidades:

```text
├── assets/
│   ├── css/
│   │   ├── variables.css   # Definição dos tokens do Design System
│   │   └── style.css       # Estilização geral dos componentes em BEM
│   └── images/             # Imagens e ativos visuais do projeto
├── index.html              # Estrutura principal da página
└── README.md               # Documentação completa do repositório