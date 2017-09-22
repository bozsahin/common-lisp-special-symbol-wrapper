# common-lisp-special-symbol-wrapper

This repo is a <code>bash</code> script based on <code>sed</code>, to wrap
all special symbols in <code>|..|</code>. Now the Lisp reader can recognize them as data.

Then the result is wrapped in <code>(..)</code> so that the Lisp reader can read the whole thing in one fell swoop.

Reads from a file/standard input and writes to standard output.
