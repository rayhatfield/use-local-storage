# @raytheist/use-local-storage

> A React hook that works like useState but persists via localStorage

[![NPM](https://img.shields.io/npm/v/@raytheist/use-local-storage.svg)](https://www.npmjs.com/package/@raytheist/use-local-storage) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @raytheist/use-local-storage
```

## Usage

```jsx
import React, { Component } from 'react'

import { useMyHook } from '@raytheist/use-local-storage'

const Example = () => {
  const example = useMyHook()
  return (
    <div>{example}</div>
  )
}
```

## License

MIT © [rayhatfield](https://github.com/rayhatfield)

---

This hook is created using [create-react-hook](https://github.com/hermanya/create-react-hook).
