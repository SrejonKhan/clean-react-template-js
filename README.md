# clean-react-template-js

This is a simple straight forward React starter project with bare minimum setup using ESLint, Prettier and Parcel. 

## Commands
Dev Build: `npm run dev`

Prod Build: `npm run build`

Check if formatted (using prettier): `npm run format:check` 

Lint (using ESLint): `npm run lint`

## How to use with Tailwind?
1. Create a new repo from this template with selecting **Include all branches**. Follow [this (step 6)](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) tutorial for step by step guide.  
2. Clone your repo to local machine and open git bash there.
3. Checkout to `tailwindcss` branch - `git checkout tailwindcss`.
4. Delete local main branch - `git branch -D main`.
5. Rename `tailwindcss` branch to `main` - `git branch -M main`.
6. Push forcefully to origin - `git push origin main -f`.
7. Delete remote `tailwindcss` branch - `git push -d origin tailwindcss`.