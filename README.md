# Body Meta

Lets store data in description fields. Because we don't have a better place to
put them.

```json
{
	"body": "Big description of\nsomething",
	"string": "data",
	"number": 123
}
```

Becomes:

```text
Big description of
something

string: "data"
number: 123
```

## Methods

### `encode`

Encodes an Object into a single string placing the `body` value on top

### `decode`

Decodes a string into a single Object

## License

Copyright (c) 2026, Marcline Szmadzinski. (MIT License)
