# taskgv
Generates a pretty, directed graph of [Taskwarrior](http://taskwarrior.org) projects, tags, and tasks. #Has, thus far, only been tested on OS X.#

Things end up looking kinda like this:

![A section of my horrifying todo-list.](examplegraph.tiff)

## Requirements

* Python

* Taskwarrior

* Graphviz

## Usage

When placed in your $PATH, `taskgv.py <filter>` opens a graph of your business, filtered by Taskwarrior `<filter>`.

### Credit

This script is derived from [graphdeps.py](http://taskwarrior.org/projects/taskwarrior/wiki/ExternalScripts#graphdepspy).
