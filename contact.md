---
title: Contact
layout: contact
description: Contact
---

Are you ready to take your screening processes to the next level? Our dedicated sales and support teams are here to help you explore exciting possibilities and guide you towards success. Whether you have questions about our products, need assistance with placing an order, or simply want to discuss your specific needs, we're just a conversation away.

<form name="contact" netlify method="POST">
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="name">Name</label>
      <input type="text" class="form-control" id="name" name="name" placeholder="John Smith">
    </div>
    <div class="form-group col-md-6">
      <label for="email">Email</label>
      <input type="email" class="form-control" id="email" name="email" placeholder="Email">
    </div>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea class="form-control" id="message" name="message" rows="3"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
