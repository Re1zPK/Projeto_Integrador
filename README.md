# Projeto Integrador — GitHub Pages

## Como publicar

1. Crie um repositório no GitHub.
2. Envie todos estes arquivos para o repositório.
3. Vá em **Settings > Pages**.
4. Em **Source**, escolha **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`.
6. Clique em **Save**.

Depois de alguns minutos, a página ficará disponível em:

`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

---

## Como trocar a logo do IME

A logo aparece nesta linha do `index.html`:

```html
<img class="ime-logo" src="assets/logo-ime.png" alt="Logo do IME" />
```

Para trocar:

1. Coloque a imagem da logo dentro da pasta `assets`.
2. Use um nome simples, por exemplo: `logo-ime.png`.
3. No `index.html`, ajuste o caminho se o nome for diferente.

Exemplo:

```html
<img class="ime-logo" src="assets/minha-logo.png" alt="Logo do IME" />
```

---

## Como trocar o fundo do prédio

O fundo está definido no `style.css` nesta parte:

```css
url('assets/fundo-predio.jpg')
```

Para trocar:

1. Coloque sua imagem na pasta `assets`.
2. Use um nome simples, por exemplo: `predio.jpg`.
3. Troque no CSS:

```css
url('assets/predio.jpg')
```

Recomendo imagem horizontal, escura, em JPG, com pelo menos 1600 px de largura.

---

## Como trocar os links dos cards

No `index.html`, cada card começa assim:

```html
<a class="card" href="#" target="_blank">
```

Substitua `#` pelo link do Google Drive, PDF ou pasta.

Exemplo:

```html
<a class="card" href="https://drive.google.com/SEU-LINK" target="_blank">
```

---

## Como trocar os ícones dos cards

Cada card usa uma imagem SVG, por exemplo:

```html
<img src="assets/icon-arquitetura.svg" alt="" />
```

Você pode substituir o arquivo SVG por outro com o mesmo nome, ou alterar o caminho no `index.html`.

---

## Como alterar integrantes

No `index.html`, procure por:

```html
<div class="members-inline">
```

Edite os nomes dentro das tags `<b>`.
