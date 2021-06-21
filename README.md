# Introduction to Sphinx

Sphinx is a documentation generator that translates a set of plain text source
files into various output formats, automatically producing cross-references,
indices, etc. Sphinx has many features for writing technical documentation which includes:

* Generate web pages, printable PDFs, and documents for e-readers (ePub) from the same sources.
* Use reStructuredText to contribute for project's documentation.
* An extensive system of cross-referencing code and documentation

## Getting Started with Sphinx

To get started with Sphinx, execute the following command:
  ```
  $ sphinx-quickstart
  ```
Sphinx quickstart creates a sample project with the following standard structure:

  ```
  project/
   docs/
    conf.py
    index.rst
    Makefile
  ```
For more details on Getting started with Sphinx project, [Sphinx Getting Started](https://www.sphinx-doc.org/en/master/usage/quickstart.html).

## Installing Sphinx

To install Sphinx for contributing to documentation, the following prerequisites must be installed:

* To install python, run the following command:
  
  ```
  $ sudo apt update
  $ sudo apt install python3.8
  ```
* Pip is a tool for installing the python packages. To install pip in your local, run the following command:
  
  ```
  $ sudo apt update
  $ sudo apt install python3-pip
  ```
* To generate the HTML documentation locally, Sphinx must be installed. Execute the following command:
  
  ```
  $ apt-get install python3-sphinx
  ```
* To build the documentation, make file must also be available on your host system.

For more details on Sphinx installation, see [Sphinx Installation](https://www.sphinx-doc.org/en/master/).

## reStructuredText for Documentation

reStructuredText is a lightweight markup language that is used in static site 
generators like Sphinx. It contains robust tools for semantic markup, reusing content, 
and content filters for different kinds of outputs. It’s also easily extendible
using custom directives that you can create yourself, allowing you to satisfy a 
wide variety of documentation needs.

For more information on Sphinx reStructuredText and its syntax usage, see [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html).

## Building the Documentation

Once you have your documentation written and want to turn it into HTML, it’s pretty simple. Simply run:

  ```
  $ make html
  ```
The generated output HTML file can be found inside top-level docs/ build directory.
