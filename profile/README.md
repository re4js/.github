# Re4


Minimal. Expressive. Compiler-first Javascript Framework
[docs](https://www.re4js.dev/)

```tsx
// counter.re
import { render } from "@re4/dom"

function hello() {
  console.log("Welcome re4!")
}

component Counter {
  state count: number = 0

  hello()

  return (
    <button onClick={() => count++}>
      Clicked {count}
    </button>
  )
}

render(Counter, document.getElementById("#app"))
```

🚧🚧WIP🚧🚧
Core compiler, renderer, and tooling are being actively built.
Stay tuned - this is just the beginning.
