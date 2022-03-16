# LumiSpy demos

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/lumispy/lumispy-demos/master)
[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](https://nbviewer.org/github/lumispy/lumispy-demos/tree/master/)

<img src="https://github.com/LumiSpy/lumispy/raw/main/doc/_static/logo_rec_april21.svg" width="300" alt="LumiSpy">

## Introduction

This repository contains [Jupyter Notebooks](http://jupyter.org/) to demonstrate and learn
how to process multi-dimensional luminescence spectroscopy data with
[LumiSpy](https://lumispy.org). For learning purposes, refer also to the
[HyperSpy User Guide](http://hyperspy.org/hyperspy-doc/current/index.html), as LumiSpy
extends [HyperSpy](https://hyperspy.org) by signal types specifically for luminescence
spectroscopy.


## Visualising and running the demos.

### (Interactive) Running the demos online

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/lumispy/lumispy-demos/master)

Follow [this link](https://mybinder.org/v2/gh/lumispy/lumispy-demos/master)
or click the "launch binder" banner above to run the the demos on 
[mybinder.org](https://mybinder.org/). The demos will run remotely, 
and one can experiment with LumiSpy in a Jupyter notebook with no need 
to install or configure any software locally.

**Note:** depending on the remote server load, the interactive binder demo may 
take up to several minutes to load. For a quicker (but non-interactive) 
visualization, see below.

### (Non-interactive) Visualizing the demos online

[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](https://nbviewer.org/github/lumispy/lumispy-demos/tree/master/)

Follow [this link](https://nbviewer.org/github/lumispy/lumispy-demos/tree/master/) 
or click on the "render nbviewer" banner above
to display the demos with the 
[Jupyter Notebook viewer](http://nbviewer.jupyter.org). 
[Nbviewer](http://nbviewer.jupyter.org/) will allow you to view the notebooks online,
but you will not be able to change them or evaluate any code, like it is possible with
[binder](https://mybinder.org/v2/gh/lumispy/lumispy-demos/master).

### Running and visualizing the demos locally

To run the demo notebooks locally, 
clone or download the [demos repository](https://github.com/lumispy/lumispy-demos) 
to your local machine, [install LumiSpy](https://lumispy.readthedocs.io/en/latest/user_guide/installation.html)
with its dependencies and [Jupyter Lab](http://jupyterlab.readthedocs.io/en/latest/)
or [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/)
and use either of the two to run the notebooks.

#### (For developers) Testing the demos locally

To test the demos, install
[nbval](http://github.com/computationalmodelling/nbval) and
[py.test](https://pytest.org/) and run

```bash
$ py.test
```

To help visualize differences/errors, install
[nbdime](http://github.com/jupyter/nbdime) as well, and run the test with

```bash
$ py.test --nbdime
```

## Contributing

To contribute new demos or improvements to the current ones, fork the demos
repository and send us a pull request. See the
[LumiSpy contributing guide](https://lumispy.readthedocs.io/en/latest/contributing.html)
as well as the
[HyperSpy Developer Guide](http://hyperspy.org/hyperspy-doc/current/dev_guide.html) 
for more details on how to contribute to the HyperSpy universe.

For issues and discussions file a [new issue](https://github.com/lumispy/lumispy-demos/issues) 
in this repository.

