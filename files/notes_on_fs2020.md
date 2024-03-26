The following will cover the order in which I do things in fs2020. We go over initial set up, tips and tricks that have helped me over my time in using fs2020.

Tips

While starting the simm, start FSUIPC7, that is, after starting the sim, and while it's signing in, start fsuipc at the same time.

When choosing a gate, use the right joystick to scroll and the DPad to go up and down through the list. This also works with the keyboard. Simply hit down and dup a few times to scroll. When in flight conditions choose in order, all for players, off for air traffic and live for weather

First pmdg setup

When setting up the pmdg aircraft for the first time, you want to try and set up the following things. The options mentioned below will be accessed at line 4r in the main menu.

First, line 1l, then line 1L. Look for the following options. Use page up and down to switch pages. Hit your corresponding key to access the line numbers. You might need to refresh with alt plus R occasionally.

EGPWS page 4/17 and following.

V1: on

Bank angle: on

Minimums: on

2500: yes

1000: yes

500: yes

400: yes

300: yes

200: yes

100: yes

50 to 10: all set to yes.

Line 6l to return, then 6l to return to main settings window.

Line 2l: options

Line 1L: simm

5L: IRS, 3L: instant. This might already be set.

REALISTIC AP ENGAGEMENT

2L: off.

Call out: airspeed alive, 80 naught, v1, v2, positive rate of climb. All set yes. Refresh with alt R when needed.

AUTO TIME COMPRESSION: I have mine set to 16 x, so keep hitting 2L until you get there should you want it.

AP disconnect upon control input: disable.

Return with 6L

Let's take to the skies.

Every time you fly you will do the following after hitting "fly now" when the menu music changes, and the progress quits speaking.

Wait for about 20 seconds after you hit fly now. Start tfm, then Start FSFO next. Set parking brake by holding down numpad period for 3 seconds and while holding down numpad period tap control.

In fsfo, hit preflight flow then start to Program CDU.

It's programming time

Start by going to line 1left, then 6 right, hit page down to check IRS page, if all values are the same go back to page 1 and hit 6 right.

IN the routes page either select line 2left or type in the airports you are going to in the edit field and put them into line 2left. No spaces so for example enter ""klasklax" without the quotes. Now after about 10 or so seconds hit 6R then alt E to execute. You might need to refresh to make sure you see "activate" on the right-hand side of line 6.

Go to the next step with 6R. Enter the information needed.

Cruise alt will go in line 1R.

Rsv fuel will go into 4L, trans alt if needed will go into 4R.

The cost index will go into line 5L.

Hit 3L twice.

Hit alt E to execute. Go to the next page with 6R.

Check the temp at the airport with tfm then O. This step is not required, however I now out of habit do this. At least set your climb power and derate take off. I do lines 3L and 3R. For the tempt I normally put about below 28 to 30 degrees C into line 1L. Do not worry about this step if you do not want to do it. Go to the next step on line 6R.

For now, enter 5 into line 1L.

Go to the departure arrival page with alt plus A. Your departure will be on line 1L, and your arrival will be on 2R.

Once you have your runway and SID set, not necessarily in that order hit alt T for routs page. If you want to save your route in case something happens you can do so on line 4L. This is optional.

Now go to line 6R and you should be on the takeoff page.

Make sure 5 is still In line 1left. Make sure 24k derate is still in line 2. If it is not hit alt I to go to the perf in it page and set that up with 3L and 3R for 24k derate and climb power 1 respectively.

Go back to the takeoff page by selecting line 6R until you see "takeoff" in the title bar. Put all the speeds you see into the speed tape by hitting 1R, 2R and 3R.

Wait for fsfo to finish the preflight flow. You can check this in the messages section of fsfo by using screen review and looking for the messages line, go down one line in screen review and you should see preflight flow completed. Do not abort anything as you will have to go into the dat file and change stuff.

