Issues
======

We use GitHub for tracking bugs in products. Periodically, reports are taken from Issues to shed light on the overall performance of the platform.

By default, all Issues logged in Github are meant to be considered a _bug_, meaning, _a software problem affecting the stability of the product_. This includes functionalities that run without error, but do something unexpected which also works against the system's stability.

Priority Labels
---------------

We use the labels P1, P2, P3 and P4 to define the overall _priority_ of resolution on the issue.

**P1** - Urgent. A key system component or feature is broken. These are the team's highest priority until resolved.

**P2** - Important. Should be fixed in the next 2-4 weeks.

**P3** - Fix eventually (within 2-3 months).

**P4** - A nice-to-have; will add as time allows. Mostly includes enhancements that aren't often requested, but would drive value in the product especially if released along with other P4s.

Other Labels
------------

All other labels are meant to take an Issue beyond the context of a _bug_.

**enhancement** - An iterative improvement to a module which is already functioning normally.

**support** - Issues which are tied to client feedback which would benefit from a personal response.

**security** - Issues that could have an effect on the privacy of client information.

_Note: Adding any of these labels doesn't change the apparent priority of an issue. It is possible to have a high-priority "enhancement"._

Enhancements
------------

Though _enhancements_ are not _bugs_, they are inherently no less important; their priority is still defined with P1-P4 labels. For example, if a new feature is in working order, but part of it generates enough negative feedback, a new issue can be created as a high-priority enhancement. The issue in no way causes instability in the platform, but needs to be addressed quickly for the users.

Feature Requests
----------------

Feature requests are ideas for new capabilities to be added to the product, such as:

*   A new module.
*   Functionality that one module doesn't have, where another one does.
*   Integration with a third-party service.

Issues is not a place for feature requests.

Issue Template
--------------

GitHub supports [Issue Templates](https://help.github.com/articles/creating-an-issue-template-for-your-repository/). Here's a template to use for the repository:

```
Expected behavior
-----------------


Actual behavior
---------------


Steps to reproduce
------------------

1.
2.
3.
4.
5.

Support cases, if any
---------------------


```
