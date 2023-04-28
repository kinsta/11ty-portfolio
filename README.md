[![How To Craft a Stylish Static Website with Eleventy](https://user-images.githubusercontent.com/2342458/235165020-59964255-e651-45fd-a236-2690e732117e.png)](https://kinsta.com/blog/eleventy/)

# How To Craft a Stylish Static Website with Eleventy
Learn how to use Eleventy to craft a stunning and functional static portfolio website without needing a server-side language or database.

Read the [full article](https://kinsta.com/blog/eleventy/).

## Kinsta Application Hosting Setup
## Dependency Management

Kinsta automatically installs dependencies defined in your `package.json` file during the deployment process.

## Web Server Setup
### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application, Kinsta automatically creates a web process with `npm start` as the entry point. Make sure to use this command to run your server.

### Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm build` command is run, followed by the `npm start` command.

## What is Kinsta
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)
