This repository hosts generated docs for packages using [QilletniDocgen](https://github.com/Qilletni/QilletniDocgen) under the `qilletni` scope. The `serve/` directory is hosted on Cloudflare Pages at [https://docs.qilletni.dev/](https://docs.qilletni.dev/) 

Documentation is generated either by a manual trigger or from a repository dispatch event. This pulls down the latest version of the specified package from [QPM](https://github.com/Qilletni/qpm-backend), extracts it, and generates documentation using `qilletni doc`.
