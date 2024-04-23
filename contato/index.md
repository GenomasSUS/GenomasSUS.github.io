---
title: Contact
nav:
  order: 4
---

# {% include icon.html icon="fa-regular fa-envelope" %}**Contato dos Centros Âncoras**


{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/labs/leandro.png"
  caption="Leandro Colli"
%}
{%
  include button.html
  type="phone"
  text="(16) 2101-9366"
  link="+55 16 2101-9366"
%}
{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/labs/michel.png"
  caption="Michel Naslavsky"
%}
{%
  include button.html
  type="phone"
  text="(11) 3091-7966"
  link="+55 11 3091-7966"
%}
{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/labs/adriana.png"
  caption="Adriana Carvalho"
%}
{%
  include button.html
  type="phone"
  text="(21) 98202-4477"
  link="+55 21 98202-4477"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
