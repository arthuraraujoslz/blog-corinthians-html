# Blog do Coringão — Desenvolvimento Web

Este repositório contém o projeto do **Blog do Coringão**, desenvolvido para a disciplina de Desenvolvimento Web, cobrindo a estrutura HTML5 semântica e a estilização CSS com Flexbox.

## Sobre o Projeto

O **Blog do Coringão** é um portal voltado para a torcida do Corinthians, reunindo notícias, apresentação do novo uniforme oficial e um formulário de inscrição para o Fiel Torcedor.

## Etapas do Projeto

### Semana 01 — Estrutura HTML Semântica
- **Estrutura Base:** `<!DOCTYPE html>`, `<html lang="pt-BR">`, `<head>` e `<body>`.
- **Tags Semânticas:** `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>` e `<footer>`.
- **Formulário NATIVO (`<aside>`):** 
  - Submissão via método `GET`.
  - Agrupamento com `<fieldset>` e `<legend>`.
  - Validações nativas de `minlength`, `type="email"`, `min` e `max` para idade.
  - Seleção de plano do Fiel Torcedor (`<select>`) e aceite de termos (`<input type="checkbox">`).
  - Associação correta entre `<label>` e campos via atributos `for` e `id`.

### Semana 02 — Estilização com CSS & Flexbox
- **Container do Formulário:** Configurado com largura máxima, padding e cor de fundo personalizada.
- **Layout com Flexbox:** Organização vertical com `display: flex`, `flex-direction: column` e `gap`.
- **Estilização dos Inputs:** Aplicação de `padding`, `border`, `border-radius` e `font-size` em `<label>`, `<input>` e `<select>`.
- **Botão Personalizado:** Destaque visual com transição e efeito `button:hover`.
- **Bónus Flexbox:** Layout responsivo lado a lado para os campos de Nome e E-mail utilizando `justify-content: space-between`.

## Arquivo do Repositório

- `index.html`: Código-fonte completo consolidado com HTML5 semântico e CSS3 incorporado.




