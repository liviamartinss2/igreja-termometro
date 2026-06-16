# Termômetro da Meta — Primeira Igreja Batista de Aquiraz

Página única (HTML/CSS/JS, sem build) que gera uma imagem de **termômetro de meta** pronta para
compartilhar no grupo ou usar nos slides. Basta digitar o valor arrecadado, escolher o tema e baixar.

## Como usar

Abra o [`index.html`](index.html) no navegador. Não há instalação nem dependências para instalar:
tudo roda no próprio navegador.

1. Digite o **valor arrecadado** no mês.
2. Escolha o **tema de cores** e o **formato da imagem** (Slides 16:9 ou Quadrado).
3. (Opcional) Defina a **data/título** e envie um **logo PNG transparente**.
4. (Opcional) Ajuste as **metas** (despesas do mês e meta do terreno).
5. Clique em **Baixar imagem** ou **Copiar imagem**.

O preenchimento mostra quanto já entrou; o percentual indica quanto das despesas já está coberto.
A faixa do terreno mostra quanto ainda falta. Quando o arrecadado passa das despesas, o
preenchimento avança sobre o terreno e o valor a faltar diminui.

## Hospedagem (GitHub Pages)

Como é um site estático, pode ser publicado direto pelo GitHub Pages:
**Settings → Pages → Branch: `main` / root**. O `index.html` na raiz vira a página inicial.

## Tecnologia

- HTML, CSS e JavaScript puro, tudo em um único arquivo.
- Renderização via `<canvas>`; exportação como PNG.
- Fonte Poppins carregada via Google Fonts (CDN).
