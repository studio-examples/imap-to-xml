imap-to-xml
===========

This example shows how to extract an attachment from the email and map it to XML format.

Step 1: import imap-to-xml project
Step 2: edit common.properties under scr/main/resources directory. Fill in the email address and the password.
Step 3: run an app
Step 4: send an email with the file input.csv under scr/main/resources as its attachment to the given email
Step 5: Success: the output in the console should contain this:

recieved: <?xml version="1.0" encoding="UTF-8"?>
<orders>
  <order>
    <orderId>1</orderId>
    <name>aaa</name>
    <units>2.0</units>
    <pricePerUnit>10</pricePerUnit>
  </order>
</orders>
<orders>
  <order>
    <orderId>2</orderId>
    <name>bbb</name>
    <units>4.15</units>
    <pricePerUnit>5</pricePerUnit>
  </order>
</orders>
