---
title: Grading Criteria
subtitle: Exercise Feedback
layout: default
---
|% Earned | Criterion 1 Feedback | Criterion 2 Feedback |
|---|---|---|
{% for feedback in site.data.simple-assignment-default-feedback %}

|{{ feedback.percent-earned }}|{{ feedback.criterion-1-feedback }}|{{ feedback.criterion-2-feedback }}|
{% endfor %}

{% include feedback.md %}
