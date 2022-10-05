
# Contributing to Buffalo

First, thank you so much for wanting to contribute! It means so much that you
care enough to want to contribute. We appreciate every PR from the smallest of
typos to the be biggest of features.


## First time committing to the Buffalo projects?

Support for go Modules was introduced in
[Release v0.13.0-beta.1](https://github.com/gobuffalo/buffalo/releases/tag/v0.13.0-beta.1)
(September 2018), and you can now use them to easily set up a development
environment. The steps involve:

1. Fork the repo
2. Clone the repo to any location in your work station
3. Read the contribution guideline below

Note: Please check the current supported Go version. By default, we support
the last two version of the officially released Go versions.


## How to contribute

1. Check Issues of the module (e.g.
   [https://github.com/gobuffalo/buffalo/issues](https://github.com/gobuffalo/buffalo/issues))
   to make sure you're not working on a duplicate issue or PR.
2. If you want to implement a new feature that doesn't have an issue open,
   please open one and ask for feedback on the feature before spending a lot
   of time working on it. It's possible the feature has already been discussed,
   or it's out of scope, or some other reason that might later prevent a PR
   from being accepted.
   The [#buffalo](https://gophers.slack.com/messages/buffalo/) channel on
   gophers.slack.com is a great place to seek this kind of guidance.
3. Write your feature/fix and make sure to include tests. Tests are an
   **absolute** requirement for any pull request. Please make sure to use the
   same testing style and libraries as the rest of the tests.
4. Make sure tests run when doing `go test -race ./...`.
5. (Optional) There is a much longer set of integration tests that can be run.
   These will be run by github actions when you open a PR. If you want to run
   them locally, you can by running `docker build .`.

Feel free to ask for help, but don't target a specific person (unless you're
replying to this person). @ gobuffalo/core-managers instead.

### Making your Pull Request

Open a PR against the `main` branch if your PR is for mainstream, otherwise you
can open a PR against version maintenance branch (e.g. `v1`) if your PR is a
hotfix for an old version in maintenance mode.
(Note that the valid branch for a new feature request PR should be `main` while
a PR against a version specific branch are allowed only for hotfixes.)


## Documentation Welcome

Hands down the most important and the most welcome pull requests are for
documentation. We LOVE documentation PRs, and so do all those that come after
you.

Whether it's GoDoc or prose on [http://gobuffalo.io](http://gobuffalo.io) all
documentation is welcome.

You can submit PRs to change the website and/or docs on
[https://github.com/gobuffalo/docs](https://github.com/gobuffalo/docs).


## Thank You

Once again, we want to take the chance to say thank you for wanting to
contribute to Buffalo. This is a community project, and that means we **need**
your help! Thank you so much.
