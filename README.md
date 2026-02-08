**Quick Menu: A Dynamic Action Button**

Quick Menu is an iOS shortcut that activates a small, dynamic and lightweight menu to be used via Action Button (highly recommended) or Back Tap on an older device.

Quick Menu allows multiple features to be added to action button or back tap using features already baked into iOS, with a nice dynamic UI, instead of installing apps that take up a ton of resources that could be purposed better. 

**Why v2?**

<img width="590" height="1278" alt="IMG_6496" src="https://github.com/user-attachments/assets/e04e277b-1c40-4d6b-b346-6a572909ade2" />

(above) **Quick Menu v2.0.1 Launch screen**

On the surface, Quick Menu is just a iOS Shortcut, but it is much more complex than that. I started v2 because i hit the architectural ceiling of v1 and my ideas (adding dynamic UI, scalable menus, future proof features) would require a new major version than incremental updates.

Quick Menu is also only approx. 38KB in size, making it run smoothly and taking up basically no memory. This is partly because its completely offline (apart from manual Updater) and has no background daemons with telemetry. I didn’t just stop with clunky UI for the point of tiny size; I made sure Quick Menu looks as legible and clean as possible, with features such as the Dynamic Toolbar (Capped at 1 line to not outweigh the top) and Launchpad, for features you might not need to always use, but are great to have, such as Get Clipboard and Weather (See the image down below).

<img width="590" height="1278" alt="IMG_6497" src="https://github.com/user-attachments/assets/c39f6e1b-004e-4ac0-bfff-951ed7774856" />

(above) **Quick Menu's Launchpad**


There are permissions in Quick Menu (Location for Weather and On The Go features, Mic for Shazam Music Recognition) but these are completely optional and only in Launchpad, never touching the core to maintain the original aims and goals of Quick Menu; to be simple and to do its job. The only online feature of Quick Menu is the manual Updater, which only directs you to the GitHub Release page of Quick Menu.

**Compatibility**

1. Requires iOS 17+

2. designed and tested on modern iPhones 

3. Could work on earlier iPhones/iOS versions, would not rely on it

4. Does not run on iPhone X

5. Best experienced with Action Button (iPhone 15 Pro line)

6. This is a iOS shortcut only, its not going to run as intended on macOS

Install

1. Click iCloud link in GitHub

2. Export to iPhone (skip this step if you are downloading on iPhone)

3. Add the shortcut to official apple Shortcuts app

4. Scroll down to the bottom and accept the shortcut

**What’s inside Quick Menu?**

(The previous images are great for reference)

Quick Menu is structured as a multi-level tree here, and it currently has 40+ interractive actions with various uses.

Quick Menu | [day/night emoji] [24hr time] | [battery state emoji] [battery %]

1. Torch

1. Media…
   
	2. Volume
	2. Playback…
    
		3. Previous Song
		3. Back 15 seconds
		3. Play/Pause
		3. Forwards 15 seconds
		3. Next Song
	2. Spotify…
	2. AirPlay…

1. Toggles…
   
	2. Silent Mode
	2. Rotation Lock
	2. Toggle Focus…
    
		3. Disable Focus
		3. Enable Focus…
	2. Display…
    
		3. Dark/Light Mode
		3. Set Brightness
	2. Control Center…

1. Launchpad…
   
	2. Get Clipboard
	2. Quick Note
	2. Weather
    
		3. Get Weather Forecast…
		3. Open Weather…
	2. Timer
    
		3. Set Timer…
		3. Cancel Timer
	2. On the Go…
    
		3. Where Am I?
		3. Shazam
		3. QR Code Scanner
	2. Games…
    
		3. Magic 8 Ball
		3. Dice…

1. Settings…
   
	2. Updater…
	2. Permissions…
	2. About…


**Notes & Limitations**

-Known issue of Quick Menu getting stuck and not showing after closing the device with it active. Fix with running a different shortcut with a menu or restart the device to clear the session.

-If you found Quick Menu to be a a great tool, or found it nice to use at 2am, leave me a star; it would be greatly appreciated.

-Quick Menu is highly customisable, any shortcut can be added or removed easily. 

This is the 2st release of Quick Menu v2, make a comment on GitHub if you want anything added or if you have feedback.
