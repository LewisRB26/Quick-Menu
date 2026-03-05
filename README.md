**Quick Menu: A Dynamic Action Button**

Quick Menu is an iOS shortcut that activates a small, dynamic and lightweight menu to be used via Action Button (highly recommended) or Back Tap on an older device.

Quick Menu allows multiple features to be added to action button or back tap using features already baked into iOS, with a nice dynamic UI, instead of installing apps that take up a ton of resources that could be purposed better. 

**Why v2?**  
<img width="590" height="1278" alt="IMG_6577" src="https://github.com/user-attachments/assets/4177f624-8285-4a5b-8d4f-17edecbc7fc7" />

(above) **Quick Menu v2.4.0 Launch screen**

On the surface, Quick Menu is just a iOS Shortcut, but it is much more complex than that. I started v2 because i hit the architectural ceiling of v1 and my ideas (adding dynamic UI, scalable menus, future proof features) would require a new major version than incremental updates.

Quick Menu is also only approx. 48KB in size, making it run smoothly and taking up basically no memory. This is partly because its completely offline (apart from manual Updater) and has no background daemons with telemetry. I didn’t just stop with clunky UI for the point of tiny size; I made sure Quick Menu looks as legible and clean as possible, with features such as the Dynamic Toolbar (Capped at 1 line to not outweigh the top) and Launchpad, for features you might not need to always use, but are great to have, such as Get Clipboard and Weather (See the image down below).

<img width="590" height="1278" alt="IMG_6578" src="https://github.com/user-attachments/assets/755e288f-0a54-499d-ae9c-94641f3cbcf5" />

(above) **Quick Menu's Launchpad**


There are permissions in Quick Menu (Location for Weather and On The Go features, Mic for Shazam Music Recognition) but these are completely optional and only in Launchpad, never touching the core to maintain the original aims and goals of Quick Menu; to be simple and to do its job. The only online feature of Quick Menu is the Updater, which only fetches version.json from GitHub, tells you if there is a update based on the version and if there is, it asks you if you want to open the RoutineHub download link and if not, you can quit Quick Menu. 

**Quick Menu is also on RoutineHub!** _In case you are interested:_ https://routinehub.co/shortcut/24915/ (Note: _Please_ be careful of popups; there are a lot)

**Compatibility**

1. Requires iOS 17+

2. designed and tested on modern iPhones 

3. Could work on earlier iPhones/iOS versions, would not rely on it

4. Does not run on iPhone X/iOS 16

5. Best experienced with Action Button (iPhone 15 Pro line)

6. This is a iOS shortcut only, its not going to run as intended on macOS

**Install**

1. Click iCloud link in GitHub

2. Export to iPhone (skip this step if you are downloading on iPhone)

3. Add the shortcut to official apple Shortcuts app

4. Scroll down to the bottom and accept the shortcut

**What’s inside Quick Menu?**

(The previous images are great for reference)

Quick Menu is structured as a multi-level tree here, and it currently has **40+** interractive actions with various uses.

Quick Menu | [day/night emoji] [24hr time] | [battery state emoji] [battery %]

Torch  
Media…  
   
   Volume
   Playback…
   		Previous Song
		Back 15 seconds
		Play/Pause
		Forwards 15 seconds
		Next Song
	Spotify…
	Shazam...
	AirPlay…

Toggles…
   Silent Mode
   Rotation Lock
   Toggle Focus…
   Display…
   		Dark/Light Mode
		Set Brightness
	Network...
		Toggle WiFi
		Toggle Celluar
		Toggle Bluetooth
	Control Center…

Launchpad…
   Get Clipboard
   Quick Note
   QR Code Scanner
   Where Am I?
   Weather...
   		Get Weather Forecast…
		Open Weather
		
	Timer
    
		3. Resume Timer
     	3. Pause Timer
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

<img width="587" height="607" alt="IMG_6502" src="https://github.com/user-attachments/assets/4b99a23e-689f-493f-848f-1b4e4bb4c0dd" />


(above image) ASCII Magic 8 Ball 


**Notes & Limitations**

-Known issue of Quick Menu getting stuck and not showing after closing the device with it active. Fix with running a different shortcut with a menu or restart the device to clear the session.

-If you found Quick Menu to be a a great tool, or found it nice to use at 2am, leave me a star; it is always appreciated.

-Quick Menu is highly customisable, any shortcut can be added or removed easily. 

This is the 7th release of Quick Menu v2, make a comment on GitHub if you want anything added or if you have feedback.
