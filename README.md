# Chat Panel 
<a href="https://discord.gg/AT44tqXVwH">
  <img src="https://img.shields.io/badge/Support-ffd700?logo=discord&logoColor=%23000000&style=Yeno" alt="Support">
</a>
<br><br>


This plugin displays in-game chat in a separate window or the side panel.

The Chat Panel window can be moved freely like a normal windowed application, including to different monitors.




![image](https://github.com/Yenof/chat-panel/assets/122739279/93b9e17f-f326-4a2e-a8ba-d4a0b977fd0a)![fixedimage](https://github.com/user-attachments/assets/803ba7ca-ae16-4ac7-993b-2b4dd2853b5e)
<br>
 

## Configuration
There are many config groups that contain the plugin's settings.<br/>
They can be expanded by clicking on the group name or little arrows.<br>
Can also use colors chosen in RuneLite's `Chat Color` plugin.

<img width="227" height="515" alt="image" src="https://github.com/user-attachments/assets/2fea9dc5-803e-4fa9-b6e6-97880a904f04" /> ![image](https://github.com/Yenof/chat-panel/assets/122739279/b561e3ab-7a41-4c49-a90b-ae1fb9552dcc)


Configurable text, background, timestamp, and name colors per tab.

Adjustable Font sizes per tab. (Min size 5, max 200)


<img width="231" height="110" alt="image" src="https://github.com/user-attachments/assets/df03a3fc-1d93-4672-ba51-dbce7fa91e4f" />
<br>

 ##
 
### <span style='color:rgb(220,138,0)'>General</span>

"Odd Row Shading" tints alternating lines of chat for visibility. Negative entries darken, positive lighten.

Line spacing adds space in between messages. (Max 10)

The font can be changed by selecting one of the several example fonts, or with the Custom Font option you can use a `.ttf` or `.otf` font file of your choice. (More info in [Usage](#usage) section)

Options for Bold, Italic, Italic Bold, and Plain font styles.

"Client Chat Colors" enables the colors chosen in RuneLite's `Chat Color` plugin to be used in Chat Panel. 
(More info in [Base Colors](#base-colors))

Timestamps can be set using SimpleDateFormat patterns. (HH:mm, yyyy.MM.dd, and more)

<img width="231" height="215" alt="image" src="https://github.com/user-attachments/assets/926eb021-ed54-4861-b608-d8a793c7a825" />
<br>

##
 
### <span style='color:rgb(220,138,0)'>Pop Out Window</span>

The window size and transparency (opacity) of the pop out window can be configured.

The pop out window can be set to "Always on Top", keeping it on top of other windows and programs.

"Auto-Pop Out Window" allows the pop out window to spawn when RuneLite is started with the plugin on, or when the plugin is turned on.

"Remember Pop Out Position" saves the size and location of the pop out window to be used next time the pop out window is opened.

![Screenshot from 2024-08-21 16-56-26](https://github.com/user-attachments/assets/39385ad7-24c8-4568-8f72-6e8a16edd2c8)
<br>

 ##

### <span style='color:rgb(220,138,0)'>Tabs</span>
Can choose between many tabs to display: Public, Private, Clan, Friends Chat, Game, All, Combat, and Custom (1, 2, 3).

"Tab Fonts" allows your choice of Font from the General section to apply to the tab names, colored with "Tab Name".

"Selection Underline" controls the color of the line beneath the selected tab.

By enabling "Split Private Messages" you can spawn individual tabs for each private chat conversation. 

<img width="227" height="480" alt="image" src="https://github.com/user-attachments/assets/7261e7ea-a49e-42be-a296-739eb9cfb0ae" />
<br>

##
 
### <span style='color:rgb(220,138,0)'>Combat</span>

"Damage Brightness" configures the brightness of the combat damage number. Applies to all tabs. <br>Negative numbers darken, positive brighten. (Min -100, max 100)

To hide hitSplat messages from other players, enable "Only Show My Combat Events".

"Show Deaths" adds a message when something dies. This does include things killed by other players.

To hide blocked/missed hits, you can enable "Hide Zero Damage Events".

"Add Combat Labels" adds "Combat" and "Death" to messages from those chat types in the Combat tab.

"Legacy Combat Messages" displays combat messages in the old style (pre-Chat Panel 2.3).
<br>
E.g., `Guard was hit for: 0`  instead of `Guard blocked`.

<img width="227" height="292" alt="image" src="https://github.com/user-attachments/assets/ea3f58ce-9f51-45d3-9275-9aebffdefdfd" />
<br>

##
 
### <span style='color:rgb(220,138,0)'>Highlighting & Filtering</span>

Chosen words (separated by commas) can be highlighted with the "Highlight Words" options. "Partial Word Highlighting" allows highlight words like "Sell" to highlight part of "Selling".

Similarly, chosen words (separated by commas) can be censored from chat using the "Filtered Words" setting.
By default this censors the filtered word, but with the "Remove Filtered Message" option enabled it removes the entire message. 

"Game Highlights" keeps text color highlights given by the game. (Olm orbs, Tempoross attacks)",


"RuneLite Highlights" keeps text color highlights given by RuneLite. (GE Average<span style='color:yellow'> 92</span> HA value <span style='color:yellow'>2</span>)<br>Uses the colors from the Transparent section in the `Chat Color` plugin.


<img width="231" height="419" alt="image" src="https://github.com/user-attachments/assets/b7466bc2-2856-4cb3-a992-a411bd0dfd9a" />
<br>
  
##
 

### <span style='color:rgb(220,138,0)'>Message Type Coloring</span>

The Message Type Coloring section allows you to select a color for a chat type. (Public Chat green, Examine text red). <br>
These choices persist through all Chat Tabs, overriding the text colors chosen in Base Colors and RuneLite's Chat Color plugin.

Override Name, Timestamp, and Group Name recolor these sections with the color chosen for the Message Type.


<img width="225" height="120" alt="Screenshot from 2025-08-01 15-30-55" src="https://github.com/user-attachments/assets/45b41c3d-56b0-4845-928c-cef53b415331" />
<br>
  
##
 
### <span style='color:rgb(220,138,0)'>Notifications</span>
The Notifications section allows tabs to be highlighted when they receive new content. 

Select the tabs you want notifications for by holding Ctrl and clicking them. (Ctrl+Click)

"Notification Color" configures what color the tab is changed to when notifying.

![image](https://github.com/user-attachments/assets/774fa4a0-d4db-46d3-beef-3cf1dd751e94)
<br>
  
##
 
### <span style='color:rgb(220,138,0)'>Base Colors</span>

The Base Colors section contains the default colors used for each Chat Tab, ***before any other recoloring.***
<br>

With `Client Chat Colors` enabled, coloring works like this:<br>
#1 - Colors chosen in Chat Panel's "Message Type Recoloring", and if that's blank...<br>
#2 - Colors chosen in RuneLite's Chat Color plugin, and if that's blank...<br>
#3 - Colors chosen in the in-game Settings chat section, and if that's non-applicable...<br>
#4 - Will default to Chat Panel's Base Colors<br>
<br>


Without `Client Chat Colors`:<br>
#1 - Colors chosen in Chat Panel's "Message Type Recoloring", and if that's blank...<br>
#2 - Will default to Chat Panel's Base Colors<br>


<br>

_You can recolor almost all of the elements in Chat Panel using only RuneLite's `Chat Color` plugin._ <br>
_These colors are largely for legacy purposes, it is intended to use primarily the Chat Color plugin for coloring._

<img width="227" height="733" alt="image" src="https://github.com/user-attachments/assets/f1a3f32f-9dd4-40c3-8423-122c99de8072" />

<br>

##
 
### <span style='color:rgb(220,138,0)'>Extras</span>

Max Lines determines the maximum number of lines that can be held in each tab.

The height of the Chat Area in the side panel can be adjusted, recommended to be less than the height of your client.

Show Account Type Icons allows icons like Iron, Hardcore, Leagues, and more, to show up in Chat Panel.

The sidebar icon position can be adjusted or the icon hidden.

Can hide the Pop out and Pop in buttons, except when the side panel is empty.

Can disable the icon for the pop out windows. (Titlebar, Taskbar)

"Export Log Date" allows you to select a date format for the `.txt` file created by Export Log.

Max PM Tabs configures the maximum number of spawnable private message tabs. 

By using "Enable My Name Color" and "My Name Color" you can set a name color for when a message has your username in the name field.

"Random Colors" randomly-ish recolors individual letters, with a minimum brightness set by the corresponding setting. 

<img width="227" height="436" alt="image" src="https://github.com/user-attachments/assets/6fcfcea7-eaab-42ad-8aa0-9b980ddd1acb" />

 
<br>
 


## Usage:

Right-clicking on a tab shows additional options like "Pop Out", "Reset History", "Export Log", and "Search".

The right-click "Search" option functions similarly to Ctrl+F; it finds, highlights, and jumps to instances of the search term within the tab.

Clicking a tab with middle mouse button can also pop the tab out into its own window.

Scroll and click to lock position while reading, return to the bottom to resume snapping to most recent message.

Text can be copied with Ctrl+C.

Custom tabs start empty, and you must add desired chat channels through the Custom Chat configurations.

If you have "Hide Sidebar Icon" enabled and close the pop out window, you will need to toggle the plugin on/off with Auto-Pop enabled to have a new Chat Panel window created.

To use a Custom Font, place a `.ttf` or `.otf` file named `customfont.ttf` into `%userprofile%\.runelite\chat-panel` on Windows or `~/.runelite/chat-panel` on Linux/OSX, then select -Custom Font- in Chat Panel's config. <br>
It must be named exactly `customfont.ttf`, even if it is an `.otf` file. <br>
Not all font files work, notably fonts with colors or pictures seem to not work.

<img width="226" height="269" alt="image" src="https://github.com/user-attachments/assets/b4f28701-8203-47f1-8767-32390608e15c" /> ![Screenshot from 2024-09-15 19-18-22](https://github.com/user-attachments/assets/b572df9f-e5fa-4733-beda-dc189c1e61c8)




 
<br>
 
## Notes:
Max lines of chat is 10,000 by default.

Some config options apply retroactively when changed, but not all.

When toggling the plugin on/off it does not remember message history (including closing and reopening the client).

Really long NPC Dialog messages get cut off and don't show the whole text, there are other plugins that handle this better.

The appearance of Chat Panel's titlebar is mostly dependent on your operating system's settings, some systems allow user customization of titlebars.<br/>
For now, RuneLite child windows like Chat Panel or Color Picker don't inherit Custom Chrome on all OSs, some work though.<br/>
Screenshots are taken on X11/GNOME/22.04 with RuneLite's Custom Chrome enabled.


<br/>
<br/>
<br/>
<a href="https://discord.gg/AT44tqXVwH">
  <img src="https://img.shields.io/badge/Discord-ffd700?logo=discord&logoColor=%23000000&style=for-the-badge" alt="Support"style="transform: scale(1.2); transform-origin: top left;">
</a> 

I love feedback, please feel free to reach out with any comments, concerns, or questions to the Chat Panel Discord. :D<br/>
or<br/>
Issues can be posted to GitHub Issues.<br/>
Suggestions can be posted to GitHub Discussions.
