Qwik lib starter using [pnpm workspaces monorepo](https://pnpm.io/workspaces) 

Lib is at packages/component-lib and is the `npm create qwik@latest` component lib starter as of 2023-06-06

App is at packages/qwik-app and is the `npm create qwik@latest` basic app starter as of 2023-06-06

1. [Install pnpm](https://pnpm.io/installation)
1. `pnpm install`
1. `cd packages/component-lib`
1. `pnpm build`
1. `cd ../qwik-app`
1. `pnpm dev`
2. `localhost:5173` and see QWIK LIBRARY LOGO and QWIK LIBRARY COUNTER in the "You can count on me" section

Will need to redo the lib build or setup scripts/watchers in order to see changes. Alternatively for the best monorepo experience use https://github.com/qwikifiers/qwik-nx