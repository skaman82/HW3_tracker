# Hello Watch 3 UI bug/functions status tracker
Here I want to list all current issues of the watch at current firmware development stages. The goal is not to make the watch to look bad, but to show the issues and demonstrate where things could be improoved to make it a good product. I think this watch has potential, but it is clearly "not there yet". I am sure even people would pay up to 50% more for this watch if the software and functionality is REALLY MUCH better than other replicas. Main focus is UI and functionallity of the watch core functions. While smoothness is an overall an issue, I leave this aside, since the functionality has a much higher priority.


REMARK: My step counter and "raise to wake" functions never worked since I got the watch. There are some people reporting steps
or rase to wake functions working - some even both. Regarding this I'm not sure if this is falty hardware and bad quality control or something else.


<b>LIST UPDATE STATE: FW 1.00.42</b> tested with Android phone

## General/Menu/Watchfaces
• CRITICAL Function issue: Watch doesn't stop vibrating when I take the call on my phone<br>

• CRITICAL Function issue: Volume control is not linked to phones volume (even if there is the setting "Media tone control"). When volume on the phone is turned down, increasing the volume on the watch has no effect<br>
- since 1.00.42 the watch has a new BT profile (detected as a watch) - in the BT device options on the phone you can activate the volume sync, but I think this should be on by default, like with other bt speakers <br>

• CRITICAL Function issue: "Raise to wake" doesnt work on my watch - might be a hardware fault (see above)<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/3.jpg" width="300px"/>

• CRITICAL Weather don't show up on the side dashboard (when you swipe right on the watch face) only cloud icon with a question mark<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/4.jpg" width="300px"/>

• UI: current watchfaces seem to have a lower resolution than the watch display. 
This resulting in blown up and blurry graphics<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/1.jpg" width="300px"/>

• UI: All corner icons in the stock watchface are not updating/working. Both on top don't open anything. The top right one could be battery level.<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10041/1.jpg" width="300px"/>

• UI: In the main menu the rainbow icon opens "sport stats" instead of "step summary". 
This is not logical as the icon represents the rainbow circle of the "steps stats screen".<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/2.jpg" width="300px"/>

• <del>Function issue: Sometimes charging screen remains on, even when the charger is remooved</del> - this screen is now updated with the bedside clock mode since 1.00.42<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/10.jpg" width="300px"/>

• NEW BUG since 1.0.42: turning the crown normally gives some haptic feedback, but sometimes after a while the vibration is completeley gone until you restart the watch.<br> 

• Not a bug, but but a suggestion: I would love if an interactive watch face style could be locked (now it is still changes style/colors on tap)<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/5.jpg" width="300px"/>

## Notifications


• CRITICAL UI: New message banner notification does not disappear on the home screen (should be only visible 2-4 seconds)<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10041/5.jpg" width="300px"/>

•CRITICAL UI: Custom wallpaper watchface breaking notification delete function: Can't delete a single notification in a stack when custom wallpaper watchface is used <br>

• CRITICAL Seating/Drinking reminder <del>can not be set up yet in the phone app</del> fixed in  1.00.42 - but reminders dont work yet on the watch<br>
• Notifications overflow: too many not usefull notifications normally not displayed by other watches like "tweet send" or "xx new messages" from whattsapp<br>

• Message detail UI: Longer messages are not displayed in full and cut off in the detail view<br> 

• UI: Not all selectable notifications from the app list have a dedicated icon, WhattsApp, Facebook, Instagramm do. But Telegram for example has a generic icon<br>

• UI: "Clear all" button would make more sense at the bottom (after scrolling through the messages)<br>
• UI: Currently there is room for a second line of text for the message preview<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10041/6.jpg" width="300px"/>

• UI: "WhatAapp message summary" message has a corrupted message count when the number is higher then 9 (see photo). But the whole message is unnecessary. The companion app should filter those default nonsense messages out and only sent usefull messages to the watch<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/7.jpg" width="300px"/>

• <del>swiping back from the message detail view shows black screen (when you have a couple messages)</del> fixed in 1.00.41<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/6.jpg" width="300px"/>

• UI: <del>Some people report time/date on the notifications not being accurate (works on my watch with android)</del> - reported as fixed in 1.00.42<br>


