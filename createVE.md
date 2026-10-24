# Create a new virtual envirnment in Linux

First of all, create a new vitrual envirnment named MLP.
'''bs
python3 -m venv MLP
cd numpyProject
source bin/activate
'''
If this is successful, '''(.venv)''' will be put.

And then, use pip tool to install some Python library, escpecially when (.venv) appears.
'''bs
pip install numpy
pip install plt
pip install pandas
pip install scipy
'''
These commands are just a few that I show, when we need to use pip command, we should go to the vitrual envirnment.

Then, we create a Python file called '''main.py''' in '''./MLP'''
