---
layout: default
title: Configuration
nav_order: 2
---

<button class="btn js-toggle-dark-mode">Toggle dark mode</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Toggle dark mode';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Toggle light mode';
  }
});
</script>

# The Title
{: .no_toc }

{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---



