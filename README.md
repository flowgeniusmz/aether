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
│   │   ├── db
│   │   ├── artifacts
│   │   ├── editor
│   │   └── utils.ts
│   │   └── constants.ts
├── public
├── tests
└── README.md

