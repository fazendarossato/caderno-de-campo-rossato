# Como publicar o Caderno de Campo Digital no GitHub Pages

Leva uns 5 minutos, não precisa saber programar. Faça isso uma única vez —
depois, para atualizar, é só repetir o Passo 3.

## Passo 1 — Criar uma conta no GitHub (se ainda não tiver)
1. Acesse https://github.com/signup
2. Crie a conta com o e-mail que preferir (pode ser o e-mail da fazenda).

## Passo 2 — Criar o repositório
1. Acesse https://github.com/new
2. Em "Repository name", digite: `caderno-de-campo-rossato`
3. Marque a opção **Public** (precisa ser público para o GitHub Pages funcionar de graça)
4. Clique em **Create repository**

## Passo 3 — Subir os arquivos
1. Na página do repositório recém-criado, clique no link **"uploading an existing file"**
   (ou "adicionar arquivo" → "fazer upload de arquivos")
2. Arraste estes 5 arquivos para a área de upload:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Role para baixo e clique em **Commit changes**

> Para atualizar depois (quando eu gerar uma nova versão com dados novos),
> repita este passo — é só arrastar o `index.html` novo por cima, o GitHub
> substitui o antigo automaticamente.

## Passo 4 — Ativar o GitHub Pages
1. No repositório, vá em **Settings** (menu superior)
2. No menu lateral esquerdo, clique em **Pages**
3. Em "Branch", selecione **main** e a pasta **/ (root)**
4. Clique em **Save**
5. Espere ~1 minuto e recarregue a página — vai aparecer um link do tipo:
   `https://SEU-USUARIO.github.io/caderno-de-campo-rossato/`

Esse é o link fixo que todo mundo da fazenda vai usar.

## Passo 5 — Instalar no celular para uso offline no campo
1. Abra o link acima no celular (com internet/wifi)
2. Vai aparecer uma faixa na parte de baixo da tela: **"Instalar"**
   - No Android/Chrome: toque em Instalar — vira um ícone na tela inicial, como um app.
   - No iPhone/Safari: toque no ícone de compartilhar (□↑) → **"Adicionar à Tela de Início"**
3. Pronto — a partir daí, o app abre direto da tela inicial, mesmo sem sinal no campo.
   Ele só precisa de internet de novo quando eu publicar uma atualização nova.

## Como funciona a atualização
- O app guarda uma cópia local no celular (cache) na primeira vez que abre com sinal.
- Toda vez que o celular tiver internet e o app for aberto, ele checa em segundo
  plano se há uma versão nova no GitHub Pages e atualiza sozinho.
- No campo, sem sinal, sempre mostra a última versão que conseguiu baixar.

---
Qualquer nova foto do caderno ou correção de produto continua sendo tratada
aqui no chat com o Claude — eu atualizo o `index.html` e te aviso para repetir
o Passo 3.
