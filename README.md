# General
This cash system is a simple log of stock withdrawal. Each user is given
their own user account, which is managed on a trust basis. The admin of the
system can add users individually and assign them an avatar.

Credentials for the administrator account are stored in `config.py`.
If this file is not available `config.py.example` is read instead.
A Makefile is available for installation and operation.

# Running
`make install` installs all dependencies into a virtual environment.

`make run` then executes the system.
