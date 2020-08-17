---
layout: page
title: Free Stuff
description: "Looking for some free stuff to help get you to the next level"
---
## Free Stuff

<span class="image left"><img src="{{ "/images/pic07.png" | absolute_url }}" alt="" /></span>

If you're looking to get some free beats, look no further. Add your email details below so that I can send you a google drive link with five free beats. Lots of producers are putting their heart and soul in these beats so do them justice and deliver your best lines! If you make a beat with them, feel free to share it with me so I can have a listen!




<section>
<h3>Free Beats form Below</h3>
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
        <li><input type="submit" value="Get 5 Free Beats" /></li>
      </ul>
      <input type="hidden" name="slap_redirect" value="{{site.url}}{{site.slapform_thankyou_page}}" /> <!-- slap_redirect allows you to set a custom redirect/thank you page -->
    </form>
  </section>