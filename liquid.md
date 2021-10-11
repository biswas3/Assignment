---
author: Sudip Biswas
layout: demo_template
date: 09-10-2021
---
# Liquid basics

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the 
leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem 
Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

A very good example of liquid syntax is using the **For-loop** statement, like below: 


```

{% for entry in site.data.<dataset> %}
1. {{entry.<column>}} : {{entry.<column name>}}
{% endfor %}

```

It gives the following results:

{% for entry in site.data.titanic %}

1. {{entry.Name}} : {{entry.Age}}

{% endfor %}