Run the preflight check list, wait about 10 seconds for the before start flow to run. If the before start flow fails to run, check the doors by hitting alt plus M, going to line 5R for fs actions, 3L for doors and close the main door with 1L. This usually kicks things off.

While the before start flow is running, bring up the speed, alt, navigation, and heading controls in TFM enter the speed you got from line 3L on the takeoff page. If you are running multiple desktops like I am, put the nav control on the same desktop as the sim.

Run the before start check. If all is good, do pushback through the pmdg CDU.

Requesting pushback.

Alt M for menu,

5R for FS actions,

4L for pushback.

Set options as needed, then 5R for removing chocks, make sure the X is next to remove. Then 5L to kick off the process.

Release parking brakes by holding down numpad period for 3 seconds.

I often use fsfo to start engines. If engines fail to start you will need to load the taxi or runway state load. This is a form of cheating to me; however, it will at least get you up and running. You might have to set engine switches to "cont" in the bottom overhead panel but that is not too hard.

Once the engines start, run the taxi check list. Reposition to the runway, then run the before takeoff check list.

Now set trim while in the sim. Once you rotate, hold attitude 10 if possible.

Turn on command A auto pilot via tfm's nav panel with alt plus A. LNav and VNav should engage, if they fail to turn them on in their respective panels, that being altitude and heading.

Run after takeoff check after gear is up and flaps are at 0, that is, when the aircraft is clean. You will usually do b gear up at about 300 feet or after about 5 seconds after you hear "positive rate of climb" then flaps up after you hear accelerations altitude, and after you hit about 200 naught.

Make sure you are on course. If you must go direct after your Sid is terminated, do so. Now just leave it alone until you get to descent.

Descending

When I'm about 5 miles from the top of descent I normally set my altitude to about the lowest waypoint I have on my star. This way my VNav will descend me at the right time and speeds. If I already have an ILS programmed in I set that to the highest in my ILS waypoint list. This will always be 2 up from the runway line, so go up from there. Example: if your runway is 19R, you will go up two lines from there. That will be your altitude to set to when descending.

Once I start my descent I keep an eye on things. I set my approach as follows.

Alt A for dep / arr page. then 2R for the arrival airport.

Choose your star on the left if there is one. Then execute.

Once about 12 thousand feet or so assuming the airport you are landing at is on flat ground, set your runway on the right-hand side. Execute the action.

Your descent check list can be run when you descend or when you input your runway. I tend to run when I start descending even though I do not have a runway set. I can still input a speed in the perf in it page (alt I) This will be on line 3R and 4R. you copy line 3R into 4R.

About 40 miles out from the airport, or when you get the runway from ATC, set your ILS. You do this with AP then shift N. This is going to be after you set your runway in TFM with tfm then control plus D. enter the icao of the airport, enter, choose ILS, hit alt O, go back into the runway dialogue with tfm then control plus D and tab to the read only edit. I copy all of that into a notepad file. Then set my ILS for nav 1 and 2 to the same freq as shown, then set course in nav 1 and 2 to the same heading as shown in the ILS information I copied into notepad.

About 20 miles out start putting out flaps. You will not have modified speed at all, VNav would have done all the work for you. So, try the following.

Flaps 1 until you reach speed 190. Then

Flaps 2 then flaps 5 until 180 then

Flaps 10 until you get to 170. Once you are 15 or so miles out gear down. 10 miles out flaps 15. once in approach mode, flaps 30. Set VRef plus 5 nauts for final appr speed. Hintr: yhoiyu will be using speed intervene for this final step. You will be landing at flaps 30.

Once you make that turn to final, turn on appr mode in the sim with left control plus A.

If you are successful and if the glide catches, just leave it alone.

Landing and final thoughts

Once you land and come to a stop, you will retract your flaps as soon as the after-landing flow starts, then set parking brakes and run the shutdown flow. The last two checklists in FSFO are optional.

Congratulations, you just did your first flight in the PMDG 737-8 in microsoftr fs20. Now, stand up, stretch and grab a nice stiff drink if you want to.
