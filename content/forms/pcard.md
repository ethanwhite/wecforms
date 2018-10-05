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
    <label>Receipt: <input type="file" name="receipt" /></label>   
  </p>
  <fieldset>
    <legend>Funding source:</legend>
    Dept. ID: <input type="text" name="deptid" value="60470000" /><br>
    Fund: <input type="text" name="fund" /><br>
    Program: <input type="text" name="program" /><br>
    Source: <input type="text" name="source" /><br>
    Budget Ref: <input type="text" name="budgetref" /><br>
    Project Number: <input type="text" name="project" /><br>
    Flex Code: <input type="text" name="flexcode" /><br>
    UFID: <input type="text" name="ufid" /><br>
    CRIS: <input type="text" name="cris" /><br>
    Charge Amount: <input type="text" name="amount" /><br>
  </fieldset>
  <p>
    <label>Faculty Name: <input type="text" name="faculty" /></label>
  </p>
  <p>
    <label>Receipt Date: <textarea name="receiptdate"></textarea></label>
  </p>
  <p>
    <label>Total: <textarea name="total"></textarea></label>
  </p>
  <p>
    <label>Vendor: <textarea name="vendor"></textarea></label>
  </p>
  <p>
    <label>Items purchased: <textarea name="items"></textarea></label>
  </p>
  <p>
    <label>How does this benefit the funding source: <textarea name="benefit"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>