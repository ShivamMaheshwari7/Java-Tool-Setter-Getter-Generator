# Java-Tool-Setter-Getter-Generator

A tool that analyzes a java class and generates setters/getters for all the class level properties, and a default constructor in which default value is setted for all properties.
By using this tool one can get rid from writing setter/getter for class properties.

This tool copy all the generated setter/getter and default constructor on clipboard.

Note : Currently works for only windows users.

# Getting started

1) Download [SetterGetterGenerator.class](SetterGetterGenerator.class) file.

2) To generate setter/getter for class properties - 

    java -classpath "path to SetterGetterGenerator.class file";. SetterGetterGenerator "class name with package of which user want to generate setter/getter"
