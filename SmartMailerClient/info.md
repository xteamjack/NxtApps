- AI Powered Email Client - NextJS 14, OpenAI, Stripe, Prisma, Clerk
  - https://www.youtube.com/watch?v=Qm7-7PnszM4&t=549s
  - https://github.com/elliott-chong/normalhuman
  - Full functional with multiple email id registration, search,
  - AI reply generation, RAG based Chat
  - Different plans with upgrade functionality
  - trpc for connecting with email servre
  - WebHooks for debugging
  - UI
    - Simple, minimalistic UI inspired by ShadCn
    - Dark and light themes
    - Pane slider

# Technologies and Frameworks

- Next.js
- React
- TypeScript
- Tailwind CSS
- Clerk
- Prisma ORM
- PostgreSQL
- AWS SDK
- OpenAI API
- Stripe
- Axios
- Pinecone
- OpenAI Edge
- Neon Database Serverless
- @tanstack/react-query
- @clerk/nextjs
- clsx
- tailwind-merge

# Build and Run

npm install
npx prisma migrate dev --name init

This should sync the db with script

npx prisma db push
To push any futher changes

# Status

- Able to build and run, need version upgrade to Next15. Few deprecated libraries
- trpc interface is failing to establish connection with mail servers
  - Test with multiple email accounts
- WebHooks for debugging to be tested
