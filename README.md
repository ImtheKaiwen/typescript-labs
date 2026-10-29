# TypeScript Labs

A small collection of standalone TypeScript examples created while studying the language. Each file focuses on one topic and can be explored independently.

## Examples

| File | Topics |
| --- | --- |
| [`type.ts`](type.ts) | Aliases, object types, unions, literals, and intersections |
| [`enum.ts`](enum.ts) | Numeric, string, and const enums |
| [`generic-types.ts`](generic-types.ts) | Generic functions, interfaces, constraints, and classes |
| [`utility-types.ts`](utility-types.ts) | `Partial`, `Pick`, and `Omit` |
| [`oop.ts`](oop.ts) | Classes, access modifiers, inheritance, and abstract classes |
| [`promise.ts`](promise.ts) | Promises, async/await, typed responses, and `fetch` |
| [`type-assertion.ts`](type-assertion.ts) | DOM type assertions |

## Run an example

Node.js and npm are required. Run a Node-compatible example with `tsx`:

```bash
npx tsx enum.ts
```

To rerun a file when it changes:

```bash
npx nodemon --exec npx tsx enum.ts
```

`npx` may download the requested tool when it is not already available locally.

## Notes

- The files are independent learning snippets, not a single application.
- `type-assertion.ts` expects a browser DOM containing an element with the ID `user-email`.
- `promise.ts` includes an example that makes a request to an external API; review the endpoint before running it.
- There is no project-level package manifest or automated test suite.
