### Deep Learning with TensorFlow 

#### Basic Installation:
If running Anaconda 4.4.0 with Python Ver 3.6 on MacOSx (Thanks to https://stackoverflow.com/users/3245212/darpan-dodiya) works for Windows as well as MacOSx

---
    * conda create --name tensorflow python=3.5  ( Creates a tensorflow environment with Python 3.5 version)
    * source activate tensorflow
    * conda install jupyter
    * conda install scipy
    * pip install tensorflow
    * source deactivate tensor 

Close Anaconda and relaunch and select tensorflow under the Applications On "tensorflow" on the Anaconda Navigator Window. 

#### Basic Conda Instructions ( https://conda.io/docs/using/envs.html)
On the terminal window follow the instructions below to verify the current environments.
* conda info --envs  ( or can use conda info -e )
---
    tensorflow            *  /Users/PAVIK/anaconda/envs/tensorflow
    root                     /Users/PAVIK/anaconda

#### Launching ipython notebook on MacOsx ( Instead of copying link and pasting it in browser)
https://github.com/JuliaLang/IJulia.jl/issues/551
Typing at a shell prompt:
> jupyter notebook --generate-config
and then uncomment/edit the line of the file ~/.jupyter/jupyter_notebook_config.py (just created), into
c.NotebookApp.browser = 'Safari' (to have Safari explicitly indicated)
