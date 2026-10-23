# Qeydlər – Next.js Blog (test deployment)

Next.js (App Router) + Tailwind CSS ilə hazırlanmış sadə bloq tətbiqi. Nümunə məzmun Azərbaycan dilindədir.

## Run locally

```bash
npm install
npm run dev        # http://localhost:3000
```

Production build:

```bash
npm run build
npm start
```

## Deploy to Vercel

1. Push this repo to GitHub.
2. Go to https://vercel.com/new and import the repository.
3. Keep the defaults (Framework: Next.js) and click **Deploy**.

## Structure

```
app/            routes (/, /blog/[id]), layout, global styles
components/     Header, ThemeToggle, PostCard
lib/posts.ts    sample posts + date helper
```
