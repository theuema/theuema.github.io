---
layout: single
title: "Contact"
permalink: /contact/
hide_title: true # theuma: hide_title added to remove title from single.html layout
---

<form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="c93da368-c184-45e3-949f-04405d4db7b8">
    <input type="hidden" name="subject" value="New Submission on theuema.github.io">
    <!-- Redirect URL after form submit --> 
    <input type="hidden" name="redirect" value="https://theuema.github.io/thank-you">
    <!-- Form Inputs. Each input must have a name="" attribute -->
    <label for="email">Email address</label>
    <input type="email" name="email" placeholder="yourname@email.com" required style="margin-bottom: 20px;">
    <label for="subject">Subject</label>
    <input type="text" name="subject" placeholder="Your subject here" required style="margin-bottom: 20px;">
    <label for="message">Message</label>
    <textarea name="message" rows="10" placeholder="Leave a comment..." required style="margin-bottom: 20px;"></textarea>
    <!-- Prevent SPAM Submission -->
    <input type="checkbox" name="botcheck" class="hidden" style="display: none;">
    <!-- hCaptcha Spam Protection -->
    <!-- <div class="h-captcha" data-captcha="true"></div> -->
    <button type="submit">Submit Form</button>
</form>
<!-- Required for hCaptcha -->
<!-- <script src="https://web3forms.com/client/script.js" async defer></script> -->


<!-- <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfSVMwv9nGe3MFyg0FvoLLUkMewUf1SP4BDoSESqbRZWyBG1A/viewform?embedded=true" width="640" height="721" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>


<form action="https://formspree.io/f/xeqypdzd" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="_replyto"><br>
  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="10"></textarea><br>
  <input type="hidden" name="_next" value="https://www.theuermann.dev/thank-you">
  <button type="submit">Send</button>
</form> -->
