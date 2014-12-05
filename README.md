breathingcode.github.io
=======================

The website source for the [Breathing Code](http://breathing-code.de)
conference.

### First run

If you use rvm, then do something like the following:
```shell
rvm use default
rvm gemset use default@breathing-code-de --create
```

After that install the dependencies and run the local server
```shell
bundle install
bundle exec jekyll serve
```

### Editing 

Next time you want to change something, only activate the gemset and run the
local server

```shell
rvm gemset use default@breathing-code-de 
bundle exec jekyll serve
```
