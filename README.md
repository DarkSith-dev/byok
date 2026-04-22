# 🤖 Gemini Chat App (BYOK)

Um aplicativo simples de chat com IA usando a API do Gemini, onde cada usuário utiliza sua própria chave de API (**BYOK — Bring Your Own Key**).

---

## 🚀 Funcionalidades

* 🔑 Entrada de API Key do usuário
* 💬 Chat com IA (Gemini)
* ⚡ Respostas em tempo real
* 💾 Armazenamento da chave no navegador (localStorage)
* 🎨 Interface simples e funcional

---

## 🧠 Tecnologias utilizadas

* HTML
* CSS
* JavaScript (Vanilla)
* API do Gemini (Google)

---

## 📦 Como rodar o projeto

### ⚠️ Importante

Não abra os arquivos diretamente (file://). Use um servidor local.

---

### ▶️ Opção 1 — Live Server (recomendado)

1. Instale o Visual Studio Code
2. Instale a extensão **Live Server**
3. Clique com botão direito no `index.html`
4. Clique em **"Open with Live Server"**

---

### ▶️ Opção 2 — Node.js

```bash
npx serve
```

ou

```bash
npx http-server
```

---

## 🔑 Como usar

1. Gere uma API Key no Google AI Studio
2. Abra o app
3. Cole sua API Key (ex: `AIza...`)
4. Comece a conversar com a IA 🤖

---

## 🔗 Endpoint utilizado

```
https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent
```

---

## ⚠️ Aviso de segurança

Este projeto é um MVP (mínimo viável):

* A API Key é armazenada no navegador (localStorage)
* Não é recomendado para produção sem backend
* O usuário é responsável pela própria chave

---

## 💡 Melhorias futuras

* 🧾 Histórico de conversa
* 🎨 Interface estilo ChatGPT
* 🔐 Autenticação de usuários
* ☁️ Backend para maior segurança
* 🔗 Integração com automações (ex: n8n)

---

## 📄 Licença

MIT

---

## 👨‍💻 Autor

Feito por você 😄🔥
