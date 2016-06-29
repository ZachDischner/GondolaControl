# GondolaControl

## Authors
* Zach Dischner
* Pierce Martin
* Wences Shaw-Cortez

## Development
Suggest you work on a Mac. iTerm + Sublime/Atom or JetBrains PyCharm. Source Tree is a great Git tool to go alongside command line use. 

git will be used extensively, potentially with a git-flow workflow in the future. 

git-flow: http://danielkummer.github.io/git-flow-cheatsheet/

## Software Environment 
The Anaconda Python environment is recomended for managing python environment used. 

https://www.continuum.io/downloads

### Python
For the most part, stick to standard coding practices as outlined by Python PEP-8 https://www.python.org/dev/peps/pep-0008/. A few stylistic differences will be found (no line length limits, aligned eqal signs, etc), as outlined in `Modeling/sample.py`. An intelligent state-aware mix of object oriented and functional programming practices are encouraged. I.E. don't create state and wasteful procedural loops when functional comprehensions and mappings will do, but don't hamstring yourself when classes and objects would simplify program flow. 

The Python Virtual Environment we're using is called *python35*, it is version 3.5.1

#### Create a Config File Describing Your Environment
0. `conda env export > environment.yml`

#### Create an Environment from Config File
http://conda.pydata.org/docs/using/envs.html

0. `conda env create -f environment.yml`

#### Activate Python Environment When Ready
0. `source activate python35`

#### Go Play!
0. `ipython --pylab`
0. `ipython --notebook`
0. `python someScript.py`
