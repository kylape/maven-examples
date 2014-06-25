#Kyle's Example Maven Projects

This is a collection of maven projects that I've created over time for various
support cases.  There is no customer-specific information contained in these
examples; they are all generic examples.

Each example is a git submodule.  I did it this way so that a project could
easily be referenced in a support case without having to clone every other
project along with it.  This has the disadvantage of 1) not having one
centralized POM that could reduce repetitive dependencies/BOMs and 2) you can't
view the source tree of everything in one place.  Both are pretty weak
disadvantages IMO.

Currently all submodules are referenced using the github SSH URL.  I'll soon
try to stick these in a different branch and make `master` use the `https`
URLs.
