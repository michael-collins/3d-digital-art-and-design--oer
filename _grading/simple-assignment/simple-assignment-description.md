---
title: Grading Criteria
subtitle: Exercise Feedback
layout: default
---

| % Earned | Criterion 1 Feedback | Criterion 2 Feedback |
|---       |---                   |---                   |
{% for feedback in site.data.simple-assignment-default-feedback %}
  | {{ feedback.percent-earned }} | {{ feedback.criterion-1-feedback }} | {{ feedback.criterion-2-feedback }} |
{% endfor %}

| % Earned | Criterion 1 Feedback | Criterion 2 Feedback |
|---       |---                   |---                   |
|test      | test2                |test  3               |

<table class="feedback">
  <tr class="table-labels">
    <td class="table-label">% Earned</td>
    <td class="table-label">Criterion 1 Feedback</td> 
    <td class="table-label">Criterion 2 Feedback</td>
  </tr>
{% for feedback in site.data.simple-assignment-default-feedback %}
  <tr class="feedback-data">
    <td>{{ feedback.percent-earned }}</td>
    <td>{{ feedback.criterion-1-feedback }}</td> 
    <td>{{ feedback.criterion-2-feedback }}</td>
  </tr>
{% endfor %}
</table>
