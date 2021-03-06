---
title: Password reset form
parent: Form templates
order: 03
lead: A standard template for resetting a password
---

{% include code/preview.html component="password-reset-form" %}
{% include code/accordion.html component="password-reset-form" %}
<div class="accordion-bordered">
  <button class="button-unstyled accordion-button"
      aria-expanded="true" aria-controls="password-reset-docs">
    Brugervenlighed
  </button>
  <div id="password-reset-docs" aria-hidden="false" class="accordion-content">
    <h4 class="heading">Accessibility</h4>
    <ul class="content-list">
      <li>As you customize this form template, make sure it continues to follow the <a href="{{ site.baseurl }}/form-templates/">accessibility guidelines for form templates</a> and the <a href="{{ site.baseurl }}/form-controls/">accessibility guidelines for form controls</a>.</li>
    </ul>
    <h4 class="heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="content-list">
      <li>To offer a way to easily reset a password any time users are able to sign in to your site.</li>
    </ul>
    <h5>Guidance</h5>
    <ul class="content-list">
      <li>If users need a password to access your site, they will forget that password and need a way to reset it.</li>
      <li>For guidance on the technical details of validation, see the
        <a href="/components/form-controls/#validation">validation documentation</a>.</li>
      <li>State any password requirements (for example, “Must include one capital letter”) up front. Don’t leave users guessing about password requirements, only to hit them with an error message later.</li>
      <li>The requirements shown above are just provided as an example and should not be taken as recommendations.</li>
    </ul>
  </div>
</div>

