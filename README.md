## dwrat-app
Water Right Allocations for California

#### Develop
To develop the standalone dwrat-app, run the following commands.  [NodeJS, NPM](http://nodejs.org) and [Bower](http://bower.io) are required.

One time, init dev environment.  Run on first install or after git pull.
```
npm run init-dev
```

To develop, run:
```
// starts local web server, defaults to: localhost:8080
npm start

// watch filesystem and browserify changes to ./lib
npm dev
```

#### Build
Create new dist dir

```
npm build
```

Test out the build
```
npm run start-dist
```