## Custom watchfaces
• CRITICAL: Custom watchface breaks notification system - deleting one single message not possible (see above)<br> 
• Function request: please also add pointer dial style to make it perfect<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/8.jpg" width="300px"/>


## Allways on display
• UI: Digital style of AOD is very simple and could have a nicer font and maybe additional info like steps, day/date or battery status<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/9.jpg" width="300px"/>


## Bedside clock
• <del>Currently missng:</del> Please make sure it is constant on with low light intensity while charging or add at least this option to the bedside clock setup screen.<br>
• BUG: since 1.00.42 bedside clock is added, but display goes off after couple of seconds, also charging state indication is missing (circle in %)<br>
+ on my watch display doesn't rotate on orientation change<br>
• BUG since 1.00.42: when switching in bedside clock mode watch sometimes reboots<br>
- <a href="https://youtu.be/ARyXgjeM1rM">see Video ></a>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/10.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/IMG_20230706_114316_edit_10699710599927_resized_20230706_114843767.jpg" width="300px"/>


## Sports (very brief tested so there may be more)
• UI: Lock/Add buttons during an activity have no function - icons are not logical<br>
• Workout/Activity stats are now shown when workout is finished - saving them (button) doesn't work<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/13.jpg" width="300px"/>

<i>• rest to be tested</i>

## Sport record
• UI: Icon makes no sense as it is showing "Step rainbow"<br>
• finished Workout/Activity is not listed yet<br>
<i>• rest to be tested</i>

## Heart Rate

