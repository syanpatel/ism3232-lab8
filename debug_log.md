# debug_log.md
# Author: [Syan Patel]

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 12, in get total
What the error means: Python was looking for the work "amout" but it didnt exist in python's dictionary.
What I told the duck: I went through each line. See whats wrong. Follow the traceback.
What I tried: I added the debug print to see each record and saw 'amout'.
How I fixed it: I changed 'amout' to 'amount'

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16, in return amount
What the error means: The formtat the number written isn't recognized by python. 
How I fixed it: When the test failed I read what was wrong. It said not supported between int and str. It hihglighted the total so i removed the apostrophe marks.

## After Fixing Both Bugs
Final output: Total: $5150.00 accross 3 records.
Did pytest pass? Yes 

## AI Literacy Reflection
Did I use AI? No
If yes -- exact prompt I used: ___
What AI explained: ___
What I changed myself: ___
Can I explain every fixed line? Yes / No

## What I learned
I learned how to spot errors and go into the nano and fix whats wrong. I learned what KeyError and TypeError mean in practice. 
