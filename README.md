# nvim
My neovim configs

# Quickstart
1. remove nvim-data
2. PylspInstall pylsp-mypy (a file must be opened beforehand (because the lsp stuffs are lazy)
3. In mason install debugpy

before running neovim in a python project, set the python env to shell,
for example in a pixi controlled project, run `pixi s -e <env>`,
and in a conda project, run `conda activate <env>`

# Debugging
pixi r -e dev debug (or other debug commands)
Pour lancer le debug il faut etre dans un fichier python -> F5 et enter enter (defaults)
F5 -> continiue
F10 -> next line
F11 -> step into
F12 -> step out

# Quick fix list
For creating one from telescope -> `C-q`
:cnext
:cprev
:cclose
`:cdo s/Foo/Bar/gc` -> replace Foo with Bar in all files in the quickfix list
`:cfdo @a` -> run macro a on all files in the quickfix list

