# Template - Vite + TailwindCSS (TypeScript)

Prettier + ESLint are included in this template.

## Initialization

1. Create a new empty repository on GitHub.
2. Clone the template repository on your local machine using the command `git clone <template_repo_url>`.
3. Remove the existing remote repository named 'origin' using the command `git remote rm origin`.
4. Add your newly created repository as the 'origin' remote using the command `git remote add origin git@github.com:user/repo.git`.
5. Run `npm install` to install the necessary dependencies.

Note: you can run `git remote -v` to list the configured remote repositories and verify that the 'origin' remote points to your new repository.

## Scripts

- `npm run dev` - starts a local development server with hot-reloading.
- `npm run build` - compiles the project and output in the /dist folder.
- `npm run pages` - deploys the content of the /dist folder to GitHub Pages.
- `npm run prettier <file>` - formats the file according to the rules set in .prettierrc.json.
- `npm run prettier:all` - formats all the files according to the rules set in .prettierrc.json.
- `npm run prettier:check` - checks if all the files are respecting the rules set in .prettierrc.json.

Note: The script npm run prettier should be followed by the file name you want to format, otherwise it won't work.

## Documentation

- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Prettier](https://prettier.io/)
- [ESLint](https://eslint.org/)
