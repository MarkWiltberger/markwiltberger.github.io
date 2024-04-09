---
layout: page
title: About
permalink: /about/
---

Coding portfolio site for Mark Wiltberger. I am a software engineer
specializing in web applications.
<br><br>
{%- if site.linkedin_username -%}<a href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg> <span class="username">{{ site.linkedin_username| escape }}</span></a>{%- endif -%}
<br>
{%- if site.github_username -%}<a href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg> <span class="username">{{ site.github_username| escape }}</span></a>{%- endif -%}
<br>
<a href="https://markwiltberger.github.io"><span class="username">MarkWiltberger.github.io</span></a>
