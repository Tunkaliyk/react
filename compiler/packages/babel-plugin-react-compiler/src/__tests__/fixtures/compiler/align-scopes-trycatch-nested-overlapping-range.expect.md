
## Input

```javascript
import { CONST_TRUE, makeObject_Primitives } from "shared-runtime";

function Foo() {
  try {
    let thing = null;
    if (cond) {
      thing = makeObject_Primitives();
    }
    if (CONST_TRUE) {
      mutate(thing);
    }
  } catch {}
}

export const FIXTURE_ENTRYPOINT = {
  fn: Foo,
  params: [{}],
};

```

## Code

```javascript
import { CONST_TRUE, makeObject_Primitives } from "shared-runtime";

function Foo() {
  try {
    let thing = null;
    if (cond) {
      thing = makeObject_Primitives();
    }
    if (CONST_TRUE) {
      mutate(thing);
    }
  } catch {}
}

export const FIXTURE_ENTRYPOINT = {
  fn: Foo,
  params: [{}],
};

```
      
### Eval output
(kind: ok) 