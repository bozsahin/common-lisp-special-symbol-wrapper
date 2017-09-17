# common-lisp-special-symbol-wrapper

This repo is a <code>bash</code> script based on <code>sed</code>, to wrap
all special symbols in <code>|..|</code> so that Lisp reader can recognize them as data.

Then the result is wrapped in <code>(..)</code> so that the Lisp reader can read it in one fell swoop.

