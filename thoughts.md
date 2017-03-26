# node acme

## top menu bar / commands

- build your own top menu-bar (like emacs, but much easier) of commands
- trivial to add key bindings to menu commmands
- menu commands can be specified ad-hoc, in the working dir/project, or globally
- all module based! (depject?)
- e.g. module that adds all npm scripts to the menu under 'npm'


## modules

possible to add/edit/publish editor modules right in the editor


## questions

### what is the principal integration mechanism? shell commands or node modules?

shell is really useful, but modules as first class is exciting

plus, you can wrap the shell using a module!

what if streams were also first-class citizens somehow? not even sure what this
means

### what kinds of things would I want modules to do?

- add new commands
- change text highlighting
- understand how to interpret some text -> a command
- apply different handlers to interactions with a pane

