# How to become a good programmer

General high level tips on how to become a good programmer.

First read [how to learn](how-to-learn.md): those techniques apply to any field of knowledge.

For a huge list of free programming resources, see: <https://github.com/vhf/free-programming-books>

## How to type

- user four fingers
- use closes finger
- look at the screen
- use keyboard shortcuts and good programs that have them (ex: Vim)

Saves time and preserves your arm.

## Make cheatsheets

Everything you learn, write it down! You will forget it later.

If there is a good link or book, save the link or the book page.

Publish your cheats so that others can use them too.

Always use correct grammar, and make things as understandable as possible.

### Write assertion cheatsheets

Whenever possible, write tutorials in code and assert automatically wherever possible.

Good:

    assert(1 + 1 == 2);

Bad:

    printf("%d", 1 + 1);

### Split cheatsheets into small files

You will be tempted at first to write on single big file.

While it is convenient to write, it is horrible to read, because programming languages are not books, and have no method to add indexes and tables of contents.

So start right:

- split it up into small files, each teaching a single small concept
- make a `README.md` file which with links to all the concepts in the good order that they should be learned

## Self advertising

Besides being good, you also have to convince people of it so that you can get better jobs and achieve your goals.

Make a web page containing:

- a list of you open source contributions: <http://www.cirosantilli.com/contrib/>
- a self evaluation of your knowledge: <http://www.cirosantilli.com/self-evaluation/>

Always search accounts / blogs of who makes software you like: they are potential teammates or supporters.

### Consistent public image

Use the same photo, username and header image on *every* account.

Link to your web page from every account that allows it.

Get a domain name based on your name, e.g. `cirosantilli.com`.

### Stack Overflow

Use it. Contribute to it. Two valid methods:

-   when you are researching something, and you find an old question that does not have the perfect answer, create the perfect answer.

-   monitor tags that you love.

    Don't monitor overly generic tags like programming languages: too many people do that, and all new questions are duplicates or off topic.

    Instead, choose niche tags, most often programming *projects* which you are working on. Very few people know about a given project, and it is there that you can really help new users.

### GitHub

Use it.

Upload *every* line of code or text you write. Including school assignments after the deadline.

Gains:

- don't ever lose a line of code again
- allow the hole world to find your code
- force yourself to write better code because it is public

Write perfect READMEs and repository descriptions. Good content is useless if people cannot:

- find it
- get started in 10 seconds

### Project divulgation methods

You have to tell people about your projects, or else they will never find them.

There is a fine line between spam and divulgation, so make sure that you post the links on very closely related threads.

The best methods are:

- Reddit. Either on new threads, or commenting on strictly related threads
- Hacker News. Featureless Reddit, very popular.
- Twitter. More personal. Keep low tweet volume to not bore your followers.
- Stack Overflow. If your question / answer requires a multi-file input to try it out, a `git clone` will be easier for other people, and it will often fit in a cheatsheet repository.

<http://danluu.com/blog/archives/popularity/> says the order of importance is Hacker News / Reddit / Twitter / Google search.

### Open source

Find applications that interest you and improve programs.

### Improvement suggestions to closed source

Whenever you find a typo or missing feature on a closed source project, make a suggestion on their tracker / email contact.

I have received a few invitations for job interviews like that.

### Prestigious projects

Contribute to prestigious projects:

- it is more likely that the project will live on and that your changes will continue to be useful
- you will learn from better coders
- you will get more visibility

"Low level" tools are the most useful for large enterprises that need to optimize at low level:

- Kernel and hardware interfacing: file systems, networking, GPUs
- assembly
- databases
- cryptography
- compilers, interpreters and standard libraries: GCC, Python, Node.js. Garbage collection internals.
- Media: formats (websites, audio, videos, images), compression algorithms, viewers (browsers, image viewer, etc.)
- Git
- formal algorithm verification: <https://en.wikipedia.org/wiki/Formal_verification>, <http://frama-c.com/>
- anything that requires knowing mathematics
- formal proof systems <https://en.wikipedia.org/wiki/Formal_proof> <https://en.wikipedia.org/wiki/Coq>

Pay huge attention to **security**. Hard to get right, and a single error can cost millions.

### Analytics

Whenever one person somehow notices you and views your profile, try to discover where this person found you.

If often happens that someone has shared your content.

