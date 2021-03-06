[![Coverage Status](https://coveralls.io/repos/github/riyadhalnur/news-cli/badge.svg?branch=master)](https://coveralls.io/github/riyadhalnur/news-cli?branch=master) [![Build Status](https://travis-ci.org/riyadhalnur/news-cli.svg?branch=master)](https://travis-ci.org/riyadhalnur/news-cli) [![Build status](https://ci.appveyor.com/api/projects/status/7ndfb8ekaa27ajf1/branch/master?svg=true)](https://ci.appveyor.com/project/riyadhalnur/news-cli/branch/master) [![Dependency Status](https://dependencyci.com/github/riyadhalnur/news-cli/badge)](https://dependencyci.com/github/riyadhalnur/news-cli)

news-cli
=================
Read the top/latest news from 24 sources in your CLI. Powered by [NewsAPI.org](https://newsapi.org/).  

![screenshot](screens/screen.png)

### Installation  
`npm install -g news-cli`  

### Usage  
```shell
Usage
  $ news <source>

  Choose which source to display news from. Defaults to techcrunch.
Options
  --sort Choose to show latest, top or popular news. Defaults to latest.
Examples
  $ news
  $ news hackernews --sort top
```

### Clickable Links
If you are using [Hyper](https://hyper.is), you can make the links clickable with the [hyperlinks](https://github.com/zeit/hyperlinks) plugin.  

### License  
Licensed under MIT. See [LICENSE](LICENSE) for more information.  

### Issues  
Report a bug in issues.   

Made with love in Dhaka, Bangladesh by [Riyadh Al Nur](https://verticalaxisbd.com)
