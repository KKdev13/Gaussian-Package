A python Gaussian Package for a ML project

Inside the folder called `Gaussian Package`, you'll find another folder and a number of files. Here is a description of each
- distributions, which contains the code for the distributions package including Gaussian.py, Binomial.py, and Generaldistribution.py code.
- setup.py a file needed for building python packages with pip
- test.py unit tests to help you debug your code
- numbers.txt and numbers_binomial.txt are data files used as part of the unit tests (test.py file)
- __init__.py inside the distributions folder for importing class modules.


When you're ready to test out your code, you'll want to pip install your distributions package and then run the unit tests. In the terminal, assuming you are in the Gaussian Package directory (if not type `cd Gaussian Package`), type `pip install .` into the command line. Then run the unit tests by typing `python -m unittest test`. 

All the unit tests should pass. 

Note that if you change the code in the distributions folder after pip installing the package, Python will not know about the changes. You'll need to run `pip install --upgrade .` when you make changes to the package files.