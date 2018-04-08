# Javascript Static Code Analysis

ESLint, JSLint and ESLint 
Above Tools are integrated with maven for testing.

# Prerequisites
  - Java
  - Node
  - Maven

# Installtion
  ```sh
$ git clone https://github.com/learnuxui/static-code-analysis
$ cd static-code-analysis
$ mvn install
```

# JSLint 
 JSLint is a JavaScript program that looks for problems in JavaScript programs. It is a code quality tool.
 For JSLint execution I have used `com.googlecode.jslint4java` maven plugin
     Parms
    options : A comma separated list of options to pass to JSLint.
    haltOnFailure : Should the build stop if JSLint reports an error? Defaults to true.
    
# JSHint 
JSHint is a program that flags suspicious usage in programs written in JavaScript. The core project consists of a library itself as well as a CLI program distributed as a Node module.
JSHint Optiions : http://jshint.com/docs/options/


# ESLint
ESLint is an open source project originally created by [Nicholas C. Zakas](http://nczonline.net/) in June 2013. Its goal is to provide a pluggable linting utility for JavaScript.
Available ESLint rules : https://eslint.org/docs/2.0.0/rules/

Ref :
 https://www.jslint.com/
 https://eslint.org/
 http://jshint.com/

