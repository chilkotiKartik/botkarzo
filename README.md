
---

<a href="https://chat.kartikchil.com/">
  <img alt="Kartik Chilkoti AI Chatbot – Next.js 14 + Vercel AI SDK" src="app/(chat)/opengraph-image.png">
  <h1 align="center">🤖 Kartik Chilkoti AI Chatbot</h1>
</a>

<p align="center">
  A fully customizable, open-source AI chatbot built with <strong>Next.js 14</strong>, <strong>Vercel AI SDK</strong>, and <strong>shadcn/ui</strong>. <br/>
  Designed by <strong>Kartik Chilkoti</strong> to empower smart conversations, experimentation, and learning.
</p>

<p align="center">
  <a href="https://chat.kartikchil.com"><strong>Live Demo</strong></a> ·
  <a href="https://sdk.vercel.ai/docs"><strong>AI SDK Docs</strong></a> ·
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#local-setup"><strong>Local Setup</strong></a>
</p>

---

## 🚀 Features

- **Next.js 14 App Router**
  - Uses React Server Components and Server Actions
  - Fast, modern navigation & performance
- **AI SDK by Vercel**
  - Unified interface for multiple LLMs (xAI, OpenAI, Anthropic, etc.)
  - Custom hooks for chat UIs and dynamic interactions
- **shadcn/ui + Tailwind CSS**
  - Clean, accessible UI with beautiful component design
- **Auth.js**
  - Simple and secure authentication
- **Data Persistence**
  - Chat history stored in NeonDB
  - File storage via Vercel Blob

---

## 🧠 Model Providers

Default: `xAI Grok-2-1212`  
Easily switch to:

- OpenAI (GPT-4/3.5)
- Anthropic (Claude)
- Cohere
- Fireworks
- [All supported providers](https://sdk.vercel.ai/providers/ai-sdk-providers)



## 🛠 Local Setup


### 1. Clone the Repository

```bash
git clone https://github.com/your-username/kartik-chatbot.git
cd kartik-chatbot
````

### 2. Install Dependencies

```bash
pnpm install
```

> Or use `npm install` / `yarn install`

### 3. Setup Environment

```bash
cp .env.example .env
```

Fill in required values (e.g., API keys, secrets).

### 4. Start Development Server

```bash
pnpm dev
```

Your chatbot will be running at [http://localhost:3000](http://localhost:3000)

---

## 🔐 Environment Variables

Refer to `.env.example` for variables like:

* `AUTH_SECRET`
* `OPENAI_API_KEY` / `ANTHROPIC_API_KEY`
* `DATABASE_URL` (Neon/Postgres)

Do **not** commit `.env` publicly.

---

## 🧩 Folder Structure

```
/app              → Pages & routes (Next.js App Router)
/components       → UI components (shadcn/ui)
/lib              → Auth, AI SDK config, utils
/public           → Static assets
/styles           → Tailwind & global styles
.env.example      → Sample environment variables
```

---

## 🧪 Customization Ideas

* Add voice input/output
* Build multi-user dashboard
* Fine-tune welcome prompts
* Integrate image generation or code tools
* Add dark/light mode toggle

---

## 📜 License

MIT — Feel free to use, remix, and share.
Built with ❤️ by [Kartik Chilkoti](https://github.com/chilkotikartik)

---

> For any feature ideas, feedback, or collaboration, feel free to connect on [LinkedIn](https://linkedin.com/in/kartikchilkoti)

```

---

Let me know if you'd like a version with:
- Dark mode switch
- Custom avatar setup
- Hindi + English language toggler
- More advanced chatbot examples

I can adjust the README or even write code for it.
```

