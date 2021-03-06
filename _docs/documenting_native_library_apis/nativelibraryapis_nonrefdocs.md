---
title: "Create non-ref docs with native library APIs"
permalink: /nativelibraryapis_nonrefdocs.html
course: "Documenting REST APIs"
sidebar: docapis
weight: 11.8
section: nativelibraryapis
path1: /nativelibraryapis.html
---

Although much attention tends to be given to the reference documentation with APIs, actually the bulk of what technical writers usually do with native library API docs is provide [non-reference documentation](docnonref.html). This is the content that engineers rarely write.

Engineers will throw a quick description of a class in a file and generate a Javadoc, and they'll give that Javadoc to the user as if it represents a complete set of documentation, but reference docs don't tell even half the story.

{% if site.format == "web" %}
* TOC
{:toc}
{% endif %}

## Reference docs can be an illusion for real doc

[Jacob Kaplan Moss says](http://jacobian.org/writing/what-to-write/) that reference docs can be an illusion:

>… auto-generated documentation is worse than useless: it lets maintainers fool themselves into thinking they have documentation, thus putting off actually writing good reference by hand. If you don't have documentation just admit to it. Maybe a volunteer will offer to write some! But don't lie and give me that auto-documentation crap. – Jacob Kaplan Moss

{% include random_ad.html %}

Other people seem to have similar opinions. In general, document generators don't tell you a whole lot more than you would discover by browsing the source code itself. Some people even refer to auto-generated docs as a glorified source-code browser.

## Reference docs are feature-based, not task-based
One of the main problems with reference documentation is that it's feature based rather than task based. It's the equivalent of going tab-by-tab through an interface and describing what's on each tab, what's in each menu, and so on. We know that's a really poor way to approach documentation, since users organize their mental model by the tasks they want to perform.

{% include random_ad2.html %}

When you write API documentation, consider the tasks that users will want to do, and then organize your information that way. Reference the endpoints as you explain how to accomplish the tasks. Users will refer to the reference docs as they look for the right parameters, data types, and other class details. But the reference docs won't guide them through tasks alone.
