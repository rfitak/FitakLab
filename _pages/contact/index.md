---
layout: page
title: Contact
permalink: /contact/
toggle: on
rank: 6
---
<head>
    <script>UPLOADCARE_PUBLIC_KEY = "9ece2f24515da2c6390d";</script>
<script src="https://ucarecdn.com/libs/widget/2.10.2/uploadcare.full.min.js" charset="utf-8"></script>
</head>
<H3 align="center">If you are interested in joining the lab or for more information, please contact us using the form below.</H3>
<font size="3">Equality and inclusion of people from diverse backgrounds are fundamental to scientific inquiry.  Similar to how major scientific steps forward have been made through the integration of multiple disciplines, the integration and collaboration of diverse people has generated new ideas, techniques, and paradigms critical for scientific advancement. Not only are we committed to fostering a diverse and inclusive atmosphere, whether it be gender, race, disability, sexual preference, etc., but recognize that it is essential to the scientific and personal development of all of us.</font>
<br>
<hr>
<br>
<form class="wj-contact" action="https://formspree.io/{{site.email}}" method="POST">
  Your email address:<br>
    <input type="email" name="email" placeholder="Email"><br>
  First name:<br>
  <input type="text" name="firstname"><br>
  Last name:<br>
  <input type="text" name="lastname">
  Interested in:<br>
  <input type="radio" name="application goal" value="MS"> MS<br>
  <input type="radio" name="application goal" value="PhD"> PhD<br>
  <input type="radio" name="application goal" value="Postdoctoral"> Postdoctoral fellow<br>
  <input type="radio" name="application goal" value="Work"> Employment <br>
  <input type="radio" name="application goal" value="Volunteer"> Volunteer<br>
  <input type="radio" name="application goal" value="Other"> Other
  <br>
  <textarea rows="10" cols="100" name="message" placeholder="Type your message here"></textarea>
  Attach a single file (<i>i.e.</i> CV, cover letter). Merge multiple files into a single PDF.<br> <input type="hidden" role="uploadcare-uploader" name="myFile" />
  <button type="submit">Send</button>
</form>

<style>
form.wj-contact input[type="text"], form.wj-contact textarea[type="text"] {
    width: 100%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: monospace, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #2e83e6;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}
form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #2e83e6;
    border-radius: 3px;
    padding: 0.5em;
    margin: 0.25em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}
</style>

