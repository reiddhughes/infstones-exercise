# infstones-exercise
Exercise for interview at Infstones

This environment assumes that you have poetry, pyenv, and task installed.

You can setup the python dependencies with `task install`.

You can run the forever script in the background with `./forever 100 &` or any other argument.
You can run the monitory script in the background with `poetry run ./monitory forever &`.
The command uses poetry to run it becasue it needs the installed psutil dependency.

You can test it by adding more forever commands and stopping the process of existing forever commands.
