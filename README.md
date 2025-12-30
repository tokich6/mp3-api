# mp3-api

├── src/
│   ├── server.ts           # Express server setup
|   ├── app.ts              # Express app setup
│   ├── routes/
│   │   └── upload.ts       # /file-upload endpoint
│   ├── services/
│   │   └── mp3Parser.ts    # Core MP3 parsing logic
│   ├── middleware/
│   │   └── errorHandler.ts # Error handling middleware
│   └── interfaces/
│       └── index.ts        # TypeScript type definitions
├── tests/
│   └── mp3Parser.test.ts   # Unit tests
├── package.json
├── tsconfig.json
├── .eslintrc.json
├── .prettierrc
└── README.md