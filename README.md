###Configuration
There are three levels of config: local(this repo), global(all repos for the user) and system(all the users).

Check your configs:
`git config --global --list`

Set your configs:
`git config --global <name> <value>`

If I want you to use awesome VIM instead of boring nano I could use:
`git config --system core.editor vim`
