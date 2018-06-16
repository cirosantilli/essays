# Replace mailing lists with bug trackers

<http://programmers.stackexchange.com/questions/191961/why-do-some-big-projects-like-git-and-debian-only-use-a-mailing-list-and-not-a>

I am talking to you, big fundamental projects from last century: Linux Kernel GCC https://gcc.gnu.org/lists.html , Binutils https://sourceware.org/binutils/

Some of you are already using Bugzilla for the bugs, so kudos. But if you've seen their benefit, why you still use the mailing list for patches?

Your tooling is still on the last century. There are better tools out there. E.g.: GitLab, GitHub, etc.

Why?

-   no metadata. Specially: open / close.

    Consequence: people have to keep a list of patches they've submitted ping weekly until they get reviewed.

-   it is impossible or very hard to reply to a message if you were not yet subscribed.

    This forces everyone to subscribe to all lists, and then set up email filters to not be flooded with emails.

-   It is not possible to subscribe to individual threads

-   Mail clients like to corrupt patches, so sending in body is bad. E.g.: <https://productforums.google.com/forum/#!topic/gmail/HasB4x0gdz8>

-   most mail web UIs suck.

    OK, this is not an unsolvable or intrinsic problem, but still a problem.

    E.g.: `ezmlm` it is not possible to see the entire content in a single page: <https://gcc.gnu.org/ml/gcc/2015-07/threads.html>

    Unless you like reading threads backwards and with 4 levels of `>` quotations.

    The alternative: do like LLVM and send attachments. Yes, I we all love opening up attachments on our browsers.

    The real solution: everyone can create branches and pull requests. Also has the benefit of running CI on the pull requests.

-   Line comments in code reviews like GitHub and GitLab.

    On mailing lists: either put a comment in the middle of a huge patch and let other people find it, or (more likely) copy paste the part of the patch that you are talking about.

There is only one good thing about email which most Git web UIs don't do yet: comment threading, like Reddit.
