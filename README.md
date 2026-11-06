# sumimi-dev.github.io

The documentation site: **<https://sumimi-dev.github.io>**

**The source is [`sumimi-dev/sumimi`](https://github.com/sumimi-dev/sumimi), the
`service/docs/` directory.** This repository does not hold the pages — it publishes
them: the workflow checks the source repository out and deploys the directory, so
there is one copy of every page, not two.

The same pages are served by the server itself at `/docs`, from the same files, so a
self-hosted instance and the public site never disagree.

To change a page, edit it in `sumimi-dev/sumimi` and open a pull request there.
