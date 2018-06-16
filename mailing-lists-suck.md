# Mailing lists suck

It boggles my mind that people use mailing list to collaborate on projects.

The only explanation is that the dinosaurs who created the projects are unable to adapt to new superior technologies.

Advantages of mailing lists:

*   threaded replies, which almost no issue tracker has. GitHub feature request: https://github.com/isaacs/github/issues/837

Disadvantages: everything else:

*   cannot subscribed to a single thread. Which forces you to create an email filter for each one of them you subscribe to.

*   no metadata, notably the notion of closing / merging, but also upvotes

    You have to read thirty messages before you can know if the bug was solved or not.

*   it is insanely hard to reply to messages from before you were subscribed: https://webapps.stackexchange.com/questions/23197/reply-to-mailman-archived-message/115088#115088

*   hard to apply patches locally to test them out https://stackoverflow.com/questions/5062389/how-to-use-git-am-to-apply-patches-from-email-messages#comment85170730_5062549

    Unless they use Patchwork, which adds one more website on top of the mess.

    And then gmail corrupts your patches, and you are forced to use `git send-email`, which does not work on some network configurations: https://stackoverflow.com/questions/28038662/how-to-solve-unable-to-initialize-smtp-properly-when-using-using-git-send-ema or setup ThunderBird.

*   often have to subscribe to post at all, thus cluttering your inbox further

*   you can edit posts to make them clearer.

    Yes, people could vandalize their answers when they get mad, and threads might stop making sense after edits. But this can be solved with an undeletable post history like Stack Overflow has (but not any other tracker does).

    Or archive.org :-)

    In any case, what do you think will happen more often and have greater impact:

    * people vandalize their posts
    * people fix their silly typos and improve content

*   searchable by author, keyword, etc. without Google. Yes, mailing list trackers could have decent implementations to overcome that. But no, GNU Mailman which everyone uses does not have it. Google barely indexes it.

    And I don't think Google properly indexes many of the mailing list archives for some reason: I never get hits for my own posts a week later, while I often do on GitHub issues.

*   people have to learn about top posting vs inline posting, and this requires infinite education of new users

Not sure:

*   you can have infinitely many trackers to replicate data in case apocalypse happens in some part of the world.

    Although I'm not sure this is an advantage, as you don't know anymore which one is the canonical trackers an advantage, as you don't know anymore which one is the canonical tracker.

    And all web interfaces already have an API to export messages, and someone has already scripted it to import from any web UI to any web UI for you.

    And GitHub offers infinite precise history transparently on its API.

Smart people:

* https://news.ycombinator.com/item?id=13631069
* https://softwareengineering.stackexchange.com/questions/191961/why-do-some-big-projects-like-git-and-debian-only-use-a-mailing-list-and-not-a#comment779146_256479
