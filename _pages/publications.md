---
layout: page
permalink: /publications/
title: Publications
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}
<div class="publications">



{% bibliography --template bib %}

</div>

<!-- Fix: Only show one "Working Manuscripts" heading per year -->
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const shownYears = new Set();
    document.querySelectorAll('.working-header').forEach(el => {
      const year = el.getAttribute('data-year');
      if (shownYears.has(year)) {
        el.style.display = 'none';
      } else {
        shownYears.add(year);
      }
    });
  });
</script>
