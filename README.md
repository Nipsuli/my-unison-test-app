# My Unison Test App

Just playing around with [The Unison language](https://github.com/unisonweb/unison)

Trying to build simple HTTP server.

## How to run unison

### Install

```
brew tap unisonweb/unison
brew install unison-language
```

In project folder run `ucm`

To install base library
`pull https://github.com/unisonweb/base .base`

basically installing packages is done with pull

More info in [quick start](https://www.unisonweb.org/docs/tour/hello-ucm/)

Unison watches all `*.u` files

In `ucm` use `view [definition]` such as `view base.Test.Result` to see definition

Check also [Unison Codebase Explorer](https://github.com/unisonweb/elm-browser)
