# pg-error-codes-ts

* **pg-error-codes-ts** is a enum of all error codes

## Documentation

Usage
```ts
import {PG_ERROR} from 'pg-error-codes-ts/lib';

try {
    await repo.findOne('wrong_id');
} catch (e) {
    if (e.code == PG_ERROR.SOME_ERROR) // ... //
}
 
```
