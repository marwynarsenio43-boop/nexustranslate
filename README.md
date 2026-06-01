# 🌐 NexusTranslate — IA de Voz & Tradução

> Sistema de IA com **Speech-to-Text**, **Tradução Automática** e **Text-to-Speech**  
> Trabalho académico — ISCIM · Sistemas de Informação

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-00ffe7?style=flat-square)](https://SEU-USERNAME.github.io/nexustranslate)
[![Licença](https://img.shields.io/badge/licença-MIT-39ff14?style=flat-square)](LICENSE)

---

## ✨ Funcionalidades

| # | Funcionalidade | Tecnologia |
|---|---|---|
| 1 | 🎙 **Speech-to-Text** | Web Speech API (nativa do browser) |
| 2 | ⚡ **Tradução automática** | Claude API (Anthropic) ou MyMemory (gratuito) |
| 3 | 🔊 **Text-to-Speech** | Web Speech Synthesis API (nativa) |
| 4 | 🔄 **Troca de idiomas** | Swap instantâneo de idioma e texto |
| 5 | 📋 **8 idiomas** | PT, EN, ES, FR, ZH, AR, DE, IT |

---

## 🚀 Como usar (online)

Acede diretamente em:  
**`https://SEU-USERNAME.github.io/nexustranslate`**

> Funciona melhor no **Google Chrome** ou **Microsoft Edge**  
> (necessário para Speech-to-Text)

---

## 💻 Como correr localmente

```bash
# 1. Clona o repositório
git clone https://github.com/SEU-USERNAME/nexustranslate.git

# 2. Entra na pasta
cd nexustranslate

# 3. Abre no browser
# Simplesmente abre o ficheiro index.html no Chrome
```

> **Nota:** Para o microfone funcionar localmente, abre com um servidor local:
> ```bash
> # Python (se tiveres instalado)
> python -m http.server 8080
> # Depois abre: http://localhost:8080
> ```

---

## 🔑 API Key (opcional)

- A aplicação funciona **sem API Key** usando o serviço gratuito [MyMemory](https://mymemory.translated.net/)
- Para tradução mais precisa com IA, obtém uma chave gratuita em [console.anthropic.com](https://console.anthropic.com)
- A chave é guardada **apenas no teu browser** (`localStorage`) — nunca é enviada para nenhum servidor nosso

---

## 📁 Estrutura do projeto

```
nexustranslate/
├── index.html        # Página principal
├── favicon.svg       # Ícone da app
├── css/
│   └── style.css     # Estilos (tema cyberpunk/terminal)
├── js/
│   └── app.js        # Lógica da aplicação
└── README.md         # Este ficheiro
```

---

## 🛠️ Tecnologias

- HTML5 / CSS3 / JavaScript (Vanilla — sem frameworks)
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) — STT & TTS
- [Anthropic Claude API](https://www.anthropic.com) — Tradução IA
- [MyMemory API](https://mymemory.translated.net/) — Tradução gratuita (fallback)

---

## 📸 Screenshots

> *(adiciona screenshots aqui após o deploy)*

---

## 📝 Licença

MIT © 2026 — ISCIM · Sistemas de Informação
