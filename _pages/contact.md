---
layout: page
title: Contact
permalink: /contact
comments: false
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Voor vragen kan je mij altijd een bericht sturen!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Naam*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mailadres*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Bericht*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form>