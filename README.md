# Chat Panel Plugin

A plugin that adds in-game chat to the side panel or seperate popout windows. 

By default has tabs for Public, Private, Clan, Game (including dialog messages).




![image](https://github.com/Yenof/chat-panel/assets/122739279/190bf4c0-2f23-4d15-ad65-51a6a5a8fb38)![image](https://github.com/Yenof/chat-panel/assets/122739279/cfa6f204-3f40-4732-b94f-b30db4c072c1)













## Configuration

Configurable text, background, and name colors per tab.

Adjustable Font sizes per tab. (Min size 5, max 50)

Options for Bold, Italic, and Plain font styles. 

Can choose between many tabs: Public, Private, Clan, Friends Chat, Game, All, Combat, and Custom (1, 2, 3). Recommended default 4 to fit nicely on sidepanel. 

Chat Area Height can be adjusted, recommended to be less than the height of your client. 

Timestamps and spaces between lines can be added.

Always on top, preset size, Auto-pop, and opacity options for pop out window.

Sidebar icon position can be adjusted or icon hidden.

Can hide Pop out button (Disable Pop Out) to save screen space on small screen devices. 



![image](https://github.com/Yenof/chat-panel/assets/122739279/525134c0-626c-40b0-9acb-4b11f5d64588)![image](https://github.com/Yenof/chat-panel/assets/122739279/b561e3ab-7a41-4c49-a90b-ae1fb9552dcc) 





## Usage:

Right clicking on a tab shows additional options like "Pop out", "Reset History", and "Export logs".

Clicking a tab with middle mouse button can also pop the tab out into it's own window.

Scroll and click to lock position while reading, return to the bottom to resume snapping to most recent message.

Text can be copied with Ctrl+C.

Custom tabs start empty, and you must add desired chat channels through the Custom Chat configuration. 

If you have "Hide Sidebar Icon" enabled and close the pop out window, you will need to toggle the plugin on/off with Auto-Pop enabled to have it auto-pop back out.

Timestamp Format can be set using SimpleDateFormat patterns.

![Screenshot from 2024-02-12 17-22-18](https://github.com/Yenof/chat-panel/assets/122739279/d0c3e199-f9a9-4e3d-b199-5d1acc1a6d96)

## Notes:

Max lines of chat is 10,000 by default.

When toggling plugin on/off it does not remember messages. 

Combat tab provides very basic logging, there are other plugins for more advanced logging.

Combat tab uses what the player is targetting, so if there is no target it will just say "PlayerName was hit for: 1".

"Hide pop out button" and "Auto-pop out window" do not work together.

<br/>
<br/>
<br/>
I love feedback, please feel free to reach out with any comments, concerns, or questions to @Yenofthunder on Discord. :D
