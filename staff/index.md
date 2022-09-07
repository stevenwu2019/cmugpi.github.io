---
layout: page
title: Staff
group: navigation
order: 5

# -- This is a test comment
# -- yaml variables local to this file --
staff:
  - id: aluque
    domain: andrew
    name: Alvaro Luque
  - id: avantikn
    domain: andrew
    name: Avantika Naik
  - id: daphneh
    domain: andrew
    name: Daphne Han
  - id: dsunkara
    domain: andrew
    name: Deepti Sunkara
  - id: jdai2
    domain: andrew
    name: Jessica Dai
  - id: jpyang
    domain: andrew
    name: Jules Yang
  - id: ktummala
    domain: andrew
    name: Kavya Tummalapalli
  - id: kbooker
    domain: andrew
    name: Kyle Booker
  - id: ljyao
    domain: andrew
    name: Laura Yao
  - id: lghuang
    domain: andrew
    name: Len Huang
  - id: linmo
    domain: andrew
    name: Lin Mo
  - id: maggieca
    domain: andrew
    name: Maggie Cai
  - id: sarahc2
    domain: andrew
    name: Sarah Chen
  - id: stevenwu
    domain: andrew
    name: Steven Wu
  - id: tcortina
    domain: cs
    name: Tom Cortina
  - id: vpeet
    domain: andrew
    name: Veronica Peet
---

# Staff
{:.ui.dividing.header.no_toc}

For general questions/comments, please post on the course Piazza. Only send an
email to a specific TA if you have a question that wouldn't be appropriate to
send to the whole course staff. 

<div class="ui three column center aligned grid">
{% for person in page.staff %}
<div class="column">
<img class="ui rounded image" alt="{{ person.id }}" width="100%" src="{{ site.baseurl }}/images/staff/{{ person.id }}.jpg">


## {{ person.name }}

{{ person.id }} at {{ person.domain }}

</div>
{% endfor %}
</div>

# Office Hours
{:.ui.dividing.header.no_toc}

Up-to-date information on office hour times and locations may be found on [Google Calendar][ohtimes] or the embedded google calendar on the homepage.


# Attribution
{:.ui.dividing.header.no_toc}

The initial version of the course and a significant amount of the current course
content was created by [Adam Blank][adam] in Fall 2011. Later, modifications and
additions to the content were made by Josh Zimmerman, who reformatted the
original PDFs into web content.

The current version of the site, including the site layout and design as well as
further modifications and additions to content, was written by [Jake
Zimmerman][jake] with contributions from the GPI staff.

The source of this site is licensed under the MIT License and is readily
[available on GitHub][cmugpi]. It uses Jekyll and Octopress 3.0 for static site
generation and Semantic UI as a general purpose CSS framework. If you enjoyed
this site, be sure to star it! If you notice an issue or bug with the site,
feel free to open an issue or a pull request.

[adam]: http://www.countablethoughts.com/
[jake]: https://jez.io/
[cmugpi]: https://github.com/cmugpi/cmugpi.github.io
[ohtimes]: https://tinyurl.com/f22-gpi-oh
