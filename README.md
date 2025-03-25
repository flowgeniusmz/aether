# aether

## Architecture
AETHER [CODESPACES: SUPRE...]
├── app
│   ├── (account)
│   │   ├── account
│   │   ├── billing
│   │   ├── api
│   ├── (auth)
│   │   ├── login
│   │   ├── register
│   │   ├── api
│   │   │   ├── auth
│   │   │   │   ├── [...nextauth]
│   │   │   │   │   └── route.ts
│   ├── (chat)
│   │   ├── chat
│   │   │   ├── [id]
│   │   │       └── page.tsx
│   │   ├── api
│   │   │   ├── chat
│   │   │   │   └── route.ts
│   │   │   ├── document
│   │   │   │   └── route.ts
│   │   │   ├── files
│   │   │   │   └── route.ts
│   │   │   ├── history
│   │   │   │   └── route.ts
│   │   │   ├── suggestions
│   │   │   │  └── route.ts
│   │   │   ├── vote
│   │   │   │   └── route.ts
│   ├── artifacts
│   │   ├── code
│   │   │   ├── client.tsx
│   │   │   ├── server.ts
│   │   ├── image
│   │   │   ├── client.tsx
│   │   │   ├── server.ts
│   │   ├── text
│   │   │   ├── client.tsx
│   │   │   ├── server.ts
│   │   ├── sheet
│   │   │   ├── client.tsx
│   │   │   ├── server.ts
│   ├── components
│   │   ├── ui
│   ├── docs
│   ├── hooks
│   │   ├── use-artifacts.ts
│   │   ├── use-chat-visibility.ts
│   │   ├── use-mobile.tsx
│   └── lib
│   │   ├── ai
│   │   │   ├── tools
│   │   │   │   ├── create-document.ts
│   │   │   │   ├── get-weather.ts
│   │   │   │   ├── request-suggestions.ts
│   │   │   │   ├── update-document.ts
│   │   │   ├── models.test.ts
│   │   │   ├── models.ts
│   │   │   ├── prompts.ts
│   │   │   ├── providers.ts
│   │   ├── db
│   │   │   ├── helpers
│   │   │   │   ├── a
│   │   │   ├── migrations
│   │   │   │   ├── a
│   │   │   ├── queries.ts
│   │   │   ├── schema.ts
│   │   │   ├── migrate.ts
│   │   ├── artifacts
│   │   │   ├── server.ts
│   │   ├── editor
│   │   └── utils.ts
│   │   └── constants.ts
├── public
├── tests
└── README.md

