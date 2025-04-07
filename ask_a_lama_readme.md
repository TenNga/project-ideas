
# 🧘‍♂️ Ask a Lama Simulator

A calm, spiritual AI web app where users can ask questions about life and receive responses from a wise Tibetan Lama persona powered by GPT.

---

## 🌟 Project Idea

**Ask a Lama Simulator** is a web app that simulates speaking with a Tibetan Lama. Users can ask personal, philosophical, or emotional questions, and receive responses in a calm, compassionate tone based on Buddhist values and Tibetan wisdom.

It’s more than just GPT — it's a cultural experience, a spiritual space, and a bridge between ancient teachings and modern technology.

---

## ✨ Why Build This?

| Benefit                            | Why It Matters |
|-----------------------------------|----------------|
| 🌱 Cultural Preservation           | Digitally honors Tibetan spiritual wisdom |
| 💬 Tailored Spiritual Experience   | Not just general GPT — it’s focused, consistent, and calming |
| 🧘 For Non-Tech Users              | Elders or youth unfamiliar with GPT can easily engage |
| 🎨 Full Creative Control           | Design, tone, and UI tailored to a peaceful experience |
| 🚀 Developer Learning              | Frontend, backend, API, UX — real-world experience |
| 📱 Shareable Spiritual Companion   | Create something others can benefit from |

---

## 📦 Tech Stack

| Area         | Tool / Library            |
|--------------|----------------------------|
| Framework    | Next.js 14 (App Router)    |
| Styling      | Tailwind CSS, shadcn/ui    |
| API          | OpenAI GPT-4 / gpt-3.5     |
| Backend      | Next.js API route          |
| State Mgmt   | React useState/useEffect   |
| Hosting      | Vercel                     |
| Optional     | Framer Motion, Whisper API, LangChain, TTS APIs |

---

## 📂 Folder Structure

```
ask-a-lama/
├── app/
│   ├── page.tsx            # Main UI
│   └── api/
│       └── chat/route.ts   # Chat handler for OpenAI API
├── components/
│   └── ChatMessage.tsx     # Chat message UI component
├── lib/
│   └── chat.ts             # GPT logic abstraction
├── public/                 # Optional assets like icons, bg sound
├── styles/                 # Global CSS
├── .env.local              # API Key config
├── README.md               # Project documentation
```

---

## 🧠 Prompt Design (System Message)

Used to instruct the model to behave like a Tibetan Lama:

```ts
const systemPrompt = `
You are a wise and compassionate Tibetan Lama. 
Speak in a calm, spiritual tone. Respond with teachings grounded in Buddhist philosophy. 
Use metaphors, references to nature, and classic Tibetan Buddhist wisdom. Avoid modern slang. 
Begin messages with phrases like "Dear one" or "Beloved student". Keep your tone kind, reflective, and concise.
`;
```

---

## 💻 Features (MVP)

- Clean, peaceful UI
- Chat experience with GPT-based Lama persona
- Consistent tone and styling
- Responsive for mobile use
- Hosted and shareable

---

## 🛣️ Future Features (V2+)

- 🈳 English / Tibetan language toggle
- 🔊 Text-to-Speech with calm Lama voice
- 🎵 Background Tibetan flute music toggle
- 📿 Daily Dharma quote pop-up
- 🧒 Children’s “Lama Story Mode”
- 🎙️ Speech input using Whisper API
- 🧠 Fine-tune a model on Tibetan texts (optional long-term goal)
- 📖 Favorite teachings/bookmarks

---

## ✨ Example Interaction

```
User: I feel overwhelmed and lost lately.

Lama: Dear one, even the brightest moon may be hidden by clouds. But the moon is still there. Rest in your breath. All things change.
```

---

## 🛠 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ask-a-lama
   cd ask-a-lama
   ```

2. Create `.env.local` and add your OpenAI key:
   ```
   OPENAI_API_KEY=your-key-here
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

---

## 🌍 Deployment

Deploy easily using [Vercel](https://vercel.com):

1. Push to GitHub
2. Connect repo to Vercel
3. Add `OPENAI_API_KEY` to Vercel Environment Variables
4. Deploy — done!

---

## 🙏 Creator

Made with intention by **Kevin Karma**, a Tibetan developer passionate about bridging cultural wisdom with modern tech.  
🔗 [GitHub](https://github.com/TenNga) | 🧘‍♂️ [Buy Me a Tea](buymeacoffee.com/kevinkarma)

---

## 📜 License

MIT — please use respectfully 🙏
