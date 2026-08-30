<p align="center">
  <img src="https://sanatan-ai.vercel.app/logo.png" width="160" alt="Sanatan AI logo" />
</p>

# Sanatan AI

**The Soul of Intelligence**  
A bilingual, dharma-focused conversational AI built with Next.js and Google Gemini.

Sanatan AI helps you explore dharma, self-knowledge, and personal growth through intelligent, context-aware conversations.

---

## Demo
Visit the live demo: https://sanatan-ai.vercel.app/ (or your hosting URL)

---

## Features
- Bilingual conversational UI (add supported languages)
- Dharma-centered knowledge and guidance
- Built with Next.js for a fast, modern web experience
- Powered by Google Gemini (LLM) for natural, helpful responses
- Extensible: easy to add new dialogs, content, and translations

---

## Tech stack
- Next.js (React)
- Google Gemini (LLM)
- Vercel (recommended for deployment)
- (Add any other libraries, e.g., TailwindCSS, Prisma, etc.)

---

## Quick start (local)

Requirements:
- Node.js 18+ (or the version your project uses)
- npm or pnpm
- A Google Gemini API key (or other LLM credentials used by this project)

Steps:
1. Clone the repo
   ```bash
   git clone https://github.com/greatsanatanai/greatsanatanai.git
   cd greatsanatanai
   ```
2. Install dependencies
   ```bash
   npm install
   # or
   pnpm install
   ```
3. Create a local env file
   ```bash
   cp .env.local.example .env.local
   ```
   Edit `.env.local` and add your API key(s). Example variables:
   ```
   GEMINI_API_KEY=your-google-gemini-key
   NEXT_PUBLIC_API_URL=http://localhost:3000
   ```
   Replace the names above with the actual env variable names used in the project.
4. Run the app
   ```bash
   npm run dev
   ```
   Open http://localhost:3000

5. Build for production
   ```bash
   npm run build
   npm start
   ```

---

## Configuration
- Add any required environment variables to `.env.local`. Typical items:
  - GEMINI_API_KEY — Google Gemini / LLM API key
  - NEXT_PUBLIC_BASE_URL — public site URL (for OG images, redirects)
  - ...other API keys or feature flags used by the app

Check your code for exact variable names and add them to `.env.local.example` if they’re missing.

---

## Deployment
Recommended: Vercel — connect the GitHub repo and add the environment variables in the Vercel dashboard. If using another platform, follow the platform's Next.js deployment docs.

---

## Contributing
Contributions are welcome! A few ways to help:
- Report issues or open feature requests in the Issues tab
- Submit pull requests with fixes, translations, or new content
- Improve docs or add code comments
- Add tests and CI configuration

When opening a PR:
1. Fork the repo
2. Create a feature branch
3. Add tests / update docs
4. Open a PR with a clear description of changes

---

## Translation & Bilingual Support
To keep the project bilingual:
- Add translation files under the i18n/locales (or your chosen structure)
- Follow existing conventions for keys and pluralization
- Please keep dharma-specific terms accurate and respectful — cite sources where appropriate

---

## Privacy & Responsible Use
This project interacts with third-party LLMs. Make sure to:
- Not log or expose sensitive personal data
- Inform users how their data is used (add a privacy page)
- Respect copyright and quote sources when providing scripture or commentary

---

## Acknowledgements
- Logo & design: (credit if applicable)
- Maintained by: [@thesanatanai](https://github.com/thesanatanai)
- Inspired by dharma teachings and community contributors

---

## License
Add a LICENSE file to this repository. If you don't have one yet, consider MIT or another license that fits your goals.

---

## Contact
For support, collaboration or questions:
- GitHub: https://github.com/thesanatanai
- Project owner: greatsanatanai (this profile)
