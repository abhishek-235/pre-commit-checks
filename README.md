# pre-commit checks

Prerequisite: pre-commit must be installed.

#### Install pre-commit if not installed
>$ pip install pre-commit


#### Check pre-commit version
> $ pre-commit --version

If you unable to check version from above command, you can try this one(on ububtu):
> $ ~/.local/bin/pre-commit --version

#### Set alias
````
$ vi ~/.bashrc
alias pre-commit=~/.local/bin/pre-commit
````

## Project setup
Create __`.pre-commit-config.yaml`__ in root directory of project and run *__`pre-commit install`__*

To run pre-commit checks manually, you can run following command.
`$ pre-commit run -a`

Note: It will not execute pre-commit check on untracked files.




