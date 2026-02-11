# ThreeJS Diving Tutorial Sandbox

> Look, try, change, learn...

## Base Branches

This repository uses base branches as project templates. Lesson branches are created from the appropriate base.

| Branch      | Description    | Features                               |
| ----------- | -------------- | -------------------------------------- |
| `base-lite` | Minimal setup  | HTML + ES modules, no build step       |
| `base-core` | Standard setup | Bundler, npm dependencies, TypeScript  |
| `base-full` | Advanced setup | FSD architecture, tests, static assets |

## Branch Naming Convention

```
base-{level}              # Base templates: lite, core, full
lesson-{NN}-step-{NN}     # Lesson checkpoints
lesson-{NN}-final         # Completed lesson
```

## Deployment

Only `lesson-*` branches are deployed to Vercel:

- URL pattern: `https://tutorial-sandbox-git-{branch}-three-js-diving.vercel.app/`

`main` and `base-*` branches are skipped via `vercel.json` [ignoreCommand](https://vercel.com/docs/project-configuration#ignorecommand).
