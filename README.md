# FileMaker Account Management Module

This project is inspired by and derived from Darren Burgess' Accounts Module, and will generally include the same features,
but with different priorities regarding integration. Whereas Darren's module requires the addition of a few tables and layouts,
the priority of this system will be to abstract configuration as much as possible so that the implementer can use whatever
conventions work for him or her. Another way to look at it is that, as thankful as I am for Darren's contribution, and I've
used it in multiple solutions to great effect, this is the module I wish I had been given.

## Priorities

- Require as few as possible changes to an existing system's data structure for integration
- Get the module working first with a single-file solution, allowing a mutli-file solution to come later
- Allow developers to decide on whatever parameter passing scheme they prefer
- Provide scripts for account creation, deletion, enabling, disabling, password change and privilege set change
