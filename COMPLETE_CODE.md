,,,,
hoodline-cad/
├── package.json
├── railway.json
├── Procfile
├── .gitignore
├── README.md
├── DEPLOYMENT.md
├── drizzle.config.json
├── server/
│   ├── index.ts
│   ├── routes.ts
│   ├── db.ts
│   ├── discordAuth.ts
│   └── storage.ts
├── shared/
│   └── schema.ts
└── client/
    ├── package.json
    ├── index.html
    ├── vite.config.ts
    ├── tailwind.config.js
    ├── postcss.config.js
    └── src/
        ├── main.tsx
        ├── App.tsx
        ├── index.css
        ├── hooks/
        │   └── useAuth.ts
        ├── lib/
        │   └── queryClient.ts
        ├── components/
        │   └── Layout.tsx
        └── pages/
            ├── Landing.tsx
            ├── Dashboard.tsx
            ├── Characters.tsx
            └── Calls.tsx
```

---

## ROOT FILES

### package.json
```json
{
  "name": "hoodline-cad",
  "version": "1.0.0",
  "description": "Computer-Aided Dispatch system for FiveM roleplay servers",
  "main": "server/index.ts",
  "scripts": {
    "dev": "npx tsx server/index.ts",
    "build": "echo 'Build complete'",
    "start": "npx tsx server/index.ts"
  },
  "dependencies": {
    "@neondatabase/serverless": "^0.9.0",
    "@types/cors": "^2.8.17",
    "@types/express": "^4.17.21",
    "@types/express-session": "^1.18.0",
    "@types/node": "^22.0.0",
    "@types/passport": "^1.0.16",
