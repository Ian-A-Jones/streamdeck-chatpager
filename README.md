<img src="https://github.com/BarRaider/streamdeck-chatpager/blob/master/_images/chatpage.png" height="120" width="120"/> 

## Twitch Chat Pager plugin for the Elgato Stream Deck

The Twitch Chat Pager plugin listens to your Twitch chat and gives you a visual alert if someone uses the !page command.  
[Demo](https://streamable.com/1wxjh)

**Author's website and contact information:** [https://barraider.github.io](https://barraider.github.io)

### New in v1.7.4
- Page message can now be written to text file (and shown on stream)
- Can now listen for pages in multiple streamers chat rooms (great for Mods that are modding multiple streamers)
- Full-Screen Alert can now be shown even if you don't have the plugin on the current profile (as long as the plugin was shown on a different plugin, at least once, since you started streaming)

### Current features
- Shows you live information on your stream, including number of viewers and streaming time
- Starts flashing when someone writes the !page command in the chatroom
- !page command can be limited to only work for specific people in the chat
- Supports adding a short text after the command, such as *"!page Behind You!"*
- Configure your own personal chat message to show in chat when you're paged
- Added option to disable going to the Twitch Dashboard on button click
- Multiple full-screen modes include choosing 1 letter or 2 letters per key during an alert


### Download

* [Download plugin](https://barraider.github.io/utils/com.barraider.chatpager.streamDeckPlugin)

## I found a bug, who do I contact?
For support please contact the developer. Contact information is available at https://barraider.github.io

## I have a feature request, who do I contact?
Please contact the developer. Contact information is available at https://barraider.github.io

## Dependencies
* Uses StreamDeck-Tools by BarRaider: [![NuGet](https://img.shields.io/nuget/v/streamdeck-tools.svg?style=flat)](https://www.nuget.org/packages/streamdeck-tools)

* Uses [Easy-PI](https://github.com/BarRaider/streamdeck-easypi) by BarRaider - Provides seamless integration with the Stream Deck PI (Property Inspector)