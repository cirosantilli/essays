# Asciidoc

Coming from markdown, I've kind of fell in love with Asciidoc for anything that has considerable size, around this time: https://github.com/cirosantilli/linux-kernel-module-cheat/commit/254c8bf42e57bb54a715f151ec31b4c87a119faa

Reasons:

- toc
- custom header, image and table ids and internal links to those ids, but still rendering the human readable title
- header numbering option
- include directives
- you can do everything without indentation, which is hard to type. Nested lists and code blocks notably.
- `link::mycode.c[]` instead of `[mycode.c](mycode.c)`

It takes markdown, and adds just enough to write serious books, while still reducing some markdown annoyances.

Oh, and then I found out that Buildroot, which is a project I love, also uses it. I found that out after thinking about how perfect their docs looked. 

Like any love, it is not perfect:

- escaping stuff is painful. Backslash doesn't work...
  - `C++`
  - inline code: https://github.com/asciidoctor/asciidoctor/issues/2582

but the thorns add to the thrill.

Ciro s2 adoc 2018
