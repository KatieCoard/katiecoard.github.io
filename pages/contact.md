---
layout: page
title: "Contact"
meta_title: "Contact and use our contact form"
show_meta: false
teaser: "Get in touch with me? Use the contact form."
permalink: "/contact/"
---
Get in touch!  You can email me at <a mailto="rethinkingrotary@gmail.com">rethinkingrotary@gmail.com</a>, or use the form below – they both end up in my inbox.


<form action="//formspree.io/rethinkingrotary@gmail.com"
      method="POST">
    <label>Name<input type="text" name="name" placeholder="Jane Smith"></label>
    <label>Email<input type="email" name="_replyto" placeholder="janesmith@gmail.com"></label>
    <label>Message<textarea name="message"></textarea></label>
    <!-- This link is the page the user is forwarded to after submission
    We can set this up once we know the permanent domain name.
    <input type="hidden" name="_next" value="//site.io/thanks.html" /> -->
    <input type="submit" value="Send" class='medium button radius'>
</form>
