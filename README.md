# Awesome Resonate example apps

The following is a list of awesome example applications that showcase how special Resonate is.

## [Human approval via email](https://github.com/Tomperez98/human-in-the-loop/tree/main)

Written with the Resonate Python SDK, this is a minimal example that implements a workflow that blocks and waits on input from a human.

## [NomNomNow food delivery](https://github.com/flossypurse/nomnomnow)

Written with the Resonate Python SDK, this application showcases a multi-step order workflow that, once started, requires input from a restaurant and a driver. It also showcases Resonate's asynchronous RPC APIs across multiple services. It includes an interactive UI that updates as the order progresses.

## [Resonate is async RPC](https://github.com/flossypurse/resonate-is-async-rpc)

Written with the Resonate Python SDK, this example showcases Resonate's asynchronous RPC APIs across the services foo, bar, and baz in the context of 3 different request flows: chain, fan-out, and fire-and-forget.

## [Durable website summarization app](https://github.com/flossypurse/website-summarization-app)

Written with the Resonate Python SDK, this example integrates Flask, Resonate, BeautifulSoup, and Ollama into a website summarization application.
The workflow is durable to crash failures and can be load balanced by running multiple instances of the app.
