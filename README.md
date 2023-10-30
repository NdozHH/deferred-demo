# Examples of slow request handling in Remix

This repo features 4 different ways of handling slow routes in remix:

1. [Prefecth - 01-prefetch](https://github.com/remixcph/deferred-demo/compare/main...01-prefetch)
2. [useTransition - 02-use-transition](https://github.com/remixcph/deferred-demo/compare/main...02-use-transition)
3. [useEffect + useFetcher - 03-use-effect](https://github.com/remixcph/deferred-demo/compare/main...03-use-effect)
4. [Deferred - 04-deferred](https://github.com/remixcph/deferred-demo/compare/main...04-deferred)

In the main branch the initial slow request is just left as is.
The slow route is on http://localhost:300/notes/koala

Each approach to improving the user experience is implemented in a branch.

## Development

- Run setup script

  ```sh
  npm run setup
  ```

- Start dev server:

  ```sh
  npm run dev
  ```

This starts your app in development mode, rebuilding assets on file changes.

The database seed script creates a new user with some data you can use to get started:

- Email: `rachel@remix.run`
- Password: `racheliscool`

This repo is based on the [Remix Indie Stack](https://github.com/remix-run/indie-stack)

