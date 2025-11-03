---
layout: default
title: Cryptography
---

# Day 3 — Cryptography (Ciphers & Keys)

<div class="callout"><strong>Goal:</strong> Learn the difference between encryption and hashing, then practice with classic ciphers.</div>

### Quick primer
- 🔑 **Encryption**: reversible with a key
- #️⃣ **Hashing**: one‑way, for integrity
- ✍️ **Signatures**: authenticity with asymmetric keys

### Challenges
1. **Caesar Shift** — Decrypt the message using a shift of 7. Submit the plaintext as the flag.  
2. **Vigenère Key Hunt** — A clue on this page hides the key. Find it and decrypt the message.

### Learn more (YouTube)
{% if site.youtube_crypto %}
<ul>
  {% for link in site.youtube_crypto %}
    <li><a href="{{ link }}" target="_blank">Watch: Cryptography {{ forloop.index }}</a></li>
  {% endfor %}
</ul>
{% else %}
<p>Add links in <code>_config.yml</code> under <code>youtube_crypto</code>.</p>
{% endif %}

**CTFd:** {{ site.ctfd_url }}
