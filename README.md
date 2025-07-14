# KindCampus

> **A modern, AI-powered campus platform for peer skill-swapping, online assignments, and instant collaboration.**

![KindCampus Banner](kindcampus/public/globe.svg)

---

## 🚀 What is KindCampus?
KindCampus is a next-generation web app designed to make campus life easier, smarter, and more fun. Connect with peers, swap skills, complete interactive assignments, and get instant AI-powered help—all in one beautiful, responsive platform.

---

## 🌟 Features

### 🤝 Peer Skill-Swapping & Team-Up (KindCollab)
- **Post & Discover Skills:** Share what you can teach or learn
- **Smart Matching:** Find the perfect study buddy or project partner
- **Instant Meetings:** Auto-generated Google Meet links
- **AI Icebreakers:** Never have an awkward intro again

### 📚 Online Assignments (KindTasks)
- **Code Challenges:** Write, test, and get instant feedback
- **Quizzes & Demos:** Interactive, auto-graded tasks
- **AI-Powered Hints:** Stuck? Get smart suggestions
- **Live Dashboard:** Teachers monitor progress in real time

### 💬 Global AI Chatbot
- **Floating, site-wide help** powered by Google Gemini
- **Suggested Q&A:** Click a question, get an instant answer
- **Fallback answers** for common campus topics

### ✨ Modern UX
- **Animations:** Framer Motion for smooth transitions
- **Accessible & Responsive:** Works on any device
- **Beautiful UI:** Tailwind CSS + shadcn/ui

---

## 🛠️ Tech Stack
- **Frontend:** Next.js 15, React 18, TypeScript
- **Styling:** Tailwind CSS, shadcn/ui
- **AI:** Google Gemini API
- **Animations:** Framer Motion
- **Icons:** Lucide React

---

## 🏁 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anishsarkars/KindCampus.git
   cd KindCampus/kindcampus
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Set up environment variables**
   Create a `.env.local` file in `kindcampus/`:
   ```env
   # Gemini API
   NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
   ```
4. **Run the development server**
   ```bash
   npm run dev
   ```
5. **Open your browser**
   Go to [http://localhost:3000](http://localhost:3000)

---

## 📁 Project Structure
```
KindCampus/
├── kindcampus/
│   ├── src/
│   │   ├── app/           # Next.js app router
│   │   ├── components/    # UI & feature components
│   │   ├── lib/           # Utilities & API helpers
│   │   └── types/         # TypeScript types
│   ├── public/            # Static assets
│   └── ...
├── README.md
└── ...
```

---

## 🌐 Deployment

### Vercel (Recommended)
1. Connect your GitHub repo to Vercel
2. Add your environment variables in the Vercel dashboard
3. Deploy! (Vercel auto-builds on push)

### Other Hosting
- Build with `npm run build` and deploy the `kindcampus/.next` output as needed

---

## 🤝 Contributing
1. Fork this repo
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to your branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License
MIT

---

## 💡 Support & Contact
- Open an issue on GitHub
- Email: support@kindcampus.com

---

> Made with ❤️ for campus communities everywhere. 