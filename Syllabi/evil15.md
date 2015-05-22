# Fiendishly Engineered Reproducible Research

## An evil plan to teach and assess reproducible work processes and software engineering

* Presumed that students get rudiments of git, Python, nose, issue trackers, elsewhere,
e.g., in a 2-day workshop. Alternatively, spend the first 1-2 weeks of the course on this
* Two projects in the course:
    + software development (a module for a Python package, for instance)
    + a scientific problem with data, topic tailored to the students or generally accessible.
The scientific problem will rely on the current state of the Python package, which accrues
functionality each time the course is taught
* Present an abstraction of good workflows for the two types of effort (software development v.
science involving data).
This might be gleaned from our case studies.
* Present a rubric for assessing reproducibility and sound practice
(repo, makefiles, tests, documentation, explicit dependencies, examples, installation instructions, etc.)
* Class divided into two groups
    + One starts on each project
    + Halfway through:
        + assess the state of their projects
        + switch projects
        + take a week to hand off the projects to the other teams.
            + Use standard tools to make bug reports, track issues, make pull requests, etc.
        + assess the reproducibility of the other team's work
            + can install?
            + compiles/runs?
            + passes tests?
            + test coverage?
            + can read the code?
            + can understand the problem?
            + can reproduce examples?
            + etc.
            + experience the cost/pain of the other's failures to work reproducibly
    + Wrap up at end of term.
        + Publish the scientific result with group authorship
        + Contribute the module to the package by pull request
            + help with code review for that request?

### Notes
* Might start with a simple exercise, the equivalent of a "Hello World" reproducibility exercise
    + code something simple and make it as reproducible as possible
    + swap with your neighbor and see whether s/he can install and run it
    + sort out the mess, using standard tools
