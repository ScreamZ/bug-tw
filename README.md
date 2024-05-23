# Instructions

- run `pnpm install` to install dependencies
- go in `src/app/fr` and create a symlink of page using `ln -s ../page.tsx`. (I already created a symlink but not sure if it will remains just in case recreate it if you can't see the bug. `unlink page.tsx` to remove in fr folder)
- `pnpm dev`
- Load the page and see "hello world" in green
- Now change the color to red in `src/app/page.tsx` and save.
- Text is now blank (previous class removed, new one added but not generated.)
