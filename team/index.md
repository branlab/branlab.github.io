---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include icon.html icon="fa-solid fa-users" %}Team
{% include section.html %}

Lead
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}

Postdocs
{% include list.html data="members" component="portrait" filter="role"=='postdoc'" %}

{% include section.html %}

PhD Students
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include section.html %}

Affiliated Members
**Istvan Kiss, Northeastern University London

{% include section.html %}

External Members
**Thomas Eisermann, University of Lisbon, Lisbon, Portugal
**Ricardo de Carvalho, University of Lisbon, Lisbon, Portugal
**Miguel Gonzalez-Casado, Universidad Carlos III, Madrid, Spain
**Elena Candellone, Utrecht University, Utrechth, Netherlands
**Fernando Diaz-Diaz, Universidad Carlos III, Madrid, Spain
{% include section.html %}

Alumni
{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}
