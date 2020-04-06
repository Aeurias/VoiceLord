# VoiceLord 1.3.2 by Aeurias for Mount & Blade II: Bannerlord

[![](https://img.shields.io/badge/Download-VoiceLord_1.3.2c-green?logo=github&style=for-the-badge)](https://github.com/Aeurias/VoiceLord/releases/tag/v1.3.2c)  [![](https://img.shields.io/badge/NEXUS-MODS-orange?logo=&style=for-the-badge)](https://www.nexusmods.com/mountandblade2bannerlord/mods/59)  [![](https://img.shields.io/badge/Discord-Aeurias_5479-7289da?logo=discord&style=for-the-badge)](https://www.nexusmods.com/mountandblade2bannerlord/mods/59)   [![](https://img.shields.io/badge/Spanish%20Version-Here-red?logo=github&style=for-the-badge)](https://gist.github.com/Aeurias/f09b8a570c398264be0b492bfe138542) 

![](https://i.imgur.com/Qd7BNMq.png)
![](https://i.imgur.com/ByrmX54.png)

### **So how does it work?**

**VoiceLord** works by using a speech recognition utility [**VoiceMacro**](http://www.voicemacro.net/download/) (*It's just like VoiceAttack but costs you nothing, yes it's free!*) with this we can send a combination of keys to the game to cast our commands for controlling troops = **Less faffing about with your keyboard + more immersion + more action!**


### **Give us some examples!**

With **VoiceLord**, you're able to select & command troops individually, all of them or in groups, have them do formations, movements & actions.
Saying a command such as ***"Infantry and archers, make a shield wall"*** will have those troops to make a shield wall for you, or you can make archers stop firing their bows, or make your gang charge into a castle by saying ***"Okay everyone, hunt them down!"***...


### **Can I use sweary words?**

Of course, because swearing is cool... just add the F word to some commands or... and when it gets grim just say ***"Okay everyone...FUCKING LEG IT!"*** to do a rapid retreat!

 
### **So how do I get setup?**

Simple, you will need:

+ **A microphone.**
+ [**VoiceMacro**](http://www.voicemacro.net/download/)
+ [**My VoiceLord profile**](https://www.nexusmods.com/mountandblade2bannerlord/mods/59/)

1. **Download the VoiceLord file from the files section and extract it.**
2. **Import into VoiceMacro by pressing the Edit button at the top left.**
3. **Then on the Profiles and macros window, press Import at the bottom.**
4. **The profile will be loaded, press Save.**
5. **Now on the VoiceMacro window to make sure *Mount and Blade II Bannerlord* is the target or choose *Active Window*.**

You can test to see if voice recognition and/or your microphone is working by saying *"can you hear me?"* a Windows TTS bot will respond, letting you know!

That's all! Now grab a glass a water to keep that voice of yours hydrated and start a battle!

------


![](https://i.imgur.com/xSPwsoH.png) ![](https://i.imgur.com/ChuaPkA.png) 

> *Make sure you adjust the recognition threshold settings to your liking or use settings in the image*

------

### Help it doesn't work for me!


***You will need to set up and train your Microsoft speech recognition for better accuracy if you haven't before. The more you train it or the more you use it, the more it will detect your voice correctly; You can do this directly from VoiceMacro, by clicking the 3 lines, burger menu icon on the top right > Windows speech recogniser. It is suggested you do it at least 3 times.***

![](https://i.imgur.com/UTnFDha.png)


If your voice is recognised but no actions are being inputted into the game, try running VoiceMacro app in **Administrator mode.**

![](https://cdn.discordapp.com/emojis/600180300747767808.png)  ![](https://i.imgur.com/j4XaxuX.png)

> *Also, make sure nothing in the top right of the VoiceMacro app has been toggled off (**Red X**)*


You will also need to make sure you have *Microsoft Speech Recogniser 8.0 in English* on your machine, most likely you will.


If it's detecting words, but not words you are saying or it has some uncertainty to it, you can change the recognition settings in the *Recogniser settings* in the settings drop window by following the image guide above.


VoiceMacro is using the microphone that is set as *"Default Device"* in **Window's Audio Recording Settings** if you have attached over one microphone you might have to define which one to use as the default microphone - you also have to make sure the microphone **Input Volume Level** is not **too low, too high or the microphone is muted.** Check VoiceMacro's Main Window left bottom corner for the **green Input Volume Meter** to make sure the Microphone Input is not too low when you speak.

*After talking, make a short pause (about 1 sec) before you speak the next command.*

if you misspoke a command (like *"Archers make me wet"*), don't correct yourself by saying *"err, archers, chaaarrgeeee??"*...
If the recognition engine does not understand your command at the first try, don't change your voice, just wait for a second and repeat and speak clearer, this will help it as it learns your voice.


*Speech Recognition will work way better over time, you can blast battle music in the background on speakers or whisper the commands at night and it will understand it.*

------

**VoiceLord** works by selecting an AI group then doing an command action

So saying: **"*Archers hold your fucking fire!*"** 

This will select the '*Archers*' (with 2 key) and then press '*Hold Fire*' key (with the F4 key).

We also have prefix, infix & suffix:

**"*[;fucking; okay], [;form a; make a], [;go on; adopt; take on]*"** are ***Prefix***

**"*[;fucking]*"** is also an ***Infix***

**"*[;listen to me]*"** is a ***Suffix***
 
These prefix and suffix are optional but help improve the voice detection a lot when they are used in your sentences.

Such as:

> [;okay] **archers** [;listen to me] 

> [;fucking] **charge**

You say = ***"Okay archers listen to me.", "Fucking charge!"*** 

Saying it like this with the use of prefix and suffix is **best** as it detect your voice almost **100%** of the time!


or you say = ***"Archers", "Charge"***

> **archers**

> **charge**


Saying it like this **without** any prefix or suffix is **bad** and makes it **very difficult** for the engine to detect your voice.

Choices are split with  **;** semicolons, you can say any one of them combined with any **prefix/infix/suffix** that is in **[  ]** square brackets for that voice command.

I've only listed some of them down below so you can understand how they work, there are a lot more available in the profile, but once you understand how these work, the rest will come naturally... :)

## Voice Commands


### Misc

Voice Command  | Voice Test
:------------- | -------------
**Can you hear me** | TTS Microphone Test

### Face Direction Commands

Voice Command  | What it does
:------------- | :-------------
[;fucking; okay] **face that way; face there; look there; look that way; look over there**  | Face to Target
[;fucking; okay] **face the enemy; look at them; look at the enemy**   | Face the Enemy

### Formation Commands
Voice Command  | What it does
:------------- | :-------------
[;form a; make a; return to] [;fucking] **line; line formation; normal formation; standard formation; basic formation**  | Line Formation
[;form a; make a] [;fucking] **shieldwall; spearwall; shields**   | Shieldwall Formation
[;go on; adopt; take on] **loose formation**  | Loose Formation
[;form a; make a] [;fucking] **circle; circle formation; ring**  | Circle Formation
[;form a; make a] [;fucking] **block; square; block formation; square formation**  | Square Formation
[;form a; make a] [;fucking] **wedge; wedge formation;spear; spear formation; skein; skein formation**  | Wedge Formation 
[;form a; make a] [;fucking] **column; column formation**   | Colum Formation 
[;fucking; okay] **scatter; scatter formation; scatter out; disperse**  | Scatter Formation 
 
 
### General Commands

Voice Command  | What it does
:------------- | :-------------
[;fucking; okay] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire**  | Hold Fire Toggle
[;fucking; okay] **dismount; mount; mount up; on your horses; off your horses; get on your horses; get off your horses** | Mount/Dismount Horsies
[;fucking; okay] **take command; on my command; to my command; you're on your own; all yours sarge; you're in charge**  | Transfer Command

 
### Movement Command

Voice Command  | What it does
:------------- | :-------------
[;fucking; okay] **move; go; move there; go there; hold that position; hold this position; hold there; wait there; hold here; stay here; defend this position; defend that position; move to this location**  | Move to Target 
[;fucking; okay] **follow me; on me; to me; come over here**  | Follow Me
[;fucking; okay] **charge;attack; kill them; kill them all; fight; get them; chase them down; hunt them down; run them down; fuck them up; kill the bastards; cut them down; drop them dead**  | Charge
[;fucking; okay] **advance; forward; march; move on; continue; onward; push forward**  | March Forward 
[;fucking; okay] **fall back; move back; back; pull back**  | Fall Back
[;fucking; okay] **stop there; stop moving; hold your ground**  | Stop Movement 
[;fucking; okay] **sound the retreat; retreat; run away; runaway; fucking leg it** |  Retreat

### Unit Selection

Voice Command  | What it does
:------------- | :-------------
[;fucking; okay] **everyone; army; troops; units; all units** [;listen to me]  | Select Entire Army 
[;fucking; okay] **infantry; warriors; fighters; footmen** [;listen to me]  | Select Infantry
[;fucking; okay] **archers; ranged units; crossbows; crossbowmen** [;listen to me]  | Select Archers
[;fucking; okay] **cavalry; knights; horsemen; riders** [;listen to me]  | Select Cavalry
[;fucking; okay] **horse archers** [;listen to me] | Select Horse Archers 
[;fucking; okay] **group five; group fiver** [;listen to me] | Select Group 5
[;fucking; okay] **group six; group sex** [;listen to me] | Select Group 6
[;fucking; okay] **group seven** [;listen to me] | Select Group 7
[;fucking; okay] **group eight; group ayte; group ate** [;listen to me] | Select Group 8
[;fucking; okay] **group nine; group niner** [;listen to me] | Select Group 9
[;fucking; okay] **infantry and archers; archers and infantry**  [;listen to me] | Select Infantry & Archers
[;fucking; okay] **infantry and cavalry; cavalry and infantry**  [;listen to me] | Select Infantry & Cavalry
[;fucking; okay] **infantry and horse archers; horse archers and infantry**  [;listen to me] |  Select Infantry & Horse Archers
[;fucking; okay] **archers and horse archers; horse archers and archers**  [;listen to me] | Select Archers & Horse Archers 
[;fucking; okay] **cavalry and archers; archers and cavalry**  [;listen to me] | Select Cavalry & Archers 
[;fucking; okay] **cavarly and horse archers; horse archers and cavalry**  [;listen to me] | Select Cavalry & Horse Archers 
[;fucking; okay] **infantry archers and cavalry; archers infantry and cavalry; cavalry infantry and archers; cavalry archers and infantry; archers cavalry and infantry**  [;listen to me] | Select Infantry, Archers & Cavalry 
[;fucking; okay] **infantry archers and horse archers; archers infantry and horse archers; horse archers infantry and archers; horse archers archers and infantry; archers horse archers and infantry**  [;listen to me] | Select Infantry, Archers & Horse Archers
[;fucking; okay] **infantry horse archers and cavalry; horse archers infantry and cavalry; cavalry infantry and horse archers; cavalry horse archers and infantry; horse archers cavalry and infantry**  [;listen to me] | Select Infantry, Cavalry & Horse Archers
[;fucking; okay] **cavalry archers and horse archers; archers cavalry and horse archers; horse archers cavalry and archers; horse archers archers and cavalry; archers horse archers and cavalry**  [;listen to me] | Select Archers, Cavalry & Horse Archers



### Single Unit Action Command - Hold Fire

Voice Command  | What it does
:------------- | -------------
[;fucking] **everyone; army; troops; units; all units; men** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Everyone - Fire at will Toggle
[;fucking] **archers; ranged units; crossbows; crossbowmen** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Archers - Fire at will Toggle
[;fucking] **cavalry; knights; horsemen; riders** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Cavalry - Fire at will Toggle
[;fucking] **horse archers; mounted archers** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Horse Archers - Fire at will Toggle
**group five; group fiver** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Group 5 - Fire at will Toggle
**group six; group sex** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Group 6 - Fire at will Toggle
**group seven** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Group 7 - Fire at will Toggle
**group eight; group ayte; group ate** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire**| Group 8 - Fire at will Toggle
**group nine; group niner** [;fucking] **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Group 9 - Fire at will Toggle

### Single Unit Combination Command

Voice Command  | What it does
:------------- | -------------
*[;fucking; okay]* **[everyone;army;troops;units;all units;men]** *[;fucking]* **[move; move there;go there; hold that position; hold this position;hold there;wait there; hold here;stay here;defend this position;defend that position; move to this location]** | Everyone - Move to Target
.
.
. + 59 More available in the profile


### Multi Group Combination Shouts

Voice Command  | What it does
:------------- | -------------
*[;fucking]* **infantry and horse archers; horse archers and infantry** *[;fucking]* **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Infantry & Horse Archers - Hold Fire
*[;fucking]* **archers and horse archers;horse archers and archers** *[;fucking]* **hold your fire; stop shooting; hold fire; stop firing; fire at will; fire; loose; shoot; stop fucking firing; stop fucking shooting; hold your fucking fire; fucking fire** | Archers & Horse Archers - Hold Fire
.
.
. + 35 More available in the profile

Way fucking too many to list all those here (96 of them), just check the profile and you will understand they are easy to use...
