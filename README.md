[![Build Status](https://travis-ci.org/nrepl/nREPL.svg?branch=master)](https://travis-ci.org/nrepl/nREPL)
[![Clojars Project](https://img.shields.io/clojars/v/nrepl.svg)](https://clojars.org/nrepl)

# nREPL

nREPL is a Clojure *n*etwork REPL that
provides a REPL server and client, along with some common APIs
of use to IDEs and other tools that may need to evaluate Clojure
code in remote environments.

### How is this different from the "contrib" [tools.nrepl](https://github.com/clojure/tools.nrepl/) project?

Check the brief history of nREPL, available
[here](https://nrepl.readthedocs.io/en/latest/about/history/).

### Status

Extremely stable.

* `[nrepl "0.3.1"]` is a drop-in replacement for
  `[org.clojure/tools.nrepl "0.2.13"]`.
* `[nrepl "0.4.0"]` changes the namespaces from `clojure.tools.nrepl.*` to
`nrepl.*`.
* A later `1.0.0` release will include fixes for all previously-reported but
  languishing nREPL issues.
* Future releases will focus on supporting the needs of the essential tools of
  the Clojure[Script] ecosystem, e.g. Leiningen, CIDER, boot, Cursive, and so
  on.

## Usage

See the [manual](https://nrepl.readthedocs.io).

## License

Copyright © 2010 - 2018 Chas Emerick, Bozhidar Batsov and contributors.

Licensed under the EPL. (See the file epl.html.)
