---
layout: layouts/default-layout.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---

<div class="container" id="form-container">
  <h1>My Netlify Form</h1>
  <form  name="contact" method="POST" data-netlify="true">
  <p>
    <label for="name">Your Name: <input type="text" name="name" id="name" required /></label>   
  </p>
  <p>
    <label for="email">Your Email: <input type="email" name="email" id="email" required/></label>
  </p>
  <p>
    <label for="role">Your Role: <select id="role" name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label for="msg">Message: <textarea id="msg" name="message"></textarea></label>
  </p>
    <p>
      <input type="radio" name="gender" id="male" value="male">
      <label for="male">Male</label>
      <input type="radio" name="gender" id="female" value="female">
      <label for="female">Female</label>
  </p>
  <p>
    <fieldset>      
      <legend>What programming language you know?</legend>      
      <input type="checkbox" name="language" value="Python">Python<br>      
      <input type="checkbox" name="language" value="Java">Java<br>      
      <input type="checkbox" name="language" value="JS_Node">JavaScript/ NodeJS<br>      
  </fieldset>      
  <p>
    <button type="submit">Send</button>
  </p>
</form>
</div>