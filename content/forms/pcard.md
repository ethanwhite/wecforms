---
title: "Pcard"
date: 2018-10-05T18:46:28-04:00
draft: false
---

<form name="Purchasing Card Receipt Form" method="POST" netlify>
  <fieldset>
    <legend>Purchase:</legend>
    Cardholder: <input type="text" name="name"><br>
    Faculty Name: <input type="text" name="faculty"><br>
    Vendor: <input type = "text" name="vendor"><br>
    Total: <input type = "text" name="total"><br>
    Receipt Date: <input type="date" name="receiptdate"><br>
    Receipt: <input type="file" name="receipt"><br>
    Descripe Items purchased:<br>
    <textarea name="items" rows = 5 cols = 30></textarea><br>
    How does this benefit the funding source:<br>
    <textarea name="benefit" rows = 5 cols = 30></textarea><br>
  </fieldset>
  <fieldset>
    <legend>Funding source:</legend>
    Dept. ID: <input type="text" name="deptid" value="60470000"><br>
    Fund: <input type="text" name="fund"><br>
    Program: <input type="text" name="program"><br>
    Source: <input type="text" name="source"><br>
    Budget Ref: <input type="text" name="budgetref"><br>
    Project Number: <input type="text" name="project"><br>
    Flex Code: <input type="text" name="flexcode"><br>
    UFID: <input type="text" name="ufid"><br>
    CRIS: <input type="text" name="cris"><br>
    Charge Amount: <input type="text" name="amount"><br>
  </fieldset>
  <p>
    <button type="submit">Send</button>
  </p>
</form>