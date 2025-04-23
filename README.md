# Instructions to start
# STEPS:


### Install flake8 and black python packages:
    pip3 install flake8 black 

### go to .git/hooks and create pre-commit file
    touch pre-commit

### Copy code from the pre-commit file and paste inside .git/hooks/pre-commit

### Make the script executable

    chmod 777 pre-commit
### Run python file with flake8

    flake8 app.y

### Run python to check black

    black --check app.py

### Run python to format properly
    black app.py
