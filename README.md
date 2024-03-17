# NextJS + Tailwind Boilerplate

### Packages installed

1. tailwindcss
2. tailwindcss-animate (plugin that adds basic animation classes)
3. eslint
4. prettier
5. husky (for running commands on git hooks such as pre-commit, pre-push)
6. lint-staged (to run the pre-commit command)
7. cal-sans (the default font for headings)

### Package Manager

- yarn v4

### Theme

Default theme is set to dark - Check the html tag in `@/src/app/layout.tsx`, if the className is dark, dark mode css variables are used

CSS variables are to be set it `@/src/app/global.css`

The following variables have been set by default for both `light` and `dark` mode

1. `foreground`
2. `background`

### Typography

Default font for heading is `Cal Sans` installed as a package

Default font for body text is `Plus Jakarta Sans`, imported from Google Fonts using `next/font/google`

=================================================================

## NextJS Readme

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Jakarta Sans, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
