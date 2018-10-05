---
title: "Pcard"
date: 2018-10-05T18:46:28-04:00
draft: false
---

<form name="Purchasing Card Receipt Form" method="POST" netlify>
  <p>
    <label>Cardholder: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Funding source: <input type="text" name="fundingsource" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>