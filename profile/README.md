# re4

**A reactive UI framework with a custom compiler and syntax.**
Minimal. Expressive. Compiler-first.
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

### Why re4?

🧠 New mental model — no useState, no hooks

⚡ Compiled — outputs direct DOM ops or glue code

🔌 Renderer-agnostic — works with DOM, Canvas, or custom targets

✍️ .re files with TypeScript+JSX syntax

🔬 Fine-grained reactivity — built-in state, computed, and effect

🚧🚧
Under heavy development
🚧🚧
Core compiler, renderer, and tooling are being actively built.
Stay tuned — this is just the beginning.
