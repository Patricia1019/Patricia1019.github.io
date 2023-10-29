---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Also see my [Google Scholar Profile](https://scholar.google.com/citations?user=f_lK1RYAAAAJ&hl=en).

<table>

<tr>
<td><img class="proj_thumb" src="images/TIP2022graph.png" width="350px" alt=""/>&nbsp;</td>
<td><div class="pub_title"> R<b>ecovering Realistic Details for
Magnification-Arbitrary Image Super-Resolution</b> </div>
<div class="pub_author"> Cheng Ma, <b>Peiqi Yu</b>, Jiwen Lu, Jie Zhou.# </div>
<div class="pub_journal"><i><b>IEEE Transactions on Image Processing</b>, 2022</i> [<a href="https://ieeexplore.ieee.org/abstract/document/9776607">Paper</a>]</div>
</td>
</tr>

</table>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
