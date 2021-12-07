# dotfiles
Useful configuration files while working on projects

Make sure to install the following applications before proceed:
* [Direnv](https://direnv.net/)


For Direnv
```bash
# Make sure to have ~/.config
# Copy the contents of direnv/direnvrc to  ~/.config/direnv/direnvrc
cp -r direnv/direnvrc ~/.config/direnv/direnvrc
```

For auto-loading of python environments, add the following lines to the environment file(.envrc) of each project.
```bash
export VIRTUAL_ENV=.venv
layout python-venv
```
