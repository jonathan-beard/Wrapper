# Wrapper

Super simple OS X automator workflow to take text from 
selection, cut down to the specified number of columns
of characters and pass it to the clipboard. Initial 
use case was simply cutting and pasting from PDF's and 
Word documents and wanting text that had carriage 
returns. 

The only real option, outside of registering it with
your system (Open the workflow on OS X and hit save)
is the environment parameter:

```bash
export RECLINEWIDTH=<XXX>
```

which sets the number of columns per line without
having to change the automator script over and over.
You might also want to set a quick key via System
Preferneces -> Keyboard -> Shorcuts.

Enjoy!
