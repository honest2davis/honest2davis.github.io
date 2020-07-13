---
layout: page
title: Thank you for your correspondence
---
## Check out the latest beats

<iframe id="soundee_player" frameborder="0" src="https://soundee.com/player/1426?iframe=1" style="width:100%;height:600px;max-width:980px;" allow="autoplay"></iframe>
<br>
### New beats are uploaded weekly! If you'd like to keep updated, feel free to sign up below.

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
        <li><input type="submit" value="Sign Up" /></li>
      </ul>
      <input type="hidden" name="slap_redirect" value="{{site.url}}{{site.slapform_thankyou_page}}" /> <!-- slap_redirect allows you to set a custom redirect/thank you page -->
    </form>
</section>