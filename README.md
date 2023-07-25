This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


## Front end start
global css: remove previous things add this
html,
body,
:root {
  height: 100%;
}

## create a folder name (routes) then create a page name page.tsx in routes folder

write page basic structure

# Now add font on layout

## Now add footer component on layout
## Create a folder name components outside the app
## Now create a footer and navbar components in components folder
## Now create a ui folder in components
# Copy lib => utils data from admin app and craete folder name lib in outside of app then ceate - util.ts
#  Command: npm i clsx tailwind-merge

## create types.ts outside the app
## create actions folder outside the app now create get-categories.tsx
## create button.tsx in components => ui folder
## command: npm i lucide-react
## create actions folder outside the app now create get-billboard.tsx
## create actions folder outside the app now create get-products.tsx
#  Command: npm i query-string