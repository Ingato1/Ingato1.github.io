---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
author_profile: true
---
---

---
layout: home
title: "Whitney Ingato Beatrice"
author_profile: true
header:
  overlay_image: /assets/images/header-bg.jpg  # Replace with your image path
  overlay_filter: 0.5
  caption: "Photo credit: [**Your Name**](https://your-site.com)"
excerpt: "My awesome biography constrained to a sentence or two goes here."
feature_row:
  - title: "Blog"
    excerpt: "Read my latest thoughts and articles."
    url: "/blog/"
    btn_class: "btn--primary"
    btn_label: "View Blog"
  - title: "Projects"
    excerpt: "Explore my work and creations."
    url: "/projects/"
    btn_class: "btn--primary"
    btn_label: "See Projects"
  - title: "About Me"
    excerpt: "Learn more about who I am."
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "About Me"
---
# Welcome to My Personal Space! ✨

Hi, I'm **Whitney Ingato Beatrice** - thank you for visiting my site!

## What You'll Find Here
- 📝 **Blog posts** on topics I'm passionate about
- 💻 **Projects** I'm currently working on
- 📚 **Resources** and tutorials I've created
- 👩‍💻 **My professional journey** and background

### Connect With Me
- Follow me on Twitter: [@IngatoIngato4](https://twitter.com/IngatoIngato4)
- Check out my GitHub: [Ingato1](https://github.com/Ingato1)
- Email me: [whitneybeatrice3@gmail.com](mailto:whitneybeatrice3@gmail.com)

---

**Recent Updates**  
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %-d, %Y" }})
{% endfor %}

[View All Posts](/blog/){: .btn .btn--primary}