• CRITICAL: Heart rate logging inconsistant (doesn't record data sometimes)<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/hr_log.jpg" width="300px"/>

• UI: Missing space: 80bpm 0Minutes ago (space between "0" and "Minutes")<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/14.jpg" width="300px"/>

• UI: Missing space and typo in "Resting heartrate" and in "Walking heartrate": 80bpm 0Minutes *Agogo* (space between "0" and "Minutes"  and "ago")<br>
 in 1.00.42: seem to be fixed, but "Missing spaces" remain.<br>
 
 • <del>CRITICAL since 1.00.41: heart rate seems not to be logged in the UI graph anymore</del> - fixed in 1.00.42<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/15.jpg" width="300px"/>


## SPO
• UI: Result screen doesnt look good<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/16.jpg" width="300px"/>


## Step
• CRITICAL Function: Step count not working on my watch (always showing 0 steps)<br>
• CRITICAL Function: When accessing step count from the watchfase (swiping left), vertical scrolling does not work to see the stats<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/17.jpg" width="300px"/>

• UI: Wrong icon in distance stats section (blue) - currently showing green steps icon <br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/11.jpg" width="300px"/>


## Compass
• CRITICAL: NEW in 1.00.42: Compas working initially after factory reset, but stops working after a short while using the watch<br>
• UI: switching between the two compass modes not allways work/very laggy (tapping on the list icon)<br>
• <del>CRITICAL Function: Not working on my watch yet - compass only mooving a few degrees if I rotate the watch</del> - kind of fixed in 1.00.42<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/18.jpg" width="300px"/>


## Sleep
• CRITICAL Sleep tracking & Stats: Not working on my watch yet <br>
• UI: "All timing" Screen not working / not configurable<br>
• UI: "add other timing" screen not working / not configurable<br>
• UI: "Sleep goal" button looks not aligned and has no function<br>
• App: "Sleep tracking" can not be activated in the phone app - only heart rate and SPO monitoring<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/19.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/20.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/21.jpg" width="300px"/>


## Dial
• UI: "+" takes you to contact list instead of typing "+" (icon either should be changed or the functionallity)<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/22.jpg" width="300px"/>


## Call record
• CRITICAL UI: Call records not scrollable if the list getting longer<br>
• NEW in 1.00.42 - deleting a call record (swiping left) breaks the UI (grey background breaks)<br>
• function: Call records list of my phone is not displayed, only calls I've made from the watch are visible<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/23.jpg" width="300px"/>
• <del>CRITICAL UI: Call records dissapearing sometimes once viewed</del><br>


## Contacts
• UI: Not enough spacing between profile icon and name<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/24.jpg" width="300px"/>


## Calender
• UI: 1st weekday is currently Sunday - thats not the case in europe and should be at least configurable <br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/25.jpg" width="300px"/>


## Weather
• CRITICAL UI: Forecast not readable (maybee add an dark gradient in the background or redesign)<br>
• CRITICAL UI: scrolling reveals black borders, while swiping left, forecast elements overflows (only when you start the weather app from the menu)<br>
• UI: Weather data not showing up on the dashboard in the watchface (only cloud icon with a "?" - see above)<br>
• UI: animated wave has no function and can be remooved <br>
• Function: weather not accurtate for my location (16 vs 19 deg/sunny vs raining)<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/26.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/27.jpg" width="300px"/>


## Music
• CRITICAL Function: BT earbud connection doesn't work<br>
• UI: no visual feedback on volume change im "media control" mode, volume level does not controll phone volume<br>
• UI: "loop track" icon has no functionality in media control mode and can be remooved in "mobile music" state<br>
• since 1.00.41: when in local music mode, chinese text is shown sometimes<br>
• Function request: please display cover artwork, title and artist of uploaded mp3 song in local music view - if possible <br>

• <del>UI: local music screen (please sync on your App) has a misplaced small music icon on the screen - apears when you tap on the tracklist icon</del> fixed in 1.00.42<br>
• <del>CRITICAL Function: local music: music file transfer not working (android)</del><br>
• <del>UI: Track name is not displayed properly while in media control mode (only first track gets updated)</del> fixed in 1.00.41<br>
• <del>UI: Play/Pause button has no state change (should be displayed as pause while music is playing)</del> fixed in 1.00.41<br>
• <del>UI: no visual feedback on volume change</del> fixed in 1.00.41 - but only in local music mode <br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/28.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/29.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10041/2.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10041/3.jpg" width="300px"/>



## Position app
• Function: This doesn't work yet on my watch<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/30.jpg" width="300px"/>


## Breath training
• UI: animation is stuttery (not a priority tho) <br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/31.jpg" width="300px"/>


## Alarms
• CRITICAL Function issue: sound alarm missing even when "ring" is set, also vibration too weak and to short<br>
• CRITICAL Function issue: Snooze function does not work, alarm not repeating<br>
• UI: in alarm edit view there is a typo on the delete button - it says "Dele"<br>
• <del>UI: text is not vertically centered and changes style (active/not active)</del> fixed in 1.00.41<br>
• <del>UI: when setting additional alarm and activating it the bell icon is overlapping text</del> fixed in 1.00.41<br>
• <del>CRITICAL adding a new alarm not allways work</del> - fixed in 1.00.42<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/32.jpg" width="300px"/>


## Stop watch
• CRITICAL Function issue: Seconds count does not corresponds real seconds (counting stuttering) - it is quite off<br>
• You cant start the count on crown press, only lapcount function


## Timer
• CRITICAL Function: sound alarm missing - vibration is not enought<br>
• UI: When timer is finished UI looks stange<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/33.jpg" width="300px"/>


## Voice assistant
• <del>Since 1.00.41: UI now displaying this (not working) toggle instead of the assistant icon</del> - fixed in 1.00.42 - appears now only if BT is not connected<br>
• <del>CRITICAL Assistant answer is not playing through the watch</del> - fixed in 1.00.42<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10041/4.jpg" width="300px"/>



## Photo album
• UI: Delete button labell is not scrolling and is cut off<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/34.jpg" width="300px"/>
• <del>CRITICAL Function: Deleting a photo doesn't work</del> fixed in 1.00.42<br>



## Audio Recording
• CRITICAL There is no possibility to save the recorded audio file to the phone, only playback<br>
• No possibility to delete the file on the watch from the phone (android) on iPhone it seems to work<br>


## Find my watch
• please add beeping/ringing sound to the watch<br>


## Settings
• Battery UI: not really helpfull data - maybee add time since last charge?<br>
• CRITICAL Settings > Sports: UI is broken, labels not scrolling (too much space between options)<br>
• CRITICAL Settings > Heartrate: UI is broken (text not vertically centered)<br>
• CRITICAL Settings > Fitness record: UI is broken (too much space between options), goal setup missing<br>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/36.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/37.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/38.jpg" width="300px"/>
<img src="https://github.com/skaman82/HW3_tracker/blob/main/10040/40.jpg" width="300px"/>




