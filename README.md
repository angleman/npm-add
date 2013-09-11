# npm-add [![NPM version](https://badge.fury.io/js/npm-add.png?branch=master)](https://npmjs.org/package/npm-add) [![Build Status](https://travis-ci.org/angleman/npm-add.png?branch=master)](https://travis-ci.org/angleman/npm-add) [![Dependency Status](https://gemnasium.com/angleman/npm-add.png?branch=master)](https://gemnasium.com/angleman/npm-add) [![License](http://badgr.co/use/MIT.png?bg=%234ed50e)](http://opensource.org/licenses/MIT)

A CLI tool for speeding up node.js productivity by instantly adding dependencies to package.json.

recent version: 0.0.1

# Install
Install globally
```
$ npm install npm-add -g
```

# Usage
### Add the latest verison of an npm package
```
$ npm-add jade
```
Then install
```
$ npm install
```

### Add multiple packages
```
$ npm-add jade socket.io
```

### Specify version

```
$ npm-add 'jade 0.30.0'
```

```
$ npm-add 'jade 0.30.0' 'socket.io 0.9.14'
```

### Adding it all together
```
$ npm-add express 'socket.io 0.9.14'
```


### Add and install
```
$ npm-add express stylus async --install
```
or
```
$ npm-add express stylus async -i
```

# Contact
If you would like to contact me for further information on the project, see the info below.

Email: jawerty210@gmail.com

Github: [jawerty](https://github.com/jawerty)

Twitter: [@jawerty](http://twitter.com/jawerty)

Blog: <http://jawerty.github.io>

# License
See the file LICENSE to view the MIT License
