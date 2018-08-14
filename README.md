# Angular Environment Variables Demo

This project contains a working demo of [How to use environment variables to configure your Angular application without a rebuild](https://jvandemo.com/how-to-use-environment-variables-to-configure-your-angular-application-without-a-rebuild/).

If you have the ability to rebuild your application for use in different environments, the built-in Angular CLI [application environments](https://github.com/angular/angular-cli/wiki/stories-application-environments) are perfect for storing configuration details.
 
However, if your application needs to be deployed with a different configuration in different environments **without having the ability to rebuild it**, this mechanism may be just what you are looking for. 

To get a better understanding of the inner workings, make sure to [read the article](https://jvandemo.com/how-to-use-environment-variables-to-configure-your-angular-application-without-a-rebuild/).

## Instructions

1. Run `ng build --prod` to build the project. The build artifacts (including `env.js`) will be stored in the `dist/` directory.
2. Serve the contents of the `dist` directory using a static web server like [serve](https://github.com/zeit/serve).
3. Edit `env.js` in your `dist` directory to control the environment variables within your Angular application without the need for a rebuild.

As soon as you refresh your browser, the new environment variables are picked up:

![Angular Environment Variables Demo](https://user-images.githubusercontent.com/1859381/44098643-b82bd342-9fae-11e8-8810-8c80b814eb3a.gif)

## More info

For more information, check out the [How to use environment variables to configure your Angular application without a rebuild](https://jvandemo.com/how-to-use-environment-variables-to-configure-your-angular-application-without-a-rebuild/).
