-include not_existing_file.mk
include a.mk

.phony main:

a="some_other_string"

main:
	echo ${arshan} # this will print the entire variable
	@echo
	echo $(arshan) # this will also do the same thing
	@echo
	echo $arshan # this won't expand the variable, only the fist char
	@echo
	echo "$arshan" # this works the same
	@echo
	echo "$(arshan)" # same as without quotes
	@echo
	echo "${arshan}" # same as without quotes

