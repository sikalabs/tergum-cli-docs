## tergum completion bash

generate the autocompletion script for bash

### Synopsis


Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:
$ source <(tergum completion bash)

To load completions for every new session, execute once:
Linux:
  $ tergum completion bash > /etc/bash_completion.d/tergum
MacOS:
  $ tergum completion bash > /usr/local/etc/bash_completion.d/tergum

You will need to start a new shell for this setup to take effect.
  

```
tergum completion bash
```

### Options

```
  -h, --help              help for bash
      --no-descriptions   disable completion descriptions
```

### SEE ALSO

* [tergum completion](tergum_completion.md)	 - generate the autocompletion script for the specified shell

###### Auto generated by spf13/cobra on 12-May-2025
