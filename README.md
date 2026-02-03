# waiyanphyo
dragon888-webapp/
├─ app/
│  ├─ layout.tsx
│  ├─ page.tsx                # Home (redirect or landing)
│  ├─ game/
│  │  └─ page.tsx             # Slot Game main UI
│  ├─ tasks/
│  │  └─ page.tsx             # Join channels to earn points
│  ├─ api/
│  │  ├─ me/route.ts          # (optional) demo: return user + balance
│  │  └─ spin/route.ts        # (optional) server-side spin (demo only)
│  └─ globals.css
├─ components/
│  ├─ SlotReels.tsx
│  ├─ BetControls.tsx
│  ├─ TopBar.tsx
│  ├─ RulesModal.tsx
│  ├─ LanguageSwitch.tsx
│  └─ TaskCard.tsx
├─ lib/
│  ├─ telegram.ts             # initData parse + helper
│  ├─ i18n.ts                 # basic i18n loader
│  └─ config.ts               # constants (bet limits, multipliers)
├─ locales/
│  ├─ my.json
│  └─ en.json
├─ public/
│  ├─ dragons/
│  │  ├─ red.png
│  │  ├─ blue.png
│  │  ├─ green.png
│  │  └─ any.png
│  └─ ui/
│     └─ bg.jpg
├─ next.config.js
├─ package.json
├─ tsconfig.json
└─ .env.example
