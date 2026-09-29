# ⚡ LocalAI.dev — Ollama + OpenCode

> Guia completo e landing page para rodar IA 100% local com **Ollama** integrado ao **OpenCode**.  
> Privado, rápido e sem nuvem.

![Status](https://img.shields.io/badge/status-stable-green?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

---

## 📸 Preview

<p align="center">
  <a href="https://vitormenoli.github.io/Ollama-com-OpenCode/">
    <img src="https://i.imgur.com/3MOyvSk.png" alt="Preview do site" width="800" />
  </a>
</p>

> 🚀 [Veja o Site aqui](https://vitormenoli.github.io/Ollama-com-OpenCode/)

---

## ✨ Features

- 🎨 **Design dark moderno** com gradientes animados e glassmorphism
- 📱 **100% responsivo** — mobile, tablet e desktop
- 🚀 **Zero dependências** — HTML, CSS e JS puros
- ⚡ **Performance máxima** — single file, sem frameworks
- 🌊 **Animações suaves** — scroll reveal, hover effects, orbs flutuantes
- 📋 **Botão copiar código** com feedback visual
- 🎯 **FAQ interativo** com accordion animado
- 🌐 **SEO otimizado** com meta tags completas
- 🎭 **Acessibilidade** — navegação por teclado e aria-labels

---

## 🛠️ Stack Tecnológica

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura semântica |
| **CSS3** | Variáveis CSS, Grid, Flexbox, animações |
| **JavaScript (Vanilla)** | Interatividade (menu, FAQ, scroll, copy) |
| **IntersectionObserver** | Animações ao rolar a página |

> **Sem build tools, sem npm install, sem bundler.** É só abrir e usar.

---

## 🚀 Como usar

### Opção 1 — Abrir diretamente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/localai-dev.git
cd localai-dev

# Abra o arquivo no navegador
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### Opção 2 — Servidor local (recomendado para desenvolvimento)

Com **Python**:
```bash
python -m http.server 8000
# Acesse: http://localhost:8000
```

Com **Node.js** (usando `serve`):
```bash
npx serve .
```

Com **VS Code**:
Instale a extensão *Live Server* e clique em "Go Live".

---

## 📁 Estrutura do Projeto

```
localai-dev/
├── index.html          # Site completo (single file)
├── README.md           # Este arquivo
├── docs/
│   └── preview.png     # Screenshot para o README
└── LICENSE             # Licença MIT
```

> 💡 Todo o CSS e JavaScript está embutido no `index.html` para facilitar deploy e compartilhamento.

---

## 🎨 Personalização

Todas as cores e estilos estão em **variáveis CSS** no `:root`. Edite para adaptar ao seu brand:

```css
:root {
  --bg: #07090f;              /* Fundo principal */
  --accent: #7c6cff;          /* Roxo primário */
  --accent-2: #38d9c8;        /* Ciano secundário */
  --accent-3: #ff6ec7;        /* Rosa destaque */
  --grad: linear-gradient(135deg, #7c6cff 0%, #38d9c8 100%);
  --radius: 18px;             /* Borda dos cards */
  --font: 'Segoe UI', system-ui, sans-serif;
  --mono: 'Cascadia Code', 'Fira Code', monospace;
}
```

### Trocar conteúdo

- **Textos do hero**: procure por `<header class="hero">`
- **Features**: seção `#features` com `.cards-grid`
- **Modelos**: tabela em `#models`
- **FAQ**: lista em `#faq` com `.faq-item`
- **Links do footer**: `<footer>` no final do arquivo

---

## 🌍 Deploy

### GitHub Pages

```bash
# Commit e push
git add .
git commit -m "feat: landing page completa"
git push origin main

# Ative o Pages em: Settings → Pages → Source: main branch
```

### Netlify

```bash
# Arraste a pasta para https://app.netlify.com/drop
# OU use o CLI:
netlify deploy --prod --dir=.
```

### Vercel

```bash
npm i -g vercel
vercel --prod
```

### Cloudflare Pages

1. Conecte o repositório GitHub
2. Build command: *(vazio)*
3. Output directory: `/`

---

## 🙏 Créditos

- **[Ollama](https://ollama.com)** — runtime local de modelos LLM
- **[OpenCode](https://github.com/opencode-ai/opencode)** — interface terminal para IA
- Design inspirado em landing pages modernas de produtos developer-first

---

<p align="center">
  <strong>Feito com ❤️ para a comunidade dev brasileira</strong><br/>
  <sub>Se esse projeto te ajudou, considere deixar uma ⭐!</sub>
</p>