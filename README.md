# Static File Serving wrapped in Deno Permissions

As deno provides a permission setup that allows reducing the security footprint of a started application, this repo makes use of it, wrapping the npm:http-server project.

This allows us to securely provide static files from our local machine with reduced risk of enabling access to private files and documents.

## Usage

```bash
deno task start
```
