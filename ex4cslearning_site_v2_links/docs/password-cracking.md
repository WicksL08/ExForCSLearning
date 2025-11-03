---
layout: default
title: Password Cracking
permalink: /password-cracking
---

# Day 2 — Password Cracking (with Hashing Concepts)

<div class="callout"><strong>Goal:</strong> Understand hashes, why passwords aren’t stored in plain text, and how attackers attempt guesses.</div>

### Key ideas
- 🔐 A **hash** is one‑way: <code>password → hash</code>
- 🧮 Sites store **hashes**, not raw passwords
- 🧰 Attackers try dictionaries or brute‑force to match a hash

### Try it (Safe Lab)
1. Download the sample hash file from CTFd (on the challenge page).  
2. Use the provided wordlist and instructions in a sandboxed environment.  
3. Submit the recovered **flag** in **CTFd → Password Cracking**.

> Ethics: Never attempt to crack real accounts. This is a closed, educational exercise.

### Learn more (YouTube)
{% if site.youtube_password %}
<ul>
  {% for link in site.youtube_password %}
    <li><a href="{{ link }}" target="_blank">Watch: Passwords & Hashing {{ forloop.index }}</a></li>
  {% endfor %}
</ul>
{% else %}
<p>Add links in <code>_config.yml</code> under <code>youtube_password</code>.</p>
{% endif %}

**CTFd:** {{ site.ctfd_url }}
