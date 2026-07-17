# Contributing

Pull requests are welcome!

To begin, clone the repo, then install dependencies.

```bash
pnpm install
```

The source code is written in TypeScript. Spin up the compiler to watch for source changes:

```bash
pnpm run watch
```

Note remember to add a Changeset entry for your work before submitting a PR. (`pnpm changeset` then follow the prompts.)


## Publishing

```bash
pnpm changeset publish
```

See [Changesets Docs](https://github.com/changesets/changesets/blob/main/docs/intro-to-using-changesets.md)) for more info on how to use changesets.
