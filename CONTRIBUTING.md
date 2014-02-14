Contributing to Duktape
=======================

Duktape copyrights are held by its contributors.  Contributors agree to
license their contribution(s) under Duktape `LICENSE.txt`.  See `AUTHORS.txt`
for details.

To make a contribution to Duktape:

* Fork the Duktape Github repository and make your changes.  Use a well named
  topic branch for the changes, preferably with lowercase and dashes, e.g.
  `xyz-compiler-fixes`.

* Test your changes as thoroughly as possible.  At the very minimum, the number
  of failed test cases with `make qecmatest` and `make apitest` should not
  increase.  If some test cases are invalidated by the changes, fix the test
  cases as part of the commit.  If you add new functionality, you should add
  test case(s) to illustrate the changes and desired behavior.

* Ensure your code follows the style guidelines in `code-issues.txt`.
  Not everything is spelled out explicitly, so try to follow the general
  style in the code base.  Check that your diff looks as clean and minimal
  as possible.

* Add yourself to the end of the author list in `AUTHORS.txt` if you're
  not already on the list.  By doing this you confirm that:

  - You own the rights to the contribution, or have the legal right to
    license the contribution under Duktape `LICENSE.txt` on behalf of
    the copyright owner(s).

  - You, or the copyright owner(s), agree to irrevocably license your
    contribution under Duktape `LICENSE.txt`.

  - Please include an e-mail address, a link to your GitHub profile, or
    something similar to allow your contribution to be identified accurately.

* Create a pull request in Github.  For now, the "base branch" should be
  "master", i.e. the pull requests are merged directly to the master branch.
  In the description:

  - Summarize the change and the motivation for the change.

  - If test case status changes (tests are broken / fixed, test cases
    themselves needed fixing, test cases were added, etc), mention that.