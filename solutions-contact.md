---
layout: solutions_page_2
title: CONTACT
subtitle: Contact Us
permalink: /solutions/contact/
---


[//]: # see http://webdesign.tutsplus.com/tutorials/quick-tip-add-a-formspree-form-to-your-static-sites--cms-23870
[//]: # input type="text" name="name" placeholder="Your name"> (This can go inside form element to input name)

Please feel free to get in touch with inquiries about collaboration, services, volunteering, and financial contributions. We would love to hear from you.


<a href="http://twitter.com/seedwater" target="_blank"> <i class="fa fa-twitter fa-2x"></i></a> @seedwater  
<a href="http://facebook.com/seedwater" target="_blank"> <i class="fa fa-facebook fa-2x"></i></a>&nbsp;&nbsp;&nbsp; Seedwater Solutions  
<a href="http://linkedin.com/seedwater" target="_blank"> <i class="fa fa-linkedin fa-2x"></i></a> &nbsp; Seedwater Solutions  

<form id="contactform" method="POST" class="bootstrap-frm">
    <div class="form">
        <input type="email" name="_replyto" placeholder="Your email">
        <input type="hidden" name="_subject" value="Website contact" />
        <input type="hidden" name="_next" value="{{ site.baseurl }}/thank-you/" />
        <textarea name="message" placeholder="Your message"></textarea>
        <input type="text" name="_gotcha" style="display:none" />
    </div>
    <br>
    <button class="button contactbutton" style="vertical-align:middle" value="Submit"><span>SUBMIT </span></button>
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'toby.lunt' + '@' + 'gmail' + '.' + 'com');
</script>   

