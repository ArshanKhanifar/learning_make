# Recipes
They look like this: 
```
target … : prerequisites …
        recipe
        …
        …
```
## Recipe Prefix
Instead of TABs you can change it: `.RECIPEPREFIX`. (Google it)


## Default Goal
* the fist one it finds first (not starting with '.')
* the `.DEFAULT_GOAL` special variable

## Objects

It's standard practice to keep a variable named `objects`
```
objects = main.o kbd.o command.o e
# then we can use it like this:
edit: $(objects)
  cc -o edit $(objects)
```







