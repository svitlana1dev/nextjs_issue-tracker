Next.js application with TypeScript [VIEW DEMO](https://nextjs-issue-tracker-akml.vercel.app/)

#### Getting Started

1. Create .env file

```

DATABASE_URL=your_db_url
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET= Run 'openssl rand -base64 32' to generate a secret
GITHUB_CLIENT_ID= generate your Github Client ID
GITHUB_CLIENT_SECRET= generate your Github Client ID

```

2. Run `npm install`
3. Use `docker-compose up` to run a database and run `db:migration:dev`
4. Run `npm run dev`
