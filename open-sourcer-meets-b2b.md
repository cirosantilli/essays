# Open Sourcer meets B2B

Thoughts that I've had when I entered my first closed source B2B job at Quartet FS in Jan 2015 after contributing to open source for a while. 

The company was a good one, and I've learnt a lot.

There were good and bad points, and for every criticism I sometimes could understand why things were like they were even if I disagreed with some of them.

## Misc

One of the managers was deciding how to structure the code of a project. He did not know Git. I hope that when I get older, I manage to keep up with the new technologies :) But I am aware that this is far from certain, as I already have a slightly hard time with some new things I see younger people using.

I am obsessed by improving workflows. Before you working, I always improve the workflow first. Then I and everyone else can work much faster later.

Quartet FS becomes QFS, which in French sounds like "cul et fesses" (asshole and ass cheeks). French people immediately see it. Also interestingly, QFS on Google does not show Quartet on the front page: Quantcast Filesystem dominates, with Oracle's Quick File System following, both of which are Big Data competitors :)

I was given tasks before understanding real use cases. This made them less interesting, and harder to solve.

A few of the developers type without the 8 fingers. Scary.

My boss asked me today if I liked the job, because I was making too many suggestions which were not related to my direct obligations. I can understand why he worries about that, but as I've told him, I made those suggestions because they are low-hanging fruits which are related to what I already know, and which be easy to improve, and that I've spent little time on them. While I understand his worries, there is also a downside to that method of operation: the killing opportunities that your employees see. This is of course balanced by the urgency of other matters, which you might notice better than your employees, since you are of course an experienced member of a profitable organization while he is not.

Update to above: colleague spontaneously asked how to do the thing that I proposed. Moral victory. :-)

## Happy

Today I saw a co-worker using a bit of documentation I wrote. Oh yes, time not wasted.

Made by first back-port. Feeling like a pro.

## Impressed first big company

Complexity is so high, that you must use a debugger to step trough the control flow. Everything is an interface, and it is too hard to find what is the implementing class otherwise.

Back-porting is done to several versions. I totally agree with it for large features, but it is hard.

## Impressed when coming from open source

Open source tends to have better tools, because there reducing the barrier of entry is crucial. On enterprises, you get paid, and use whatever your are told.

Since there is no code review and since the release notes are generated from solved issues automatically, minimal commits are not required! Horrendous. Selected changelogs are the only way.

We don't follow SemVer: API breaks can happen on minor versions!

We don't have a nice way of automating tests! There are several repos, and some people start tests on each one manually on by one, and several (like me) have developed their own (bad) personal scripts to help a bit.

## Impressed on B2B

I got assigned the first issue which comes directly from a client, and in particular this one only appears for very large deployments such as theirs. I got surprisingly excited.

I was not used to B2B. On significant end user SaaS, users are counted by the Millions. But on B2B, you may only have a few clients, and each deal has a huge importance to your company. Thus the marketing department will be much larger proportionally.

Many bug reports suck, without any concrete example to reproduce. Because users pay us we have to fix things however they get reported, and because they can call us, the written reports become less important.

On B2B, you sell to company bosses who may have good technical advisors and technical domain knowledge or not. This is already easier than selling to particulars, who have no technical domain knowledge.

People were happy when bosses from the prospect wanted to bypass their own IT department as it made making deals easier. Likely, the local IT departments felt menaced by the externalization of work or were over-confident about their skills (in which my company specialized, but not them).
