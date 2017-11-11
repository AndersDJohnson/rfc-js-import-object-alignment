# rfc-js-import-object-alignment

Normalize syntax for aliasing imports with the field renaming feature of object destructuring.

```js
import { Foo: MyFoo } from './foo'
```

equivalent to:

```js
import { Foo as MyFoo } from './foo'
```
