# diGamela — Landing Page (Linktree)

> Página de links estilo Linktree para o perfil da diGamela nas redes sociais.

---

## 📁 Estrutura de arquivos

```
digamela-linktree/
├── index.html   ← página principal
├── style.css    ← estilos
├── logo.png     ← ⚠️ COLOQUE SUA LOGO AQUI (veja abaixo)
└── README.md
```

---

## 🖼️ Como adicionar a logo

1. Pegue o arquivo de imagem da sua logo (PNG ou JPG).
2. Renomeie-o para **`logo.png`**.
3. Copie-o para a pasta do projeto (junto com `index.html`).

> Formatos aceitos: `.png` (recomendado, suporta fundo transparente), `.jpg`, `.webp`.  
> Se quiser usar outro nome/formato, edite a linha no `index.html`:
> ```html
> <img src="logo.png" ...>
> ```

---

## ✏️ Como editar os links

Abra o `index.html` em qualquer editor de texto e localize os botões:

```html
<a class="btn" href="#" target="_blank" rel="noopener">
```

Substitua o `href="#"` pelo link real de cada botão. Exemplos:

| Botão | Exemplo de link |
|---|---|
| Pedido | `https://wa.me/5562999999999?text=Quero+fazer+um+pedido` |
| WhatsApp/Atacado | `https://wa.me/5562988888888` |
| Fábrica/Retirada | `https://maps.google.com/?q=Endereço+da+Fábrica` |

Para **adicionar um botão novo**, copie um bloco `<a class="btn">...</a>` e cole logo abaixo do último, trocando ícone, texto e link.

Para **remover um botão**, apague o bloco `<a class="btn">...</a>` inteiro.

---

## 🌐 Como publicar no GitHub Pages (passo a passo)

### 1. Crie o repositório

1. Acesse [github.com](https://github.com) e faça login.
2. Clique em **"New repository"**.
3. Dê um nome (ex: `digamela-links`) e deixe **público**.
4. Clique em **"Create repository"**.

### 2. Suba os arquivos

**Opção A — Pelo site do GitHub (sem precisar de Git instalado):**

1. No repositório recém-criado, clique em **"uploading an existing file"**.
2. Arraste todos os arquivos: `index.html`, `style.css`, `logo.png`.
3. Clique em **"Commit changes"**.

**Opção B — Via terminal (Git instalado):**

```bash
git init
git add .
git commit -m "feat: landing page diGamela"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/digamela-links.git
git push -u origin main
```

### 3. Ative o GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **"Source"**, selecione **"Deploy from a branch"**.
3. Em **"Branch"**, escolha `main` e pasta `/ (root)`.
4. Clique em **Save**.

Aguarde ~1 minuto. Seu site estará disponível em:

```
https://SEU_USUARIO.github.io/digamela-links/
```

---

## 🎨 Personalização rápida

Abra o `style.css` e edite as variáveis no topo:

```css
:root {
  --bg:         #f2ead8;   /* cor do fundo da página */
  --bg-card:    #faf6ed;   /* cor do card central */
  --brown-dark: #6b1f1f;   /* marrom escuro */
  --gold:       #c8860a;   /* dourado */
  --green-dark: #1d4a35;   /* verde escuro */
}
```

---

## 📱 Onde usar o link

Cole a URL do GitHub Pages na **bio do Instagram**, WhatsApp, TikTok, etc.

---

Feito com ❤️ para diGamela · *sabor que abraça*
