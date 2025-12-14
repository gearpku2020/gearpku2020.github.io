---
title: "Contact"
permalink: /Contact/
layout: single
author_profile: false
---

<style>
.contact-form{
  max-width: 600px;
  margin: 0 auto;
}
.contact-form label{
  font-weight: 600;
}
.contact-form input,
.contact-form textarea{
  width: 100%;
  padding: 10px;
  margin-top: 6px;
  margin-bottom: 16px;
  border-radius: 8px;
  border: 1px solid rgba(0,0,0,.2);
}
.contact-form button{
  padding: 10px 22px;
  border-radius: 999px;
}
</style>

<p>
If you have any questions about our research, tools, or collaborations,
please feel free to contact us using the form below.
</p>

<form class="contact-form"
      action="https://formspree.io/f/xjknzapq"
      method="POST">

  <label for="name">Name</label>
  <input type="text" name="name" required>

  <label for="email">Email</label>
  <input type="email" name="email" required>

  <label for="message">Message</label>
  <textarea name="message" rows="6" required></textarea>

  <button type="submit" class="btn btn--primary">
    Send Message
  </button>

</form>
