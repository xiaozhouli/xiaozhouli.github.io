---
layout: archive
title: "Courses Taught"
permalink: /teaching/courses/
author_profile: true
---

{% include base_path %}

This page provides an overview of all the courses I have taught, followed by a detailed listing organized by academic year and semester.  The courses span different levels, including core undergraduate subjects and advanced elective topics.

Please note:
* Courses with English titles were delivered in English.
* Courses with Chinese titles were taught in Chinese.

Course materials and resources (such as lecture notes, slides, etc.) are available via the links associated with each course.

Note: This website has been migrated from a previous server due to unforeseen circumstances. As a result, some course resources may have been lost, and certain links may be temporarily inaccessible. Content is being restored progressively.

---

## Master/PhD Courses

* Numerical Solutions of Partial Differential Equations
* 数值分析 
* Introductions to Differential Equations 
* Numerical Methods for Ordinary Differential Equations

## Undergraduate Courses

* Probability and Statistics
* Calculus I & II
* Linear Algebra and Space Analytic Geometry
* 计算：第三种科学方法
* 数值分析
* 计算方法

## Short Courses/Seminar Courses/Projects

* Isogeometric Analysis
* Finite Element Methods
* Spectral Methods
* Nodal Discontinuous Galerkin Methods
* Numerical Methods for Conservation Laws
* GPU Implementation of the Parareal parallel-in-time Method

---

# Teaching by Semester

{% for post in site.teaching reversed %}
  {% include archive-single-teaching.html %}
{% endfor %}
