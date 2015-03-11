![Build Status](share/4i/images/logo.png)

# 4i

4i is a **Model-Oriented Programming** and **Meta-Programming** orchestration tool, you can use it to create models and generate codes. It makes possible for programmers to build there own modules from-scratch or just extend some existing ones.

## Development state

Software is still under development but it is already used internally. An active work is ongoing to make 4i as good as possible for any developer backgrounds.

However it is hoped to build a module hosting platform in a near future according to the following roadmap:

1. Several primitive modules will be released such as programming languages (c++, python, html, ...) easier and high and low level development framework (django, flask, boost, ...).
2. A module hosting platform that will enable users to pull-push modules, to extend modules based on other modules and share them with others.
3. A project hosting platform to assemble modules, host projects and deploy them.

## Going further

### Documentation

Coming soon...

### Talk about/get involved in 4i project

If you wish to participate/debate on 4i, you can:

* join the discussion group: https://groups.google.com/forum/?hl=fr#!forum/4geit-4i
* contact me directly at caner@candan.fr

## Resources

Resources are available at these links:

* [4geit-tool](https://github.com/4geit-tool)
* [4geit-core](https://github.com/4geit-core)
* [4geit-module](https://github.com/4geit-module)
* [4geit-project](https://github.com/4geit-project)

## Big picture

```
   /------------\
   |CORE LIBRARY|
   \------------/
         |
 /----------------\
 |MODULES REGISTRY| (meta-code)
 \----------------/
         |
 /-----------------\
 |PROJECTS REGISTRY| (xml, remix, api)
 \-----------------/
         |
   /------------\
   |HOSTING APPS| (orchestration)
   \------------/
```

## Todo

* 4i-login
* 4i-core-push
* 4i-core-pull
* 4i-core-search
* 4i-core-create
* 4i-core-delete
* 4i-module-push
* 4i-module-pull
* 4i-module-search
* 4i-module-create
* 4i-module-delete
* 4i-project-push
* 4i-project-pull
* 4i-project-search
* 4i-project-create
* 4i-project-delete
* 4i-project-deploy

## References

* [GSL - a Universal Code Generator](https://github.com/imatix/gsl)

## License

This software is provided under [GPLv3](LICENSE).
