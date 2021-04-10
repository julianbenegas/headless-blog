# next-typescript

The objective of this boilerplate is to set up everything the developer will need (in terms of configuration) to start a next + typescript project. Eslint, prettier and husky are configured to work independent of the user's IDE configuration (as long as it's vscode).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fbasementstudio%2Fnext-typescript)

## Featured aspects of the stack

- Typescript
- NextJS
- TailwindCSS
- next-themes

## Things to note

- It comes with Inter (it's better to host fonts here rather than getting them from google fonts). Remove it if you are not going to use it.
- Pages, components, etc... are located under `/src`. If you are changing this, be sure to also update `tsconfig.json`'s `baseUrl`.
- If you are **not** using Tailwind, you can remove `postcss.config.js` and `tailwind.config.js`.
- It comes with `next-themes`, so dark mode ready. If you're not using it, just remove the library.

---

If you found you needed to make extra config to make this work better, feel free to submit a pr suggesting your changes. Our focus is for you to get up and running with the least steps and burden as possible.

---

Let's go 🚀
