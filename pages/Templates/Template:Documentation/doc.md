---
title: Template:Documentation doc
permalink: /Template:Documentation/doc/
---

## Description

This template is used to insert descriptions on template pages.

## Syntax

Add `<noinclude>``</noinclude>` at the end of the template page.

Add `<noinclude>``</noinclude>` to transclude an alternative page from
the /doc subpage.

## Usage

### On the Template page

This is the normal format when used:

    TEMPLATE CODE<includeonly>Any categories to be inserted into articles by the template</includeonly><noinclude>
    {{documentation}}</noinclude>

*If your template is not a completed div or table, you may need to close
the tags just before `{{documentation}}` is inserted (within the
noinclude tags).*

*A line break right before `{{documentation}}` can also be useful as it
helps prevent the documentation template "running into" previous code.*

### On the documentation page

The documentation page is usually located on the /doc subpage for a
template, but a different page can be specified with the first parameter
of the template (see [Syntax](#Syntax "wikilink")).

Normally, you will want to write something like the following on the
documentation page:

    ==Description==
    This template is used to do something.

    ==Syntax==
    Type <code>{{t|templatename}}</code> somewhere.

    ==Samples==
    <code><nowiki>{{templatename|input}}</nowiki></code>

    results in...

    {{templatename|input}}

    <includeonly>Any categories for the template itself</includeonly><noinclude>[[Category:Template_documentation|{{PAGENAME}}]]</noinclude>

Use any or all of the above description/syntax/sample output sections.
You may also want to add "see also" or other sections.

Note that the above example also uses the
[Template:T](Template:T "wikilink") and
[Template:T/piece](Template:T/piece "wikilink") templates.

<includeonly></includeonly><noinclude></noinclude>

[](Category:Templates "wikilink")
[](Category:Template_documentation "wikilink")