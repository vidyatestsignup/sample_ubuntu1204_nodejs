Node.js Sample
=================

This sample is built for Shippable, a docker based continuous integration and deployment platform.

This sample helps you create a shippable.yml file for your Node.js project on Shippable. It uses Grunt to run tests against an Express server, then generates reports with Xunit and Istanbul. Please refer to our [language specific documentation on Node.js](http://docs.shippable.com/languages/#nodejs) for more details.

### Build Image

The sample uses a php specific build image that's available for public use:
[shippableimages/ubuntu1204_nodejs](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_nodejs)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_nodejs/blob/master/Dockerfile)).

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_nodejs`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).
