# webpack-pyvue
Vue.js + Webpack + Python fullstack application

## Installation
Go to the src folder.

```bash
virtualenv env
```

Activate the Virtual Enviroment and install the following packages.

```bash
Click==7.0
Flask==1.1.1
itsdangerous==1.1.0
Jinja2==2.10.1
MarkupSafe==1.1.1
Werkzeug==0.15.4
```

## Usage

Into the src\appsite load the NPM modules.

```bash
npm install
npm run build
```

Execute the Python server

```bash
python server.py
```

## References
The references I've used to build this solution.

[Vue.js - Getting started](https://vuejs.org/v2/guide/#Getting-Started)

[Creating a full-stack web application with Python, NPM, Webpack and React](https://codeburst.io/creating-a-full-stack-web-application-with-python-npm-webpack-and-react-8925800503d9)

[Vue.js and Webpack 4 From Scratch](https://itnext.io/vuejs-and-webpack-4-from-scratch-part-1-94c9c28a534a)



## License
[MIT](https://choosealicense.com/licenses/mit/)
