# 🚀 Front-End Challenge – Landing Page com SASS e JS

Bem-vindo(a) ao desafio de Front-End!
O objetivo é praticar **HTML, CSS (com SASS)** e **JavaScript** desenvolvendo uma página realista e bem estruturada.

---

## 🎯 Objetivo

Criar uma **Landing Page Responsiva** para uma **Cafeteria Fictícia** usando **SASS para organizar os estilos** e **JavaScript para pequenas interatividades**.

---

## 📋 Requisitos do Projeto

1. **HTML**

   * Estrutura semântica da página (`header`, `main`, `section`, `footer`).
   * Menu de navegação fixo.
   * Seção de destaque com banner.
   * Seção “Cardápio” com pelo menos **6 cards de produtos**.
   * Seção “Contato” com formulário simples (nome, email, mensagem).

2. **SASS**

   * Usar **variáveis** para cores e tipografia.
   * Usar **mixins** para responsividade (mobile-first).
   * Usar **aninhamento** para organizar os seletores.
   * Criar pelo menos **2 partials** (`_header.scss`, `_footer.scss`) e importar no `style.scss`.
   * Usar **color.scale()** para gerar variações de cor (ex.: hover mais escuro).

3. **JavaScript**

   * Criar um **menu hambúrguer** para telas pequenas.
   * Validar o formulário de contato (não enviar vazio).
   * Bonus: adicionar **scroll suave** entre seções.

---

## 📦 Estrutura do Projeto

```
/assets (imagens, ícones)
/scss
   _header.scss
   _footer.scss
   style.scss
/css
   style.css (gerado)
/js
   script.js
index.html
README.md
```

---

## 🔧 Rodando o Projeto

1. Instale o SASS:

   ```bash
   npm install -g sass
   ```
2. Compile os estilos:

   ```bash
   sass --watch scss/style.scss css/style.css
   ```
3. Abra o `index.html` no navegador.

---

## 🎨 Inspiração de Design

* Paleta sugerida: tons de marrom, bege e branco (estilo cafeteria).
* Tipografia: uma fonte cursiva para títulos + fonte sem serifa para texto.
* Imagens: use fotos de café de bancos gratuitos como [Unsplash](https://unsplash.com).

---

## 🏅 Critérios de Avaliação

* **Organização do código** (HTML semântico, SASS modularizado).
* **Responsividade** (funciona bem em desktop e mobile).
* **Design** (cores, tipografia, espaçamento).
* **Funcionalidade** (menu e formulário funcionando).
* **Criatividade** (animações, ícones, detalhes extras).

---

## 📌 Entrega

* Cada equipe deve criar uma **branch** no repositório.
* Subir o projeto completo.
* Abrir um **Pull Request** descrevendo as soluções aplicadas.

Boa sorte e bom código! 🚀
