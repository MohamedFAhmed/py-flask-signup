
## Features
###
### Themes
The code includes several Bootstrap themes from [bootswatch.com](http://bootswatch.com/). You can dynamically change the active theme by setting the THEME environment variable in the [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk) or setting OS environment variables imported by web server.

![](misc/theme-flow.png)

Installed themes include:

* [flatly](http://bootswatch.com/flatl
* [slate](http://bootswatch.com/slate)
* [united](http://bootswatch.com/united)

### Flask Debugging
Similar to themes, you can control Flask debugging by toggling the FLASK_DEBUG env var from the [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk) or setting an OS environment variable imported by web server.
