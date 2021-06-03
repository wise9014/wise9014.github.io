## Welcome to Bill's Page

This is my location to document my thoughts, research, and observations. Please click one of the links below if you are interested in reading my bio, a d

### Page Directory
<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

### Inspiration, ΥΓΕΙΑ, and Intuition

![The Perspective of Nature](/Slate_Valley.jpg)
```

### Contact

If you would like to contact me, please don't hesitate to email me at:
wise9014@colorado.edu

### Post Directory
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>