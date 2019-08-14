> Written with [StackEdit](https://stackedit.io/).

# Some notes about using `.gitignore`

`.gitignore`

This tells git which files to ignore. This should be setup as first priority in a new project because once you commit something stupid, it’s there forever unless you take special action.

It’s most important to exclude sensitive information, like passwords and API keys. If you commit a file containing sensitive information early on, this quickly becomes a nightmare. Deleting it from the current snapshot is not enough–you need to eliminate it from all previous commits. Do yourself a favor and just avoid having to learn how to do that.

The next step is to ignore very large data files and unimportant files that do not need to be tracked (i.e. ipython notebook checkpoints, settings files from your IDE, __pycache__, .pyc, etc). In the example above, all the input/output artifacts should be ignored too since they are fully determined from the code itself and can be regenerated if needed.

[Source](https://towardsdatascience.com/implementing-git-in-data-science-11528f0fb4a7)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMTg0NDc3OTJdfQ==
-->