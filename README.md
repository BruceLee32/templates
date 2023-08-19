# templates
.zshrc alias:

```
# LaTex aliases 
alias o='nvim template.tex'
alias m='nvim master.tex'
alias s='cp ../template.tex ../preamble.tex ../macros.tex .'
alias config='nvim ~/.config/nvim/init.vim'
alias snippets=' nvim ~/.config/nvim/UltiSnips/tex.snippets'

# Test 
alias testPackage="cp -R ~/templates/test/master .; cp -R ~/templates/test/preamble .; mkdir figures"

# Challenge Problems
alias challengePackage="cp -R ~/templates/challenge/master .; cp -R ~/templates/challenge/preamble .; cp -R ~/templates/challenge/problems .; cp -R ~/templates/challenge/solutions .; mkdir figures"

# Notes
alias notesPackage="cp -R ~/templates/notes/master .; cp -R ~/templates/notes/unit1 .; mkdir figures; cp -R ~/templates/notes/preamble ."
alias notesFolder="cp -R ~/templates/notes/folder ."
alias notesFile="cp ~/templates/notes/folder/file.tex ."

alias notes2Package="cp -R ~/templates/notes2/master .; mkdir figures;"

# Tufte Style
alias tuftePackage="cp -R ~/templates/tufte/master .; cp -R ~/templates/tufte/preamble .; mkdir figures; cp -R ~/templates/tufte/chapter1 ."
alias tufteFolder="cp -R ~/templates/tufte/folder ."
```
