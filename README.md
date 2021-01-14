# typedoc-bug

This is a repo which reproduces how packageDocumentation is broken in the latest version of `typedoc`.

## Setup

```bash
git clone https://github.com/amilajack/typedoc-bug
cd typedoc-bug
npm i
npx typedoc index.ts --json foo.json
# Notice how foo.json doesn't contain the @packageDocumentation comment
```