On your personal webpage, use Google Analytics.

On GitHub, use `/graphs/traffic` whenever you get an upvote for a low voted repository.

Keep public track of all sources that mentioned you. On GitHub, I often use the repository wiki for that.

## TODO list

Maintain a file with a TODO list.

Whenever you have a new idea, or want to learn something, do the following:

- can it be done in 5 minutes? Do it now.
- otherwise, add it to the TODO

Put most important things first on the file. When you do them, delete the entry.

## Standards

When you start learning something, immediately start trying to understand its standards.

Download the documentation, learn where to find all its versions online. Try to understand it as early as possible while you go through tutorials.

### Portability

Following standards gives you portability.

Always try to use the least dependencies possible on backwards compatible standards. E.g., if you can do something easily in C89, why use C99 for a few language features? C89 gives you Windows compilation!

### Style guides

Find the most famous style guides if applicable. They are often from big companies. Many technologies offer multiple ways to do things. Learn from the start which one is the best in general.  Also great way to learn new features. E.g.: [Google](http://google-styleguide.googlecode.com/), [GitHub](https://github.com/styleguide), [Thoughbot.inc](https://github.com/thoughtbot/guides).

### Implementation state

What is the state of implementations? Are they consistent with one another? Are they updated. Example:

- standard: W3C HTML or CSS
- semi-compatible implementations: browsers: Firefox, Chrome, IE

### Standard extensions

What are the most important extensions to the standard? How portable are they? Examples:

- ANSI C vs POSIX vs GNU extensions

## Minimal test cases

This is a common mistake amongst beginners. You have a problem that has 2 parts.

When debugging, try hard to reduce the problem to the minimal number of parts possible.

This hugely increases the probability that you will find a solution, and if you don't and ask a question on a public forum, this hugely increases the likely utility of the question for further readers.

There is even a website dedicated to explaining that to newbs that you can link to: <http://sscce.org/>

## Backups

Do them periodically (Deja Dup) on material you generated (not large things you downloaded).

Use a dedicated home partition.

Use a dotfiles on GitHub.

## Tools

General tools and applied topics which you should consider learning.

But do not forget: algorithms are as important than tools, since a single algorithm can be used by one thousand tools. The ideal is to take a middle path and learn both at the same time:

- learn the tools first to see how things are useful
- learn the theory to see why the tool is made that way, how to improve it, and what are it's theoretical limitations

### Where tools come from

Tools are not magic esoteric objects given by God to man.

Every piece of software has been code by some human at some point in time.

Understanding where the tool comes from, who created it, in which package it is distributed, can give you great insight about what it does.

Whenever you use a command line utility on Ubuntu, check what package it comes from.

### OS choice

Use Linux.

It's free.

There are many more open source projects than in Linux that you can contribute to and become famous.

Learn about POSIX: <https://github.com/cirosantilli/linux/tree/master/posix>

### Languages

#### Programming

Learn:

-   first C and C++. Gives you valuable low-level insight, widely used in fundamental tools like:

    - Linux and Windows kernel
    - POSIX API
    - interpreters of all major languages: Python, Ruby, Perl
    - MySQL
    - Git

    Even today, when people have a library which they want to run fast and portably on every language, what they do is implement it in C and let other languages bind to it, including in the web development domain. E.g.:

    - <https://github.com/libgit2/libgit2> and <https://github.com/libgit2/rugged>
    - <https://github.com/sass/libsass> and <https://github.com/sass/node-sass>

-   a weakly typed interpreted language, either Python or Javascript (Node.js)

Considerations:

-   Most popular? Hard to say

-   Niches matter. Some languages dominate certain application spaces.

    - PHP, Ruby, JavaScript == web
    - Fortran == numerical

-   All major programming languages have the same theoretical power as they are Turing complete.

-   Categories:

    -   Compiled vs interpreted (virtual machine) non compiled languages.

        Speed vs multiplataform, quick test, prototyping.

        There is no hard distiction: any compiled language could also be interpreted and vice versa.

        It is mainly a question of design: some langs are designed to be interpreted.

        Haskell for example can be compiled but also comes with a standard [REPL] interface.

    -   Objects oriented vs non object oriented.

    -   Type systems:

        - statically vs dynamically typed
        - weakly vs strongly typed

-   Languages are easy, libraries are hard.

    Languages are easy to learn because they are all very similar.

    Library interfaces however are not, because they involve completely different concepts between one another.

    Therefore: if a project does what you want in a language you don't know

    - learn that language!
    - **don't** recode the project!

#### Data languages

- XML
- JSON

#### Markup languages

- HTML
- LaTeX
- Markdown

### Language tools

Once you have chosen a language, there is a standard set of tools that you need to learn to work with the language:

- the compiler and interpreter. Learn the options from the command line.
- build system and package manager. E.g.: `make` for C++, Rake and Bundler for Ruby, etc.
- IDE. Only use once you can compile from the command line.
- lint tool: checks your style and code smells
- coverage tool: checks how much of your code is covered by your tests

### Web development

-   HTML

-   HTTP

-   CGI

-   Apache configuration

-   CSS

-   JS

-   MySQL

-   PHP

-   the other interpreted CGI languages:

    - Python
    - Ruby
    - Perl

-   real deployment

    - FTP
    - deal with permissions you lack on server
    - ssh

#### Multiple browsers

Have at least two browsers, one main where you are logged in all your websites,
and one secondary, which you will use to see how other users see your profiles.

Same goes for web development: have multiple browsers to quickly switch users.
Also good practice as it lets you see often how the website renders under different browsers.

For websites that allow you limited unsigned entry, have a third browser to test as unsigned.

E.g. on Ubuntu 12.04 I run Firefox (primary), Chromium (secondary) and Chrome (unsigned).

### Filesystem

One of the first things you should understand better as a programmer is your filesystem.

-   home dir

-   upper vs lower case

-   naming conventions

    - bin

    - `~` and `.bak`

    - doc

    - dot hidden

    - lib

    - src

    - include

    - share

    - local

    - and the rest of the Linux Filesystem Hierarchy Standard
        <http://www.tuxfiles.org/linuxhelp/linuxdir.html>

-   do not start filenames with hyphen so as not to conflict with command line options.

-   symlinks vs hardlinks, and other pseudo files like Windows / XDG desktop shortcuts

### Databases

- MySQL
- SQLite

### Important programs for life

-   dropdown terminal emulator: Guake.

-   Vim

    Text editor.

-   Krusader

    File manager.

-   Source version control.

    You need to contribute with others.

    Most commonly used:

    - Git. Dominates web development.
    - SVN. Still popular for scientific applications.

-   make (Makefile)

    Automate compilations.

    <http://www.jfranken.de/homepages/johannes/vortraege/make_inhalt.en.html>

-   Bug trackers, like GitHub built-in one. **Always** use one for your project!

-   Virtual machines. VirtualBox + Vagrant are game changing.

-   ack (find/grep replacement)

    Find in files.

#### Shell

-   Each terminal can run one ore more languages. The most important ones are:

    - Linux: bash
    - windows: cmd

-   Terminal: the little window that runs a shell language and lets you interact with it.

    Many terminals can be used for a single language, e.g., both `xterm` and `guake` are bash interfaces.

    Pros:

    - easy to explain to other people precisely what to do
    - faster than clicking 50 times on a GUI
    - less prone to interface changes

    Con: cannot show images.

    Conclusion: always use it unless you *need* images.

-   Bash:

    - pro: super easy file/pipe/process handling
    - con: insane, slow

    Use for one liners only. Replacements:

    - Perl is dead, but golfs really well.
    - Python! Also useful for other things, so worth learning

-   directory structure, home directory

-   fundamental tools: `ls`, `cd`, `mkdir`, `cp`, `rm`, `rmdir`, Ctrl+Z, `bg`, `find`, `grep`

-   command line option common standards.

    GNU:

    -   Single dashed options can only have a single letter

    -   Single dashed options without arguments can be combined: `-ab` equals `-a -b`.

    -   Parameters are passed just after the arguments, e.g.: `compile --output output-file input-file`

        Most options take a single parameter.

        The last arguments can be a long list.

    -   Most options have both a double and single dashed version

    Subcommands are sometimes used to break up very complex utilities: e.g.: `git add`, `git rm`, etc.

    Not all programs follow GNU guidelines, but you should.

-   `--help`, how to read CLI interface specification `[]`, `...,`, `man`, `info`, `--version`.

-   stdin/stderr/stdout:

    - three holes
    - pipes `>` to file, `|`, `1>&2`

-   exit status

-   pipe (help grep example)

-   interactive vs. non-interactive

### Assembler

Understand exactly what operations a processor can do.

<http://www.bottomupcs.com/>

### Data representation

#### character representation

Understand:

- ASCII
- Unicode
- UTF8

#### Integer representation

-   binary, hexa

-   signed

    - one's complement
    - 2-complement

#### Float representation

Understand how floating point numbers are represented.

### IPC

### Concurrency

### Multithreading

-   thread vs process.

    A process can contain many threads.

    Threads share a memory space, process don't.

-   IPC.

    - pipes : same machine

    - sockets : different machines

        - internet
        - PCI
        - USB

### Operating systems

You must learn how your operating system works.

The only operating system you can really understand is Linux since it is open source,
so understand Linux.

Topics which you should look into:

#### Program memory space

Address, operational system division:

-   <www.dirac.org/linux/gdb/02a-Memory_Layout_And_The_Stack.php>

#### Driver programming

- <http://www.linuxjournal.com/article/7353> Control a lamp. Contains C code.

- <http://www.freesoftwaremagazine.com/articles/drivers_linux>

#### Executable files

ELF files, including libraries

### Hardware

-   Memory: registers vs caches vs RAM vs ROM (BIOS) vs VRAM vs HD.

    <http://arstechnica.com/gadgets/2002/07/caching/2/>

    Deep explanation.

-   Buses: <http://computer.howstuffworks.com/pci1.htm>

### Optimizing code

More important than those are to first:

- use best algorithm

- compile instead of interpret

A few important ones are:

- cache: <http://en.wikipedia.org/wiki/CPU_cache>

- speculative execution <http://en.wikipedia.org/wiki/Speculative_execution>

- loop unwinding: <http://en.wikipedia.org/wiki/Loop_unwinding>

- out of order execution: <http://en.wikipedia.org/wiki/Out-of-order_execution>

- register renaming: <http://en.wikipedia.org/wiki/Register_renaming>

### Automatic optimization

-   branch prediction

    <http://en.wikipedia.org/wiki/Branch_predictor>

    An example of perceptible branch prediction:

    <http://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-an-unsorted-array>

### GPU programming

TODO

### SemVer

### Semantic versioning

Popular standard for program versioning <http://semver.org/> formalized by Tom Preston-Werner.

## Licenses

Learn about licenses.

I'm an open source addict and pro copyleft, so I basically use GPL, AGPL or CC BY-SA.

I'm against licenses that are too free like BSD and MIT: if people are going to use your work, better force them to merge back stuff, otherwise you and society get nothing in return. And believe it: enterprises care only about money, and they *won't* give anything back unless forced to.

Another advantage of copyleft is that you are able to sell what you produce if someone really wants to fork it. E.g. MySQL.

## Philosophy

### Programming and ideas

    ideas (that can be programmed)
    +
    programming
    ------------------------------
    *power*

- without ideas, programming is useless!
- without programming, some ideas are useless!

### Imperfection

It is the work of a programmer to search perfection, while accepting that imperfection is inevitable.

When in doubt, look, decide, and follow your decision all the time, knowing that all other choices are also imperfect.

### Design patterns

Learn from the Zen of Python <http://legacy.python.org/dev/peps/pep-0020/>. The following resonate on my mind every week:

-   Flat is better than nested.

-   There should be one, and preferably only one, obvious way to do it, although that way may not be obvious at first unless you're Dutch (Python's creator is Dutch). Ruby disagrees:

        if not true

        unless true

-   Explicit is better than implicit.

### Architecture

Very high level application organization.

Important, but hard to learn and to formalize.

<http://aosabook.org/en/index.html>, <https://github.com/aosabook/500lines>.

### Human factors

Unfortunately, even as a programmer you still have to deal with humans, those unpredictable and hard to optimize systems.

Artistic level:

-   coworkers

-   clients

-   market

-   <http://www.joelonsoftware.com/>

    Quite a few strategy articles.

    E.g.: Microsoft employee, lots of exp.

## Find the people you need

-   Whenever you see someone hardcore on any forum like Stack Overflow / GitHub, check out their profile, website and LinkedIn.

-   Pay huge attention to:

    - Industry groups
    - Conferences

    Those will group the most interesting people of each domain that matters.

    Stay away from flashy consumer oriented confs, and look into hardcore dev confs.

