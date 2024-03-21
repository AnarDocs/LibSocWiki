---
title: Template:Navbox doc
permalink: /Template:Navbox/doc/
---

Description
This template is used to create a basic navigation box. You can do so by
calling the template, via the steps under "Syntax", but it is
recommended to **copy the code verbatim** via the steps under "Navbox
Creation".

Navbox Creation

<createbox> prefix=Template: preload=Template:Navbox
editintro=Template:Navbox/doc buttonlabel=Make your navbox! default =
Navbox Foo </createbox>

1.  Think of a name for your navbox, like "Navbox Foo". Type it in the
    above field, press the button, and save the page immediately. Be
    ready to return to *this* page to see the rest of the instructions.
2.  Edit the resulting page in source mode.
3.  Replace with the text you would like to appear in the header.
4.  Replace with the text you would like to appear in the body.
5.  To add another section, copy these four lines of code immediately
    below the lines in the existing code that they resemble:

<!-- -->

    |-
    ! style="padding:0.2em 0.5em;" nowrap="nowrap" class="color1" | {{{header}}}
    |-
    | style="padding:0.2em 0.5em;" | {{{body}}}

Save the page once you have added as many sections as you needed, and
filled them with content. You may also want to create a /doc subpage
explaining that to call the resulting template, one must only type
`{{Navbox Foo}}`, or rather, whatever we decided to name the template in
step 1.

Syntax

<!-- -->

    {{navbox
    |header=Land of Bob
    |body=This <nowiki>[[place|place]]</nowiki> and that <nowiki>[[place|place]]</nowiki>.
    }}


Results in...

<includeonly></includeonly><noinclude></noinclude>

[](Category:Templates "wikilink")
[](Category:Templates/Navbox "wikilink")
[](Category:Template_documentation "wikilink")