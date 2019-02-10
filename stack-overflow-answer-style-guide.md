# Stack Overflow answer style guide

When this gets good enough, post at: https://meta.stackexchange.com/questions/18614/style-guide-for-questions-and-answers

**Use bold for title-like structs**

E.g.:

    **Subsection**

    Bleble.

    **Another subsection**

    Blabla.

Don't use headers as they are too large, and don't generate any link IDs anyways...

Don't use bold anywhere else, otherwise readers will have a time finding the subsection titles.

**Start every answer with a title**

Summarizing the key part of the answer:

    **Minimal runnable example**

**Theory and experiment**

The perfect answer often contains both:

-   experiments: concrete examples you have run to verify that you understood the theory

-   theory: for most programming questions, this means a quote from canonical standards, documentation, or source code

    Provide the exact version of the documentation, ideally with a link to it, and quote the most relevant paragraphs in the answer.

The experiment should come first, that is the better way to teach something to humans.

**Extremely concrete experiments**

If the answer contains an experiment, provide:

- full runnable code
- full commands used
- expected output

and only then start explaining why the expected output happened.

**Tested with**

If you did any experiments, add a "Tested with:" section at the end of your answer, so that others will know how to reproduce your results.

This should include:

-   your distro version

-   the version of key utilities used in the answer

    While this is implied from Ubuntu version for example, it still saves readers some time.

E.g.:

    Tested on Ubuntu 18.04, GCC 8.2.0.

It is true that Ubuntu patchlevel versions e.g. `18.04.2` may change those versions further, and you can also get even more precise package information from `dpkg -l` e.g.:

    8.2.0-7ubuntu1

but I think it is reasonable to omit this level of detail as it is likely too much for most users.

If you have tested different sections with different OSes, add the tested with line for each section instead of at the end of the answer.

**Files**

Represent files and their names as:

    main.c

        int main(void) {
            return 1;
        }

    another_file.c

        int myvar = 0;

**Images**

If input / output images are involved in the answer, provide them.

Relevant images are fun and intuitive!

Videos are also good! They can be represented with GIFs, see:

- https://askubuntu.com/questions/648603/how-to-create-an-animated-gif-from-mp4-video-via-command-line/837574#837574
- https://unix.stackexchange.com/questions/24014/creating-a-gif-animation-from-png-files/489210#489210

If a diagram would help, also consider some ASCII art.
