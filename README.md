
<h1 align="center">Project: AI Chatbot</h1>

<p align="center">
  Create a simple web application that implements a chatbot interface using OpenAI's API. This project will demonstrate your ability to work with frontend, backend, and optionally an API integration. 
  The chatbot helps user advise on what book to read next.
</p>

## Running locally

You will need to use the environment variables [defined in `.env.example`](.env.example) to run Next.js AI Chatbot. It's recommended you use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables) for this, but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

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

Your app template should now be running on [localhost:3000](http://localhost:3000/).
