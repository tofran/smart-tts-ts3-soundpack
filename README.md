# Tofran's Smart TTS soundpack:

Smart TTS is a custom sun pack for teamspeak 3. It's a mix between the default female voice and TTS (Text To Speech), in order to create a pleasing Text To Speech sound pack experience.

## Behaviour

 - It uses the default female sounds if the action does not involve variables (client nickname, channel names, etc). Ex:
   - If you mute your microphone it will play the recoording "Microphone Muted" wav file from the default female soundpack.
   - If someone joins your channel it will output "<USER> joined your channel" with system TTS.
 - Lots of simplified sentences to make them shorter and more pleasent to listen.
  
**Note:**

 - To ensure the best experience channel and clients should have pre-defined phonetic names.
 - It does not contain a single audio file! It uses the **Default Sound Pack (Female)** and **Default Text To Speech** by *TeamSpeak Systems GmbH* (so you need to have them - included by default with the teamspeak installer).
 
## Versions

 - **Smart TTS** is the recommeneded soundpack for everyone, it is simple, consise and works very well.
 
 - On the other hand **Smart TTS Extended** is more complex and overloaded with actions. You you use it on a big server or dont configure ir properlly to disable unecessary sounds it can be **very annoying**. It adds sounds that aren't directly connected with your client/channel for example:
  - `username` created an channel
  - `username` was banned by `username`
  - `username` joined the server
  - .... and more

## Windows 8, 10 and later
This soundpack was originally designed for Windows 7. On 8, 10 and later you may need to tweak Windows text-to-speech settings.
Open **Change text to speech settings** settings, you can find it by searching for `speech` or the long way by navigating to *Control Panel* > *Speech Recognition* then *Advanced speech options* in the left panel.

If you still with me, on the second tab *Text to Speech* you can change the behaviour of the TTS.
I Personaly recomend *Microsoft Zira* (mobile or desktop) at a modest speed of 13. 
Fell free to tweak around and find the best for you.

## How to

To Install the soundpack, just run the file, then click install.
(You may be asked to give admin privileges depending on your installation path)
Then restart your TeamSpeak client.

To make it server specific (recommended) go to bookmarks>manage bookmarks, select the server you wish to edit the sound pack then (in the more pane) select "Smart TTS" as the soundpack.

To use it for all servers (set it as the default, not recommended) go to settings>options>notifications then select "Smart TTS" from the drop down menu and then click the check button.

To use it occasionally, just go to Self>Sound Pack>Smart TTS whenever you want to use it.

More info in the forum post [forum post].

## License

MIT


[forum post]: <http://forum.teamspeak.com/showthread.php/105784-SoundPack-Smart-TTS-by-ToFran?p=396416#post396416>
