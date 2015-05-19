# sassy-exists

`sassy-exists` is SASS micro library for existance checks. 

# Requirments 

* `gulp`
* SASS `3.4.13`

# Usage

`sassy-exists` provides alternative syntax for these functions:

* `variable-exists($name)` 
* `global-variable-exists($name)` 
* `feature-exists($name)` 
* `mixin-exists($name)` 
* `function-exists($name)` 

With `sassy-exists` it becomes:

    exists($name, $type)

`$type` values are: 

* `variable`
* `global-variable`
* `mixin`
* `function`
* `feature`