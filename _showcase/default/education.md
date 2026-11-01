---
title: Education
group: Education
show: true
width: 12
date: 2025-03-01
---

<style>
  .education-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.95rem;
  }
  .education-table td {
    padding: 10px 12px 10px 0;
    vertical-align: top;
  }
  .education-table td:first-child {
    width: 200px;
    white-space: nowrap;
    font-weight: 500;
    color: #555;
    padding-right: 24px;
  }
  @media (max-width: 575.98px) {
    .education-table tr,
    .education-table td {
      display: block;
      width: auto;
    }
    .education-table td:first-child {
      padding-bottom: 2px;
    }
    .education-table td:last-child {
      padding-top: 0;
      padding-bottom: 18px;
    }
  }
</style>

<div class="white-box">
  <h5 style="font-size: 1.25rem; font-weight: 700; margin-bottom: 1rem;">Education</h5>
  <hr />
  <table class="education-table" aria-label="Education history">
    <tbody>
      {% for item in site.data.profile.education %}
      <tr>
        <td>{{ item.date }}</td>
        <td>
          <strong>{{ item.name }}</strong><br>
          {{ item.position }}
          {% if item.advisor %}<br>Advisor: {{ item.advisor }}{% endif %}
        </td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
</div>
