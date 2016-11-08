# react-flask-boilerplate
Boilerplate for setting up new React Projects running on a simple Flask webserver, built with Gulp and Watchify

## Requirements
- [Python 3.4+](https://www.python.org/)
- [Node 0.10.25+](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [virtualenvwrapper 1.11.6+](http://virtualenvwrapper.readthedocs.io/en/latest/http://virtualenvwrapper.readthedocs.io/en/latest/)
- [git-flow](https://github.com/nvie/gitflow)

# Installs
- [Flask](http://flask.pocoo.org/docs/0.11/)
- [React](https://facebook.github.io/react/)
- [Gulp](http://gulpjs.com/)
- [Browserify](http://browserify.org/)
- [Watchify](https://github.com/substack/watchify)

## Installation instructions
1. Clone this repository with a new project name
```bash
git clone https://github.com/Eighty20/react-flask-boilerplate new_project
```
3. Create a new repository on github or bitbucket with the same name
2. Enter the directory you just created
```bash
cd new_project
```
4. Set the remote origin of your project to the new repository and push
```bash
git remote set-url origin https://github.com/Eighty20/new_project
git push origin master
```
3. Set up `git flow`
```bash
git flow init -d
```
2. Checkout the `develop` branch
```bash
git checkout develop
```
4. Set up a new python virtual environment
```bash
mkvirtualenv --python=/usr/bin/python3 training
```
5. If your virtual environment is not immediately activated, enter it with
```bash
workon training
```
6. Install the required python packages
```bash
pip install -r requirements.txt
```
7. Install the required node modules
```bash
npm install
```

## Running the app
1. In a new terminal, in the project folder, run `gulp`
```bash
gulp
```
2. In another terminal, start the webserver
```bash
./run.sh
```
3. In a browser, navigate to
```
http://localhost:5000
```
4. Read the documentation on each of the technologies to figure out where to go from there.
