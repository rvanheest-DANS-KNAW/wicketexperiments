# Experiments with Wicket

This repository contains Maven projects for experimenting with the Wicket web framework.

* [wicket-intro](/wicket-intro)
* [wicket-intro-8](/wicket-intro-8)
* ...

## Get started
To get started with any of these projects, run the following commands:

    cd <subproject>
    mvn clean install
    mvn jetty:run

## Development
I've set up the Jetty plugin such that it will scan for changes in the compiled sources. Therefore,
during development, you start by running `mvn jetty:run` in a terminal, and after that you only
need to click '_compile_' in IntelliJ and reload the browser window to see the changes.

These are the urls to follow in order to see the results:
* wicket-intro
    * default home page - http://localhost:8080
    * shoppinglist - http://localhost:8080/shoppinglist

## Tutorials/Documentation
* [Apache Wicket Quick Start](https://www.youtube.com/watch?v=V_XmXeiVito)
* [Guide (Wicket 7)](https://ci.apache.org/projects/wicket/guide/7.x/single.html)
* [API docs (Wicket 7)](https://ci.apache.org/projects/wicket/apidocs/7.x/index.html)
* [Guide (Wicket 8)](https://ci.apache.org/projects/wicket/guide/8.x/single.html)
* [API docs (Wicket 8)](https://ci.apache.org/projects/wicket/apidocs/8.x/index.html)
