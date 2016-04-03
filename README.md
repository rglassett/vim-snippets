# snipMate Snippets

This repository contains my personal snippets files for various programming
languages. It was originally forked from
[honza/vim-snippets](https://github.com/honza/vim-snippets).

## Guidelines

Following are some guidelines from the original snippets repository. I think
they make sense, and am keeping them here for my own personal reference.

Useful snippets to have in every language:

```
if  : if without else
ife : if $1 else $2
eif : else if ($1) { .. }
el  : else ..
wh  : while (cond) ...
```

Avoid useless placeholders in conditions and block bodies:

```
# bad
if (${1:condition}){
  ${2:some code here}
}

# good
if (${1}){
  ${2}
}
```
