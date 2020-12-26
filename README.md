# Ultimate TTSH Source Pack
Hello there, this is FriskySaga! Just a few remarks:

I facechecked the zip file from [this video](https://www.youtube.com/watch?v=A_RGw8cdwjs). Then I uploaded all the files from that zip file as is to GitHub so that my friends could have access to this.

I also grabbed the updated 9 cogs stun file from that video description and made the updates here.

Finally, I'll copy paste the text files from the zip file for easy access.

P.S. And I'll make updates to the code as needed

## How To Get Started
***To Play Solo***
1. Extract the entire .ZIP Folder
1. Install Panda3D
2. Open TTSH\win32
3. Open start_all.bat
4. Play!

***To start up your own server***
1. Install Hamachi
2. Create an account or log in
3. Create a Hamachi network/Join your friends' Hamachi network
4. Open TTSH\win32
5. Open start_all.bat
6. Play!

***To join someone's server***
1. Install Hamachi
2. Create an account or log in
3. Create a Hamachi network/Join their Hamachi network
4. Open TTSH\win32
5. Open join_server.bat
6. Enter a Username (Don't make it random/be sure to remember it as your toons will be stored here)
7. Copy their IPv4 Address
8. Enter their Hamachi IPv4 address
9. Play!

********************************************************************************

For 

For CFO, WAIT until Mata Harry starts TALKING, then type "~rcr" twice.
  If you ~rcr too early, you will crash.
  If you ~rcr only once and hop on a crane, you will crash as well.

For CJ, if you want the podium there, type "cannons", then "~rsc".
  If you only ~rsc, the CJ will be floating; however the podium will remain on the ground.
  If you do the cannon round, the scale will appear as it normally would.

## Useful Commands
\\Starting Off//

To max your toon:
~maxtoon (must do this to be able to exit TTC
~maxhp [15-137] (sets max laff)
~hp [15-137] (sets laff)
~NeverSleep (disables falling asleep for your current session; does not affect other toons)

To change your name and nametag style:
~name [name]
~nametag [style]

To change your clothes:
~shirt [value]
~shirtcolor [value]
~sleeves [value]
~sleevescolor [value]
~bottoms [value]
~bottomscolor [value]
~hat [value] [value]
~glasses [value] [value]
~backpack [value] [value]
~shoes [value] [value]
~color [head/arm/leg] [value]
~gm

Values are in the shticker book

\\For the VP//
~stunvp
~skipvp
~rpr

\\For the CFO//
~rcr (skips straight to the crane round/restarts the crane round)
~setCraneSpawn [1-4] (sets the craning spawn point of a certain toon)
~safeRush (sets knockout damage in cfo to 2 for safe rush practice)
~DisableGoons (stuns all goons in the area)
~god (god mode + superspeed; ~run to disable the superspeed)
~oobe (allows you go get an out of body POV; navigate with left/right click)

\\For the CJ//
~cannons (skips to the start of the cannon round; use for 12 cog stuns or for scale practice)
~rsc (skips straight to the scale round/restarts the scale round)
~GivePies 7 (gives infinite amount of evidence)
~fps (shows fps in top right corner)
~run (toggles speed)
~god (god mode + superspeed)
~stun (instantly stuns all lawyers and gives you stun bonus)
~FillJury (fills all jury seats with toons)

\\For Recording Cinematics//
~getpos/~setpos [x y z] (get/set your coordinates; will appear in your game client command prompt)
~gethpr/~sethpr [h p r] (get/set your angle/rotation/pivot; will appear in your game client command prompt)
~camera startpoint [x y z h p r] (sets your startpoint for the camera path)
~camera addpoint [x y z h p r t] (adds a point in which the camera will fly towards; t stands for seconds it takes to fly there)
~camera play (plays the camera path in full)
~camera clear (clears all points; does not clear startpoint. to clear startpoint, just replace it)

## Credits
The Toontown Offline Team for the original source code
Aeterna/Alyazia for modifying all 3 sources
Relentless/Travis for writing the rebind source for scale + crane source
Holland for implementing rebind keys for stunning source + compiling all of these files together

Astron
Panda3D (More specifically, the modified Astron Panda3D which can be found here)
libpandadna
libotp-movement
libotp-nametags
Reverse-engineered Toontown Online client/server source code is property of The Walt Disney Company.

"Should credit 'Sketched' too because I basically took his branch and modified it from there"
-Aeterna