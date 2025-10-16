# Deploy Next.js on Seenode

This is a simple Next.js app set up to deploy on [Seenode](https://seenode.com).

It shows a basic page and lets you add API routes if you need them.

### Quick start
Read the [Seenode guide for Next.js](https://seenode.com/docs/frameworks/javascript/nextjs/).

## How to Deploy on Seenode

1. Go to the [Seenode dashboard](https://cloud.seenode.com) and create a new web service from this repo.
2. Use these commands when asked:
   - Build: `npm run build`
   - Start: `npm start`
3. Click Create. Seenode will give you a public URL when it’s live.

That's it! Your Next.js app will be deployed and available at a public URL.

### What you get

- Works out of the box on Seenode.
- No port setup needed. Port is set to 80. Just make sure to enter 80 in the port input.
- Add API routes under `app/api` if you want server endpoints.

## Getting Started (Local Development)

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Edit the homepage at `src/app/page.tsx`. Changes show up automatically while the dev server runs.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to load fonts.

## Learn more

Helpful links:

- [Next.js docs](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)
- [Seenode guide for Next.js](https://seenode.com/docs/frameworks/javascript/nextjs/)

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!
