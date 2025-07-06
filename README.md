# Chat Panel Plugin


This plugin displays in-game chat in a separate window or the side panel.

The Chat Panel window can be moved freely like a normal windowed application, including to different monitors.



![image](https://github.com/Yenof/chat-panel/assets/122739279/93b9e17f-f326-4a2e-a8ba-d4a0b977fd0a)![fixedimage](https://github.com/user-attachments/assets/803ba7ca-ae16-4ac7-993b-2b4dd2853b5e)
















## Configuration
There are many config groups that contain the plugin's settings.<br/>
They can be expanded by clicking on the group name or little arrows.


![image](https://github.com/user-attachments/assets/5a187a52-abb7-464e-bc9b-b10ba9be7e87) ![image](https://github.com/Yenof/chat-panel/assets/122739279/b561e3ab-7a41-4c49-a90b-ae1fb9552dcc)


Configurable text, background, timestamp, and name colors per tab.

Adjustable Font sizes per tab. (Min size 5, max 200)

![Screenshot from 2024-08-21 16-55-26](https://github.com/user-attachments/assets/41cbed28-8bc1-4e5b-ba2c-23341f7506b1)

"Odd Row Shading" tints alternating lines of chat for visibility. Negative entries darken, positive lighten.

Line spacing adds space in between messages. (Max 10)

The font can be changed by selecting one of the several example fonts, or with the Custom Font option you can use a `.ttf` or `.otf` font file of your choice. (More info in [Usage](#usage) section)

Options for Bold, Italic, Italic Bold, and Plain font styles.

Timestamps can be set using SimpleDateFormat patterns. (HH:mm, yyyy.MM.dd, and more)

![Screenshot from 2024-08-21 16-56-05](https://github.com/user-attachments/assets/9a2e785c-4a3e-4b5e-8083-452863599e70) ![Screenshot from 2024-08-21 16-56-26](https://github.com/user-attachments/assets/39385ad7-24c8-4568-8f72-6e8a16edd2c8)



The window size and transparency (opacity) of the pop out window can be configured.

The pop out window can be set to "Always on Top", keeping it on top of other windows and programs.

"Auto-Pop Out Window" allows the pop out window to spawn when RuneLite is started with the plugin on, or when the plugin is turned on.

"Remember Pop Out Position" saves the size and location of the pop out window to be used next time the pop out window is opened.

![image](https://github.com/user-attachments/assets/fae88c8f-edc4-4930-a6f8-660a5f064aaa) ![Screenshot from 2024-08-21 16-59-57](https://github.com/user-attachments/assets/bbcae4ad-2d9a-4547-bd68-53c516f94555)





Can choose between many tabs to display: Public, Private, Clan, Friends Chat, Game, All, Combat, and Custom (1, 2, 3).

"Tab Font" allows your choice of Font from the General section to apply to the tab names. 

By enabling "Split PMs" in the "Private Chat" settings, you can spawn individual tabs for each private chat conversation. 

For the Combat Tab, there are options to only show combat events related to you, hide zero damage events, and show deaths in chat.

The Message Type Coloring section allows you to select a color for a chat type. (Public Chat green, Examine text red). <br>
These choices persist through all Chat Tabs, overriding the text colors chosen in the Chat Tabs.


Chosen words (separated by commas) can be highlighted with the "Highlight Words" options. "Partial Word Highlighting" allows highlight words like "Sell" to highlight part of "Selling".

Similarly, chosen words (separated by commas) can be censored from chat using the "Filtered Words" setting.
By default this censors the filtered word, but with the "Remove Filtered Message" option enabled it removes the entire message. 

The Notifications section allows tabs to be highlighted when they receive a new content. Select the tabs you want notifications for by holding Ctrl and clicking them.

![image](https://github.com/user-attachments/assets/774fa4a0-d4db-46d3-beef-3cf1dd751e94) ![image](https://github.com/user-attachments/assets/f11286dd-efe6-4e1a-a585-bef3aa963255)

The height of the Chat Area in the side panel can be adjusted, recommended to be less than the height of your client.

The sidebar icon position can be adjusted or the icon hidden.

Can hide the Pop out and Pop in buttons, except when the side panel is empty.

Can disable the icon for the pop out windows.

"Export Log Date" allows you to select a date format for the .txt file created by Export Log.

By using "Enable My Name Color" and "My Name Color" you can set a name color for when a message has your username in the name field.

"Random Colors" randomly-ish recolors individual letters, with a minimum brightness set by the corresponding setting. 

![image](https://github.com/user-attachments/assets/6240f1f5-9150-438b-8e9e-a44b19af8583) 






## Usage:

Right-clicking on a tab shows additional options like "Pop Out", "Reset History", "Export Log", and "Search".

The right-click "Search" option functions similarly to Ctrl+F; it finds, highlights, and jumps to instances of the search term within the tab.

Clicking a tab with middle mouse button can also pop the tab out into it's own window.

Scroll and click to lock position while reading, return to the bottom to resume snapping to most recent message.

Text can be copied with Ctrl+C.

Custom tabs start empty, and you must add desired chat channels through the Custom Chat configurations.

If you have "Hide Sidebar Icon" enabled and close the pop out window, you will need to toggle the plugin on/off with Auto-Pop enabled to have a new Chat Panel window created.

To use a Custom Font, place a `.ttf` or `.otf` file named `customfont.ttf` into `%userprofile%\.runelite\chat-panel` on Windows or `~/.runelite/chat-panel` on Linux/OSX, then select -Custom Font- in Chat Panel's config. <br>
It must be named exactly `customfont.ttf`, even if it is an `.otf` file. <br>
Not all font files work, notably fonts with colors or pictures seem to not work.

![Screenshot from 2024-08-21 17-01-28](https://github.com/user-attachments/assets/5f614adc-536d-43f9-9749-5332f29cdee1) ![Screenshot from 2024-09-15 19-18-22](https://github.com/user-attachments/assets/b572df9f-e5fa-4733-beda-dc189c1e61c8)





## Notes:
Max lines of chat is 10,000 by default.

Some config options apply retroactively when changed, but not all.

When toggling the plugin on/off it does not remember message history (including closing and reopening the client).

Really long NPC Dialog messages get cut off and don't show the whole text, there are other plugins that handle this better.

Combat Tab provides very basic combat logging, there are other plugins for more advanced logging.

The Combat tab relies on what the player is targetting, so if you are hit and you have no target it will just say "PlayerName was hit for: 1".

The appearance of Chat Panel's titlebar is mostly dependent on your operating system's settings, some systems allow user customization of titlebars.<br/>
For now, Chat Panel does not inherit RuneLite's Custom Chrome on all OSs, some work though.<br/>
Screenshots are taken on X11/GNOME/22.04 with RuneLite's Custom Chrome enabled.


<br/>
<br/>
<br/>
<a href="https://discord.gg/AT44tqXVwH"><img src='https://img.shields.io/discord/1307357303099621426?color=ffd700&&logo=discord&logoColor=%23ffd700&style=for-the-badge'/></a>

I love feedback, please feel free to reach out with any comments, concerns, or questions to the Chat Panel Discord. :D<br/>
or<br/>
Issues can be posted to Github Issues.<br/>
Suggestions can be posted to Github Discussions.
