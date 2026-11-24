# Shilp

Open-source packages for building apps faster. Headless UI building blocks for React and Vue, plus extensions for [Directus](https://directus.io).

[shilp.dev](https://shilp.dev) is built and maintained by [7Span](https://7span.com). Every package is published on npm under the `@shilp.dev` scope.

## Packages

### [List](https://github.com/shilpdev/list)

Headless list components. You write the markup. Shilp handles fetching, pagination, search, filters, sorting, selection and state persistence.

| Package | Description | npm |
| --- | --- | --- |
| [`@shilp.dev/react-list`](https://github.com/shilpdev/list) | List components for React 19+ | [![npm](https://img.shields.io/npm/v/@shilp.dev/react-list.svg)](https://www.npmjs.com/package/@shilp.dev/react-list) |
| [`@shilp.dev/vue-list`](https://github.com/shilpdev/list) | List components for Vue 3.5+ | [![npm](https://img.shields.io/npm/v/@shilp.dev/vue-list.svg)](https://www.npmjs.com/package/@shilp.dev/vue-list) |

### [Form](https://github.com/shilpdev/form)

Headless CRUD form components. One form for create and edit, with values, dirty and touched tracking, validation, loading flags and errors handled for you. Works with any schema library and any backend.

| Package | Description | npm |
| --- | --- | --- |
| [`@shilp.dev/react-form`](https://github.com/shilpdev/form) | Form components for React 19+ | [![npm](https://img.shields.io/npm/v/@shilp.dev/react-form.svg)](https://www.npmjs.com/package/@shilp.dev/react-form) |
| [`@shilp.dev/vue-form`](https://github.com/shilpdev/form) | Form components for Vue 3.5+ | [![npm](https://img.shields.io/npm/v/@shilp.dev/vue-form.svg)](https://www.npmjs.com/package/@shilp.dev/vue-form) |

The React and Vue packages share the same API: learn it once, use it in either framework.

### [Directus Extensions](https://github.com/shilpdev/directus-extensions)

Extensions for Directus 11 and newer.

| Package | Description | npm |
| --- | --- | --- |
| [`@shilp.dev/directus-google-auth`](https://github.com/shilpdev/directus-extensions/tree/main/packages/google-auth) | "Login with Google" for custom frontends. Signs users in (and registers them on first login) as regular Directus users, with session cookie or JWT modes. | [![npm](https://img.shields.io/npm/v/@shilp.dev/directus-google-auth.svg)](https://www.npmjs.com/package/@shilp.dev/directus-google-auth) |
| [`@shilp.dev/directus-ai-content-generator`](https://github.com/shilpdev/directus-extensions/tree/main/packages/ai-content-generator) | Flow operation that generates content (descriptions, summaries, copy) with Claude or Gemini from a prompt and a set of variables. | [![npm](https://img.shields.io/npm/v/@shilp.dev/directus-ai-content-generator.svg)](https://www.npmjs.com/package/@shilp.dev/directus-ai-content-generator) |
| [`@shilp.dev/directus-counter`](https://github.com/shilpdev/directus-extensions/tree/main/packages/counter) | Endpoint that atomically increments a numeric field (views, plays, downloads) of any item, found by its id or any other field such as a slug. | [![npm](https://img.shields.io/npm/v/@shilp.dev/directus-counter.svg)](https://www.npmjs.com/package/@shilp.dev/directus-counter) |

## Contributing

Issues and pull requests are welcome on every repository. Each one has its own README with setup and development notes.
