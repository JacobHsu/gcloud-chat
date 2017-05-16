# Setup

Install [Node.js](https://nodejs.org/en/).  
Install [git](https://git-scm.com/).  
Create a [Google Cloud Platform project](https://console.cloud.google.com).   
Install the [Google Cloud SDK](https://cloud.google.com/sdk/). then 
`gcloud auth login`  

### Running locally 
`npm install`    
`npm start`   

### Deploying to App Engine
`npm run deploy`  

package.json
```
  "scripts": {
    "deploy": "gcloud app deploy",
```

[gcloud](https://gcpug-tw.gitbooks.io/google-cloud-platform-in-practice/content/gcloud-intro.html)  

# Tutorials

[Node.js on Google Cloud Platform](https://cloud.google.com/nodejs/)  
[Node.js Getting Started on Google Cloud Platform][gcloud-getting-started]  
[Socket.IO][socketio-getting-started] guide
of the Socket.IO website.  
GoogleCloudPlatform/[nodejs-docs-samples][nodejs-docs-samples] [hello-world](https://github.com/GoogleCloudPlatform/nodejs-docs-samples/tree/master/appengine/hello-world)


[socketio-getting-started]: http://socket.io/get-started/chat/
[gcloud-getting-started]: https://cloud.google.com/nodejs/getting-started/hello-world
[nodejs-docs-samples]:https://github.com/GoogleCloudPlatform/nodejs-docs-samples
[nodejs-docs-samples]:https://github.com/GoogleCloudPlatform/nodejs-docs-samples


### NPM

[![NPM](https://nodei.co/npm/express.png?downloads=true&stars=true)](https://www.npmjs.com/package/express)  
[![NPM](https://nodei.co/npm/socket.io.png?downloads=true&stars=true)](https://www.npmjs.com/package/socket.io)  