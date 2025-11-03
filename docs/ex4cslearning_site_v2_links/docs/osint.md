---
layout: default
title: OSINT
---

# Day 1 — OSINT (Open Source Intelligence)

<div class="callout"><strong>Goal:</strong> Learn to find and verify public information online using ethical, legal methods.</div>

### What you’ll do
- 🔎 Practice targeted searches and filtering
- ✅ Verify info using at least two sources
- 🏁 Submit answers as flags in CTFd under **OSINT**

<div class="card">
  <h3>Warm‑Up Example</h3>
  <p>Find the official profile for a brand using:</p>
  <ul>
    <li><code>site:instagram.com brandname</code></li>
    <li><code>site:linkedin.com "Brand Name"</code></li>
  </ul>
</div>

### Challenges
1. **Find the About Page** — Locate the “About” or “Contact” page for the sample brand used in class.  
2. **Verify an Address** — Use search results and mapping tools to confirm a city and state. Cross‑check two sources.  
3. **Who Is Hiring?** — Search job boards for any public postings by the brand.

> Submit each answer as a flag in **CTFd → OSINT**.

### Learn more (YouTube)
{% if site.youtube_osint %}
<ul>
  {% for link in site.youtube_osint %}
    <li><a href="{{ link }}" target="_blank">Watch: OSINT resource {{ forloop.index }}</a></li>
  {% endfor %}
</ul>
{% else %}
<p>Add links in <code>_config.yml</code> under <code>youtube_osint</code>.</p>
{% endif %}

**CTFd:** {{ site.ctfd_url }}
