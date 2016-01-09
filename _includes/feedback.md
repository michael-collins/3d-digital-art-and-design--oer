

#Feedback

| % Earned| Criterion 1 Feedback | Criterion 1 Feedback |
|--- |:---:|---:|
{% for feedback in site.data.simple-assignment-default-feedback %}
| {{ feedback.percent-earned }} | {{ feedback.criterion-1-feedback }} | {{ feedback.criterion-2-feedback }} |
{% endfor %}

<table style="width:100%">
  <tr>
    <td>% Earned</td>
    <td>Criterion 1 Feedback</td> 
    <td>Criterion 2 Feedback</td>
  </tr>
{% for feedback in site.data.simple-assignment-default-feedback %}
  <tr>
    <td>{{ feedback.percent-earned }}</td>
    <td>{{ feedback.criterion-1-feedback }}</td> 
    <td>{{ feedback.criterion-2-feedback }}</td>
  </tr>
{% endfor %}
</table>