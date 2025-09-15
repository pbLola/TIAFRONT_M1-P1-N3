# Projeto: Página de Notícia — Jornal TIA 📰

Uma página web semântica e acessível que simula a cobertura de um protesto, com foco em **revisão de semântica, organização de pastas, links e imagens**. O projeto aplica boas práticas de **HTML5 semântico, acessibilidade (ARIA + visually hidden), responsividade mobile-first e design tokens em CSS seguindo UI Kit Neumorphic Colorido**.

---

![Print do Projeto](assets/screenshots/screenshot.png)

## ✨ Funcionalidades

- Estrutura semântica com `header`, `main`, `article`, `aside` e `footer`.
- SEO otimizado com `<title>` e `<meta name="description">`.
- Navegação acessível:

  - `role="banner"`, `role="navigation"`, `role="search"`, `role="contentinfo"`.
  - Labels ocultos com `.visually-hidden`.
  - Uso de `aria-labelledby` e `aria-label`.

- Inclusão de imagens com descrições (`alt`) e créditos (`figcaption`).
- Tabela de dados com `<caption>`, `<thead>`, `<tbody>`.
- Layout com **CSS Grid e Neumorphism leve**.
- Design tokens para cores, sombras, bordas e tipografia (Poppins).
- Microinterações: hover em links, botões, imagens e cards.
- Responsividade mobile-first: mobile → tablet → desktop.

---

## 📂 Estrutura

```
projeto-p1-noticia/
├── README.md # Documentação do projeto
├── index.html # Página principal
├── css/
│   └── style.css # Estilos globais (UI Kit Neumorphic Colorido)
├── js/
│   └── main.js # Microinterações (hover, foco, etc.)
├── assets/
│   ├── img/
│   │   ├── hero.jpg
│   │   ├── author.jpg
│   │   ├── card1.jpg
│   │   └── logo.svg
│   └── screenshots/
│       └── screenshot.png
└── .gitignore
```

---

## 🖼️ Tecnologias

- **HTML5 semântico**
- **CSS3** (variáveis, grid, responsividade, sombras, Neumorphism)
- **JavaScript** (microinterações)
- **Google Fonts (Poppins)**

---

## ⚙️ Melhorias aplicadas na versão final

- Estrutura semântica revisada e organizada (header, main, article, aside, footer).
- Adicionado `meta description` para SEO.
- Tabela de dados do evento estruturada com `<thead>`, `<tbody>` e `<caption>`.
- Microinterações implementadas: hover em links, botões, imagens e cards.
- Tokens de cores, bordas e sombras aplicados seguindo UI Kit Neumorphic Colorido.
- Responsividade mobile-first: grid adaptável de 1 para 2 colunas.
- Acessibilidade reforçada com skip link e ARIA labels.

---

## 📝 Licença

Este projeto é de uso educacional.
© 2025 Jornal TIA — Todos os direitos reservados.
