# ci.yaml
Github provides us a service called Github Action -- > pushing the code to Git hub     

# requirements_dev.txt we use for the testing 
It makes it easier to install and manage dependencies for development and testing, separate from the dependencies required for production

# difference between requirements_dev.txt and requirements.txt 
requirements.txt is used to specify the dependencies required to run the production code of a Python project, while requirements_dev.txt is used to specify the dependencies required for development and testing purposes.

# tox.ini
We use if for the testing in the python package testing against different version of the python 
Testing the project in a local envirnonment 

## how tox works tox enviornment creation
  1. Install depedencies and packages
  2.Run commands
  3. Its a combination of the (virtualenvwrapper and makefile)
  4. It creates a .tox

# pyproject.toml 
  similar to setup config , to write it on our meta data 

# init_setup.sh 
  write down all the commands in the shell script  
  virtual environment is not required - conda create , cond

# Src 
  Source Code 

# Experient 
  for iterations and experiments -  

# Test folder 
  Test cases  
  1. Integration Testing - Componenents 
  2. Unit Testing - Individual componenents

# .Github 
  workflows folder - Complete configuration 
  1. ci.yaml : Config related to the continous integration - To test the code in Github (Git hub Action server) (As soon as i push the code to Github action) 
  2. python-publish.yaml : Config related to the PyPi deployment - Deploy the code to the PyPi depositary


     
