# Miscellaneous thoughts on assessment

## What should we teach?

* We've mostly spoken about software tools (i.e., Git, GitHub, Docker,
  Python, R, Make, unit tests, etc.) for reproducibility.  Yet the mechanical
  reproduction of results is not an end, but a means to provide a secure
  foundation for reliable research.  To what extent
  should we be teaching/discussing other aspects of computational
  reproducibility (e.g., statistical issues) and tool-agnostic principles
  that can be introduced in many different contexts.
* Statistical training makes sense for many scientists, but may
  not be as widely appropriate as the tools for computational reproducibility.
  For instance, what role would statistical concerns play in a traditional
  numerical analysis course. The specifics of statistical reproducbility
  are probably best determined at a domain specific level.  There might still
  be some statistical issues that cross many domains. For example, the
  relationship between effect size and probability of reproducing that result.
* It is an open question as to what exactly we mean by the term
  computational research.  Different domains will have different working
  definitions and issues.  However, we do seem to agree on the usefulness
  of some of the core tools, which are shared across domains.
* There are also issues involved with open science and access such as
  licenses, permanent identifiers, provenance, appropriate data repositories,
  and open access publication.
* Teaching some philosophy of science might increase students "buy-in",
  convincing them that reproducibility is a thing to pursue.
* Relatedly: there might be an argument for teaching "data science for
  future presidents" (analogous to UCB's "physics for future presidents"),
  in which the tools are not taught, but the concepts, and their importance, are.

## Class assessment

* From the campus perspective, it would be useful to have a ranking of courses
  in terms of the degree that they teach or encourage reproducible practices,
  without being too particular about tooling. For instance, assignments are
  submitted as:
  * scripts and narrative text
  * scripts and narrative text and the scripts are version controlled
  * scripts and narrative text and everything is version controlled
  * etc

## Student assessment

* Much of our experience in assessing students has been on end results
  (e.g., check results of submitted code and read final report), while
  reproducibility is more about process than product.  This is due in
  part to necessity but is also a practical way to introduce principles
  of reproducibility without demanding
  high-level skills in specialised software tools.  As class sizes grow,
  detailed individual review becomes increasingly difficult.
  * combine autograding, with short answer (1 sentence to 1 paragraph)
    interpretive responses to demonstrate you've understood what you've
    done and why you did it.
  * peer grading / review is potentially a good way to scale up closer
    examination of code, and also to help students recognize the value of
    good design and documentation.
  * 3 stage model:  (a) 1 student/group develops project, (b) another
    student/group tries to reproduce the work of the 1st group and when there
    are issues they work with the 1st group to improve the code and/or
    documentation using an issue tracker and possibly pull requests, and
    (c) finally a 3rd student/group checks that the work is now reproducible
    without needing to communicate with either of the first two students/groups.
