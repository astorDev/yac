---
type: article
status: draft
---

## CLI

Beyond, being VS Code HttpYac also can be used as a CLI-tool. The installation is based on the `npm`:

```sh
npm install --global httpyac
```

After the CLI-tool is installed we'll be able to send requests 

> Since the CLI-tool has no access to VS Code settings we'll need to set `Content-Type` header in `.httpyac.json`

```sh
httpyac send spacex.http
```

| Output    | Gives You                        |
|-----------|----------------------------------|
| short     | Method, Url -> Status, Elapsed   |
| body      | Just Response Body               |
| headers   | Request and Response Headers     |
| response  | Response Headers and Body        |
| exchange  | All Headers and Body             |
| none      | Just how many requests processed |