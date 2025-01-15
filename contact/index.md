---
title: Contact
template: base.html
---

<div class="jumbotron bg-light">
  <div class="row g-3 align-items-center">
    <div class="col-md-4">
      <img src="../assets/agu.jpg" alt="Sample Image" class="img-fluid rounded" style="">
    </div>
    <div class="col-md-8">
      <h1 class="display-4">Contact</h1>
      <p class="lead">
        Have questions, feedback, or just want to say hello? Feel free to reach out to me!
      </p>
      <hr class="my-4">
<ul class="fa-ul">
{% for contact in config.contact.links %}
  <li>
  <i class="fa-li {{ contact.icon }}"></i>
  <a href="{{ contact.url }}">{{ contact.text }}</a>
  </li>
{% endfor %}
</ul>
   </div>  
  </div>
</div>
