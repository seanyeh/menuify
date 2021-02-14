# Menuify

Menuify is a tool allows you to create interactive text based menus.
(Work in progress)

## Examples

### Populate command prompt with a recent command (zsh)
```
print -z $(fc -ln -10 | menuify)
```

### Interactive git add with unstaged files as menu options
```
git diff --name-only | menuify --multi | xargs git add
```
