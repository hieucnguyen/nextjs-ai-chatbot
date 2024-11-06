
<h1 align="center">Project: AI Chatbot</h1>

<p align="center">
  Create a simple web application that implements a chatbot interface using OpenAI's API. This project will demonstrate your ability to work with frontend, backend, and optionally an API integration. 
  The chatbot helps user advise on what book to read next.
</p>

## Running locally

0. Install necessary libraries: npm, [tsx](https://tsx.is/getting-started), docker
1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`
4. Start your local Postgres instance: `docker-compose up -d`
5. Setup the database with data: npx tsx db/migrate
6. Build project 
```bash
pnpm install
pnpm dev
```

NOTE: All credentials are included privately in the Google Drive file, not pushed to Github.

Your app template should now be running on [localhost:3000](http://localhost:3000/).
