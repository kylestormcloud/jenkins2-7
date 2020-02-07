# jenkins2-7
Repository created at the direction of Stephen Wight for the purpose of learning Jenkins.

### About Jenkins:
* Jenkins is CI heavy and CD light.
* Open source
* written in Java

### Jenkins Pipeline:
* Development
* Code Commit
* Build
* Test
* Release
* Deploy / Deliver
* Production


### Unit Testing:
* every small piece of your code has a test
* fewer human eyes have to hit your code
* ideal: run tests, then straight to dev

### Step 1: Virtual Environments
* $ pip install virtualenv
* *change to project folder
* $ python -m virtualenv venv
* $ source venv/bin/activate
* (venv) $ pip freeze

### Environment Requirements:
* $ pip install pytest
    * unit testing for python
* $ pip install pytest-cov
    * plug-in for pytest
    * code coverage test
* $ pip install pylint
    * syntax checker
* $ pip freeze > requirements.txt

### pytest:
* $ python -m pytest
* $ python -m pytest --junit-xml test-result/results.xml
* $ python -m pytest --cov=./
* $ gedit .coveragerc
* $ python -m pytest --cov=./
* $ python -m coverage xml
