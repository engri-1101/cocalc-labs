# ENGRI 1101 Labs on CoCalc

This repository contains lab examples for [ENGRI 1101: Data Science and Decision Making: An Elementary Introduction to Modeling and Optimization](https://engri-1101.github.io/textbook/cover.html).

It's layout is suitable for [repo2docker](https://repo2docker.readthedocs.io/) and used to create a custom software environment on [CoCalc](https://cocalc.com).


## Usage

* CoCalc:
  1. Create a new project and enter your license
  2. Click on "Customize software environment" → select "Custom" → and pick "Data Science and Decision Making (ENGRI 1101)"
  3. This will then use exactly this software environment and copies these files over into your project to work with. Changes are saved persistently.
* Mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/engri-1101/cocalc-labs.git/HEAD)

## Testing

Notebooks should execute.

## Building

This is how this is intended to be built.
If this works, it should work on CoCalc.
Besides this, an "appendix" installs a few additional tools, that's all.

```
repo2docker --no-run --user-id 2001 --user-name user --image-name "engri-1101" "https://github.com/engri-1101/cocalc-labs.git"
```


