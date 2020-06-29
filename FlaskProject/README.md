## FlaskProject

This Flask Project has been built based in the guide [Getting Started With Flask, A Python Microframework](https://scotch.io/tutorials/getting-started-with-flask-a-python-microframework). The project search to rebuild the code using Python3.

### Web App being developing

### Table of Contents

- [x] Installation
- [x] Say "Hello World!" with Flask
- [ ] Directory Structure
- [ ] File Structure
- [ ] Configuration
- [ ] Initialization
- [ ] Run, Flask, Run!
- [ ] Views
- [ ] Templates
- [ ]  Conclusion 

* Before table of contents currently has the same structure of the original article writted by [Mbithe Nzomo](https://github.com/mbithenzomo/), as the project evolves, it may or may not change.

# Install and setup

Firt we'll go to install the libraries will help us to keep the dependencies used by the projects separate.

```
pip3 install --user virtualenv
pip3 install --user virtualenvwrapper
```
or
```
pip3 install -r requirements.txt
```

```
export WORKON_HOME=~/Envs
source ~/.local/bin/virtualenvwrapper.sh
```

Now we'll create and active a virtualenv. In this case called _my-venv_
```
mkvirtualenv my-venv
workon my-venv
```

Now we'll create the dictory for our project.
```
mkdir FlaskProject
cd FlaskProject
```

Now, we'll install Flask
```
pip3 install Flask
```
