---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

## Teaching Philosophy

The central role of teaching mathematics has always been helping people learn how to think. This involves guiding students to develop both a deep conceptual understanding of mathematical ideas and the ability to reason logically and critically. While specific knowledge may fade over time, the habits of mind cultivated through mathematical thinking can last a lifetime. 

**Essential keywords: order, method, and logic.**

The knowledge may be forgotten, but the way of thinking and understanding will be with the students for their entire life. Ultimately, my goal as a teacher is not merely to transmit knowledge, but to cultivate a mathematical way of thinking that empowers students long after they leave the classroom.

---

## Teaching Techniques

### *Blackboard*

Like many mathematicians, I find the blackboard to be my most valuable teaching tool. In my experience, it remains the most effective medium for presenting mathematics, particularly when developing proofs or explaining abstract concepts. The step-by-step process of writing helps students follow the logical flow and structure of ideas.

### *Modern Technology*

While blackboards excel in fostering understanding, modern technology can complement traditional methods by offering clarity and structure. For example, slides are useful for visual summaries or organizing complex content. I’ve also found tools like **Jupyter Notebooks** especially effective in courses such as *Numerical Analysis* or *Scientific Computing*, where the combination of code, visualization, and explanation enhances student engagement and understanding.

---
# Teaching Experience

{% for post in site.teaching reversed %}
  {% include archive-single-teaching.html %}
{% endfor %}
