# delegation-script
Easy Steemit Delegation Script HTML and JS
This script lets you easily add a delegation form to your website. Not sure how all of this works but this is a super simple script that many folks need to help them integrate with steemconnect2.0. You can customize it how ever you want.

You will want to change the line 6 ... delagatee=steemthat to delegatee=yourusername. Of course you might want to change the image link also to make it yours. This script lets people delegate 10 Steem Power. I'll be adding a selection list to this soon unless someone else wants to add it before I get to it.

Added 4 selections and tested it out again...Success! The way to calculate the STEEM Power is in Vests... The conversion rates change from time to time. I will need to build a script that calls the Steem API for this number and then does the math at some point...Or someone else that is a lot smarter than me might do it and update this code. Very nice of you if you do it..Many thanks yous.

Currently the Vests from steemd.com
steem_per_mvests

486.604

Here is the formula:
1,000,000/486.604 = V
V multiplied by the number of Steem Power (10,25,50,100) to delegate = Final Answer

Note The Format has to be numbers in front or the decimal 00000.000000 and has to have 6 numbers after the decimal.
