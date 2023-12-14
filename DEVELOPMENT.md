Workspace setup
---------------

* To reduce pain, set up [rbenv] to manage your Ruby versions.
Install one that's known to work:

      make ruby

    * Otherwise, make sure you have Ruby and [Bundler] set up.

* Install dependencies:

      make deps

* Make sure builds are working:

      make build

[rbenv]: https://github.com/rbenv/rbenv
[Bundler]: https://bundler.io/

Development
-----------

* Build the website and serve it at http://localhost:4000/:

      make serve

    * It will pick up changes and reload pages automatically.

Upgrading dependencies
----------------------

    bundle update
