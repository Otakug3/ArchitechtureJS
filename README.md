ArchitectureApp Client
============

Simple AngularJS client for the ArchitectureApp , a Spring web application providing a RESTFul JSON API consumed by this client. The ArchitectureApp is available from [https://github.com/otakug3/ArchitectureApp](https://github.com/otakug3/ArchitectureApp)

To run locally, you need first node.js and its package manager (npm) installed.  You can get them from [http://nodejs.org/](http://nodejs.org/).

Then, use npm to install the dependencies in package.json, currently just the http-server module:
```
npm install
```

And to run the server on http://localhost:8000
```
npm run-script server
```

There is also a Procfile to run http-server once deployed to Heroku that calls npm start, which is intended just to run the application there.


The application ArchitectureApp is available by Web interface at: http://stormy-temple-9571.herokuapp.com/

When running the route to acces to the application is: 

http://localhost:8000