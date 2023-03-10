This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
pnpm dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in a browser to see it in action.

You can start editing by modifying `app/page.tsx`. Your browser will auto-update as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Beta Documentation](https://beta.nextjs.org/docs) - incomplete documentation focused on the new structure introduced in Next.js 13
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - feedback and contributions are welcome.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Code Commits

### Committing Code

This repository uses [commitizen](https://www.npmjs.com/package/commitizen) to help enforce rules and simplify the commit process. To commit any staged files, simply run `npm run commit` and follow the on-screen prompts.

### Commit Messages

Commit messages in this project follow a strict standard using commitlint and enforced by a husky hook. Commits must follow a format of:

```
type(scope?): subject(#issue number?)
body
footer?
```

for example:

```
feat: install commitlint and husky(#41)

- installs commitlint
- installs husky
- adds commitlint config file based on @commitlint/config-conventional
- adds husky pre-commit hook to lint commit messages
```

- [what is commitlint](https://github.com/conventional-changelog/commitlint/#what-is-commitlint)
- [commitlint rules reference](https://commitlint.js.org/#/reference-rules)
- [@commitlint/config-conventional rules](https://github.com/conventional-changelog/commitlint/tree/master/@commitlint/config-conventional)

## Commit with a GUI

Out of the box, the husky pre-commit hooks configured in this project will prevent you from committing code using a GUI like [Tower](https://www.git-tower.com/). Don't fret, it's possible to get this working with very little overhead.

- [Description of the issue](https://www.git-tower.com/help/guides/integration/environment/mac)
- [Example fix with Tower](https://www.git-tower.com/blog/git-hooks-husky/)
