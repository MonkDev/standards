Documentation
=============

1.  Project-level documentation should be written in [Markdown](https://help.github.com/articles/github-flavored-markdown)
    in the root-level `README.md` file. See below for a suggested outline for
    this file.
2.  Component-level documentation (i.e., a module or feature) should be written
    in Markdown in the repository's [GitHub Wiki](https://help.github.com/articles/about-github-wikis/).
3.  Proper spelling, grammar, and punctuation should be used at all times.
    Strive to be a good writer.

Code-level
----------

1.  Code-level documentation depends on the language/framework, and should be
    prescribed in the relevant Standards document. In general, it should be
    1.  comprehensive (shoot for 100% coverage),
    2.  easily generated, and
    3.  ignored by version control.
2.  Documentation should appear on the line(s) before the code being documented.
3.  All functions/methods should be documented, including parameter(s), return
    value(s), and exception(s) that can be thrown/raised.
4.  While code-level documentation is generally good, it should not be used as a
    crutch to mask bad code. [As Jeff Atwood says](http://blog.codinghorror.com/coding-without-comments/):

    > You should always write your code as if comments didn't exist. This forces
    > you to write your code in the simplest, plainest, most self-documenting
    > way you can humanly come up with.


Suggested `README.md` Outline
-----------------------------

```
Title
=====

[Badges]

One sentence description.

*   [Link to documentation]
*   [Or staging and production]
*   [Or anything of importance]

Overview
--------

Explain how things work. For an app, give a high-level overview of the system.
For a library, explain how to install, configure, and integrate.

### Use

#### Sections

#### As

### Necessary

Development
-----------

Explain how to setup the development environment. List prerequisites like
languages and databases that can't be installed automatically, as well as
dependencies that can. List the commands for building documentation, running
tests, executing tasks, etc.

Deployment
----------

Explain and list the commands for deploying, restarting services, etc.
```
