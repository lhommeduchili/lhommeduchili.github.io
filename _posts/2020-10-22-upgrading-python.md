---
layout: post
title: blog # This is the title displayed next to 南波的博客
post_title: Upgrading python version
---

This how I currently keep myself updated in the ever growing world of Python.

To manage multiple python versions I use pyenv:
```shell
  pyenv install --list
  pyenv install VERSION
```

(e.g. `pyenv install 3.9.0`)

Then, to change the global python version use:
```shell
  pyenv global VERSION
```
 (e.g. `pyenv global 3.9.0`)


These are the libraries I normally use at the present time, and I use `pip` to manage them:

```shell
  pip install numpy matplotlib pandas
              opencv-python jupyterlab scipy
              scikit-learn scikit-image seaborn
```

---
*Note for myself:*

*If installing python for the first time, remember to add __.pyenv/bin__ directory to `$PATH` and __pyenv init__ to the shell configuration as well.*

---

## Checking compatibility with Jupyter

Now, in order to use the latest version of python's kernel in jupyter, I have to modify `alfre/Library/Jupyter/kernels/python3/kernel.json`, specifying the version of python that I'm actually using.

To check which version of python jupyter is actually using, open a console inside jupyter's environment and type:

```python
  import sys
  print(sys.version)
```

## Uninstalling old versions
```shell
  pyenv uninstall VERSION
```

(e.g. `pyenv uninstall 3.8.5`)
