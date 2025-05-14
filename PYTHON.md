## Python examples apps

The following is a list of example apps written primarily in Python and uses Resonate's Python SDK.

### [Async RPC](https://github.com/resonatehq/example-async-rpc-py)

Written with the Resonate Python SDK, this example showcases Resonate's asynchronous RPC APIs across multiple services in the context of 3 different request flows: Await Chain, Detached Chain, and a Fan-out Workflow.

### [Human-In-The-Loop](https://github.com/resonatehq/example-human-in-the-loop)

Written with the Resonate Python SDK, this is a minimal example that implements a workflow which blocks indefinitely, waiting on input from a human.

### [Batch record deletion with RedPanda](https://github.com/resonatehq/example-batch-record-deletion-py)

This is an example app showcasing what a RedPanda + Resonate pipeline might look like in the context of a "batch record deletion" use case.

### [NomNomNow food delivery](https://github.com/flossypurse/nomnomnow)

Written with the Resonate Python SDK, this application showcases a multi-step order workflow that, once started, requires input from a restaurant and a driver. It also showcases Resonate's asynchronous RPC APIs across multiple services. It includes an interactive UI that updates as the order progresses.

### [Durable website summarization app](https://github.com/resonatehq/example-website-summarization-app)

Written with the Resonate Python SDK, this example integrates Flask, Resonate, BeautifulSoup, and Ollama into a website summarization application.
The workflow is durable to crash failures and can be load balanced by running multiple instances of the app.

### [Basic webservers](https://github.com/resonatehq/example-webservers-py)

Written with the Resonate Python SDK, this example repository showcases how to integrate Resonate into the popular webserver frameworks:

- Django
- Flask
- FastAPI

### [Resonator | Distributed calculator](https://github.com/dfarr/resonator)

Written with the Resonate Python SDK, Resonator is a distributed calculator that can calculate basic arithmetic expressions that contain numbers and the symbols `( ) + - *`

### [Function-As-A-Service (FaaS) infra example](https://github.com/avillega/resonate-faas-demo)

Written with the Resonate Python SDK, this example showcases Resonate's ability to facilitate the creation of FaaS infrastructure.
