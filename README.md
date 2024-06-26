# Code Connect Demo

Barebones React demo of Figma's [Code Connect](https://github.com/figma/code-connect).

## Codebase setup

- `npm i` to install dependencies
- `npm run app:dev` will run server at [localhost:8000](http://localhost:8000) which renders contents of [App.tsx](src/App.tsx).
- Optional: Using `npm run figma:connect:*` commands (described in [package.json](package.json))
  - Only if you don't want to paste your tokens / don't have another setup
  - Duplicate [secrets.example.env](secrets.example.env) as `secrets.env`
  - Set `FIGMA_ACCESS_TOKEN` in `secrets.env` as your Figma API token with Code Connect scope

## Figma file and Code Connect prep

- Duplicate [this file](https://www.figma.com/community/file/1367910052286562243) and get the file key from the duplicated file url.
- In this repository, find all `SS2xN8AagXT0ofpo8PNIp9` and replace with the new file's file key.
