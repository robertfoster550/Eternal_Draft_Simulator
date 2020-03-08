# Draft_Simulator
Eternal Draft Simulator
by: Robert Foster (aka: Xi550, astroknitter)

This program is intended to simulate a draft for the game Eternal. It is not affiliated with Eternal or Dire Wolf Digital in any way. This is just a fan-made project, intended for use by the community. All assets from Eternal are property of Dire Wolf Digital. All copyrighted material, images, and ideas belong to Dire Wolf Digital. This simulator is in no way intended to compete with the original game, and is simply a way to express love for the game, to provide a place to practice, and to spread awareness of the original. If you have never played Eternal, download it and play it! It is a great game. Visit https://www.direwolfdigital.com/eternal/ for more information.

The images and JSON files used as the basis of the drafter are taken from Eternal Warcry; https://eternalwarcry.com/. Please visit and use this website, as it is also great.

Some card ratings used are from Farming Eternal; http://farmingeternal.azurewebsites.net/. This is a great podcast and community. The ratings themselves are taken from Ben's metrics. Thank you all very much!

Feel free to provide feedback on GitHub or anywhere else you can reach me.



### Version 0.1 ###

Currently it is just a Python code (or corresponding Jupyter Notebook code). To use, download the files, and run the code (or the notebook). There are a few packages that are required to run it, but most are not unusual, so hopefully it isn't too difficult to use. I'm brand new to coding for other's use, so let me know if there is something I really shouldn't do.

### Version 1.0 ###

There is now a basic GUI in place, and a Windows executable. To use it, simply download and extract all of the files, then find the application called "Draft Simulator" and double-click. That will run the program. Currently, the bots do not have much information about the format, as it runs the Set 6 - Flames of Xulta draft, which currently is new. So, the bots are a bit dumb, but they still work; usually taking the rare in the pack and then sticking to the first two colors they get into. This will be improved soon.

### Version 1.1 ###

Moved 'Start Draft' button to center of the screen.
Made the stats slightly smaller.
Made the deck list slightly larger.
Added the 'Cost Curve' to the drafting screen.
Added progress bar to the drafting screen.
Added 'Settings', saving and resetting; more options comming soon.
All of Set 7 has been added, but we don't have the Draft Pack contents yet, so the default format is still 6c. 

### Version 1.2 ###

Added Format 7 draft, and made it the default.
Fixed the Pass Styles, so they actually work now.

### Version 1.3 ###

Added hidden files, which should allow the program to run on other computers. These were numpy, Pillow, requests, matplotlib, and IPython.
Added 'Learning Bots', where a players choice will improve the rating of a card.
Added Warning for reseting bots.
Fixed y-ticks on bar plots, so they wouldn't crowd as much.

### Version 1.4 ###

Made it so Bot deck buttons change depending on the pass style.
Added personality qualities; color preferences, tempo preference, rarity preference.
Added bot options; allowing you to change them.
Added name to stats page.
Added cube options. The set MUST have at least 144 cards per pack (576 for standard 4 set drafts), or the app will crash.
Can now add promos and unnumbered cards if desired.
Added saveable data arrays for the formats and sets.
Added menues, and a way to add formats and sets.
Sets must have at least one card of each faction, and if being used as a regular set, needs at least 1 legendary, 1 rare, 3 uncommons, and 9 commons.
Added Set 7b, and updated curated pick amounts, to reflect in-game rates.

### Version 1.41 ###

Fixed the boosed rate, so that it was actually acurate. Previously it was +1 as much.
Also added a shortcut icon.

### Version 1.42 ###

Fixed the program, so that it would run.
Added 'Promises by Firelight' cards.

### Version 1.5 ###

Changing the way boosted cards are added, so that different amounts can be added for each card.
Added the Flames of Xulta preview format.
Added Echoes of Eternity cards and format.
