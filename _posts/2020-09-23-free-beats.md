---
layout: post
title:  "Five Free Beats"
date:   2020-09-23
excerpt: "Let's keep it simple, can I help you with some free beats?"
image: "/images/pic07.png"
---
## Need a freebie?

Yeah it's a little tough out there so let me help you with a 5 pack of free beats with the contract in them so that you can use them commercially too. Pop your email down in the form below and I'll send you the link directly for some free beats.

<section>
    <form method="POST" action="https://api.slapform.com/{{site.email}}">
      <div class="field">
        <label for="name">Name</label>
        <input type="text" name="name" id="name" />
      </div>
      <div class="field">
        <label for="email">Email</label>
        <input type="email" name="slap_replyto" id="email" /> <!-- slap_replyto will set the reply-to as the submitter's email! -->
      </div>
      <ul class="actions">
        <li><input type="submit" value="Get Free Beat" /></li>
      </ul>
      <input type="hidden" name="slap_redirect" value="{{site.url}}{{site.slapform_thankyou_page}}" /> <!-- slap_redirect allows you to set a custom redirect/thank you page -->
    </form>
  </section>