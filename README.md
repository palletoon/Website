# Website
website using visual studio and python
1. Learn the basics of coding
2. Learn programming language most relevant to speech language pathology
3. Make an awesome website with language games
4. JavaScript and Data Structures Certification--Basic JavaScript (FreeCodeCamp?)
5. Scientific Computing with Python Certification


<img src="images/Screenshot%20(114).png" width="100">

![](images/Screenshot%20(114).png)

direct in git bash

![](images/Screenshot%20(135).png)
![](images/Nari%20and%20kibbles.jpg)
![](images/parrot_problem.png)
![](images/parrot_problem_2.png)
![](images/parrot_problem_3.png)
![](images/parrot_problem_JS.png)

## 02.19.2021 set up virtual environment venv
![](images/Screenshot%20(141).png)
![](images/Screenshot%20(139).png)
![](images/Screenshot%20(140).png)
Codes are:
* which python
* python --version
* source ./venv/Scripts/activate
* which python
* pip install pylint pytest pytest-watch pytest-testmon pytest-describe
* pip freeze
* pip freeze > requirements.txt
* git add requirements.txt
* git status
* git commit -m"venv setup"
* git push

after writing the test
* pytest
* git add .
* git commit -m "sleep_in tests written"
* git push

## 02.22.2021 continue venv
* source ./venv/Scripts/activate #activate virtual environment
* pytest
* ptw #runs changes automatically
* = assignment == equality comparison

## 02.24/2021
* ctrl + / or control and forward slash marks every line highlited # or comments
* git status
```python
# pylint: disable=unused-variable
```
* makes yellow squiggly underline (means possible variable error) go away
* ```python
./venv/Scripts/activate
* ```
* M next to files means modified

## 02.26.2021
* 1. Finished monkey_trouble
* 2. Created JavaScript edition repository on github
* 3. Clone repository on git and code on visual studio
![](images/Screenshot%20(150).png)
* 4. Initiated npm (==pip of Python)
    first check `which node` then `npm init`
    add description: My solutions to Coding Bat challenges in JavaScript
    add test command: jest
    add author: palletoon <palletoon@gmail.com>
* 3. Install lingting and testing tool
    ```js
    npm install eslint jest --save-dev
    ```
    eslint is for linting and jest is the testing --only required by developers and development dependencies. Never upload node_modules file onto github
* 4. Configure eslint
   ```js
   ./node_modules/.bin/eslint --help
   ./node_modules/.bin/eslint --init
   ```
the terminal will walk us through initializing eslint
![](images/Screenshot%20(151).png)

## 03.01.2021
* .eslintrc.js gets installed when you initialize eslint
* can download eslint on the website
* npm install == yarn add
* npm i -D eslint-plugin-jest # install
* in eslintrc.js, under env, under, es2021: true, add 
```js
'jest/globals': true,
```
and above rules: {
```js
plugins: ['jest'],
```
* creat warmup-1\sleep_in then README.md and sleep_in.spec.js # which is equivalent of test
```js
npm test
```
