# 🎤 Quiz K-Pop: Missão da Acentuação

Jogo de perguntas sobre acentuação em português, com grupos de K-Pop, criado pelos alunos.
São 5 fases, da mais fácil à "mega impossível", com pontuação e barra de progresso.

## Como jogar

Abra o link do jogo (GitHub Pages):

https://szadil763.github.io/k-pop/

Ou baixe o projeto e abra o arquivo `index.html` no navegador. Não precisa instalar nada.

## Estrutura

```
k-pop/
├── index.html    # o jogo inteiro (visual + perguntas + lógica)
├── images/       # fotos usadas em cada pergunta
├── README.md
└── CLAUDE.md
```

## Como adicionar ou editar perguntas

No `index.html`, procure a lista `perguntas`. Cada pergunta tem este formato:

```js
{
fase:"🎀 FASE 1 - FÁCIL",
grupo:"ILLIT",
imagem:"images/yunju.jpg",
pergunta:"Qual é a forma certa?",
opcoes:["Musica","Música","Musíca","Mùsica"],
correta:1
},
```

`correta` é a posição da resposta certa na lista `opcoes`, contando a partir de 0
(0 = primeira, 1 = segunda, 2 = terceira, 3 = quarta).

## Imagens

Coloque as fotos na pasta `images/`. O nome do arquivo precisa ser **idêntico** ao do código,
inclusive maiúsculas e minúsculas (`Yunju.jpg` é diferente de `yunju.jpg`).
Se uma foto não existir, o jogo continua funcionando e apenas não mostra a imagem.

Arquivos esperados pelo código:

- `yunju.jpg`
- `moka iroha e wonhee.webp`
- `martin e james.webp`
- `kjs.jpg`
- `cse.jpg`
- `yk.jpg`
- `sl.jpg`
- `danon.jpg`
- `meichae.jpg`
- `bangknow.jpg`
- `chanjin.jpg`
- `hanlix.jpg`
- `seungin.jpg`

## Publicar no GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Em 1 ou 2 minutos o jogo estará no ar.

## Créditos

Projeto criado pelos alunos com o GitHub Copilot, com orientação do professor Adilson.
