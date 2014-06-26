imap-to-xml
===========

This example shows how to extract an attachment from the email and map it to XML format.

Step 1: import the project
Step 2: edit common.properties
Step 3: run mule app
Step 4: send an email to the email address specified in the step 2. add a file input.csv under scr/main/resources as 
an attachment 
Step 5: Success: output in the console should contain:

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
