# learnantlr

A Clojure library designed to ... well, that part is up to you.

## Usage
Add [clj-antlr "0.2.4"]
lein repl

In REPL, type: (require ['clj-antlr.core :as 'antlr])

then, type: (def json (antlr/parser "grammars/Json.g4"))

then, type: (pprint (json "[1,2,3]"))




FIXME

## License

Copyright © 2017 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
