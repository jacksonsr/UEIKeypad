# UEIKeypad
UEI XHK1 keypad DTH for SmartThings.  Modified to work with SHM Delay 2.0

This DTH was set-up specifically to be used with SHM Delay 2.0.  It may work with other smartapps but has not 
been tested.  This DTH was modified to accomodate a change to createEvent that smartthings made to the platform 
on or around May 09, 2019. On May 10, 2019 smartthings reverted that change so that the "old method" and 
"new method" both worked on the platform. The problem with this is that this DTH is designed to work with the 
new method of createEvent and will not work with a smartapp that still uses the old method. An old DTH 
will not work with a smartapp designed to work with the new method either.  That means that we now have smartapps
that require a certain DTH to make them work.  It also limits that apps that will workwith any given DTH.  
In my opinion, a can of worms that should not have been opened.

I suppose someone much more adept at coding a DTH could make a DTH that works under both conditions but I do not
have that knowledge nor do I have the need so I will leave it to someone else if they want a DTH for that 
particular scenario.

Arn B updated the old Centralite DTH and his smartapp SHM Delay 2.0 on May 09, 2019 to work with the new method 
of createEvent.  I took his updated DTH and changed the references to the battery voltages and added the 
fingerprint to work with the Xfinity UEI XHK1 keypad that is available on Ebay for around $20.  No changes other
than commenting were made to Arn B.'s modified Centralite keypad.  I will try too keep this DTH updated as Arn B.
makes any changes so that it continues to work with SHM Delay 2.0.
