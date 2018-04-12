# Universal Database Adapter

GraphQL adapter for SQL databases.

## Usage Example

```js
import express from 'express';
import dbadapter from 'dbadapter/express';

const app = express();

app.use('/db', dbadapter());

app.listen(8080);
```
