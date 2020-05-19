---
layout: default
bodyClass: page-home
title: Katamari Restaurants of Cambridge and Somerville
displayTitle: " "
excerpt: >
  A summary of the running loss of local restaurants to deep-pocketed private 
  equity and national chains.
style: |
  .blocktable {
    table-layout: fixed;
  }
  .blocktable thead th {
    text-align: left;
  }
---

# Katamari Restaurants of Cambridge and Somerville

_A summary of the running loss of local restaurants to deep-pocketed private 
equity and national chains._

When $2T-$6T of freshly-printed government-guaranteed low-cost credit goes to
deep-pocketed private equity firms, transnational corporations, big banks,
investors and monopolists, we'll quickly see the biggest loss of local 
restaurants to national chains.

This will fundamentally reshape the terrain of independenly run restaurants in 
the US and around the globe. The Urban America we know, of heterogeneous small 
restaurants would look very different after this pandemic is over&mdash;a 
homogeneous space optimized for massive corporations, and reducing local 
autonomy and diversity.

## The List

<table class="blocktable">
  <thead>
    <th scope="column" width="30%">Name</th>
    <th scope="column" width="20%">Date</th>
    <th scope="column" width="10%">URL</th>
    <th scope="column" width="10%">
      <abbr title="Replaced by">Replacement</abbr>
    </th>
    <th scope="column" width="30%">Notes</th>
  </thead>
  <tbody>
   {% for item in site.data.companies %}
     {% assign key = item[0] %}
     {% include company-row.html key=key %}
   {% endfor %}
  </tbody>
</table>
