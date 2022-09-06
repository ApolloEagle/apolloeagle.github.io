---
layout: page
title: About
permalink: /about/
---

<div>
    <p>
    If you have a question, please fill out the appropriate fields below and we will contact you as soon as possible.
    </p>
    <form action="https://formspree.io/f/xnqrjjok" method="POST" class="contact-form">
        <label>First Name</label>
        <input type="text" name="first-name" required/>
        <label>Last Name</label>
        <input type="text" name="last-name" />
        <label>Email</label>
        <input type="text" name="email" required/>
        <label>Subject</label>
        <input type="text" name="subject" required/>
        <label>Message</label>
        <textarea class="textarea" name="message" required></textarea>
        <button>Submit</button>
    </form>
    <div class="link">
        <a href="{{ site.baseurl }}/privacy">Privacy Policy</a>
    </div>
</div>
