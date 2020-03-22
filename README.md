# @raytheist/use-local-storage

> A React hook that works like useState but persists via localStorage

## Install

```bash
npm install --save @raytheist/use-local-storage
```

## Usage

```jsx
import React, { Component } from 'react'

import useLocalStorage from '@raytheist/use-local-storage'

const Example = () => {
  const [value, setValue] = useLocalStorage('storage-key', 0);
  
  return (
      <button onClick={() => setValue(value + 1)}>{value}</button>
  )
}
```

## License

MIT © [rayhatfield](https://github.com/rayhatfield)
