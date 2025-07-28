---
layout: default
title: Home
---

<!-- Tabs on top right -->
<div style="display: flex; justify-content: flex-end; gap: 10px; margin-top: 10px; margin-bottom: 30px;">
  <a href="/cv" style="padding: 8px 16px; background-color: #f9f9f9; border-radius: 5px; text-decoration: none; border: 1px solid #ccc;">CV</a>
  <a href="/projects" style="padding: 8px 16px; background-color: #f9f9f9; border-radius: 5px; text-decoration: none; border: 1px solid #ccc;">Projects</a>
  <a href="/talks" style="padding: 8px 16px; background-color: #f9f9f9; border-radius: 5px; text-decoration: none; border: 1px solid #ccc;">Talks</a>
</div>

<!-- Profile header and image on top left -->
<div style="text-align: left; margin-bottom: 30px;">
  <h1 style="margin: 0;">{{ site.author.name }}</h1>
  <p style="margin: 5px 0;">{{ site.description }}</p>
  {% for link in site.social_links %}
    {% if link.title == "GitHub" %}
      <p style="margin: 5px 0;"><a href="{{ link.url }}">View My {{ link.title }} Profile</a></p>
    {% endif %}
  {% endfor %}
  <img src="/assets/20250324_171905.png" alt="{{ site.author.name }}" style="width: 180px; border-radius: 50%; box-shadow: 0 0 8px rgba(0,0,0,0.1); margin-top: 10px;">
</div>

---

## About Me

I'm a computational cognitive science researcher with a background in physics and complex systems, currently pursuing an M.S. in Psychology at Arizona State University. I work in the PALM Lab under the supervision of [Dr. Ben Falandays](https://jbfalandays.com/).

---

## Research Focus

I study the co-evolution of culture and social networks using agent-based modeling and Bayesian approaches to learning and communication. I build large-scale simulations in Julia and Python to investigate how communicative success, category structure, and social connectivity interact over time and shape culture.

My work spans data-driven modeling, sentiment analysis, and network science, with the goal of contributing to theory-building at the intersection of cultural evolution, cognition, and computational social science.

---

## Contact

Feel free to reach out via [email](mailto:your@email.com) 
