# Animal Crossing: New Leaf but poorly translated (working title)
This is a (Work In Progress) poor translation of [Animal Crossing: New Leaf](https://en.wikipedia.org/wiki/Animal_Crossing:_New_Leaf) for the [Nintendo 3DS](https://en.wikipedia.org/wiki/Nintendo_3DS) [console](https://en.wikipedia.org/wiki/Video_game_console). As of now, it's planned to just replace the text, however changing the graphics may be considered.

# I need YOU!
As of right now, there's a very high chance for this to take actually forever, so I need someone who knows how this video game handles text, specifically the `Talk` folder. So, **what** exactly do I need? Simple. As of right now, I'm using [MSBT Editor Reloaded](https://github.com/IcySon55/3DLandMSBTeditor/releases/) on a Windows 7 virtual machine. This seems to be able to get the job done for the most part. Well, until I tried to edit Kapp'n's song. Editing this seems to be a complete nightmare, and I can't wrap my head arround it. That's where you come in (I hope). I have a very simple request:

### My request
I need software that is able to edit New Leaf's `.msbt` files. More specifically, I would like it to be able to allow the user to edit the text, and have the software able to handle the hex part. It should also be able to change the colour of a word in a user friendly way. There is a chance that some files require different types of hex (or identifiers, I don't know what it is), or none at all, so there should be a way for the user to choose the mode based off of the file in question. I.E, there could be one mode called `Villager text` and another one called `Kapp'n Song`, and each will make the text work in those areas.
A few other things I would like include:
* The software should be able to work on Windows 7 and up, GNU/Linux (Debian, Ubuntu or any variations of them, i.e Linux Mint) or both. Debian and Linux Mint are my daily drivers (depending on what PC I'm using), however I can set up a VM in case making a Linux version ends up being too complicated. The choice is up to you
* The software should be open source. Please. I like open source software.
* It should be quite user friendly. I'm a dumb dumb and I have no idea what I'm doing.
* It shouldn't take up too much RAM. This isn't Google Chrome.

If you're interested, please get in contact, either via Twitter DMs ([@vilijur](https://twitter.com/vilijur)), GitHub, or Discord (vilijur#4481). If these ways to contact me don't work, open an issue and mention me in it.

Okay, that's it, you can continue reading the readme.

(P.S, if this software that I'm looking for exists, please let me know.)

# ⚠**WARNING**⚠
This mod was made based off of Animal Crossing: New Leaf - Welcome amiibo (EUR), and as such, the Title ID in the `luma` folder is for that game. If you do not have Animal Crossing: New Leaf - Welcome amiibo (EUR), you can change the Title ID to the version of your game, however this may cause more unexpected issues. **PROCEED AT YOUR OWN RISK**

# Some questions, and some answers!

### What the hell is this?
Well, it's just me taking Animal Crossing: New Leaf and throwing it into [Google Translate](https://translate.google.co.uk/). That's it.

### How do I install it?
**Since this is a modification of the European/PAL files, these instructions will assume you're using the European/PAL version of Animal Crossing: New Leaf - Welcome amiibo.**
**If `Enable game patching` is already enabled, skip step 1**

1. Make sure you have a [hacked 3DS](https://3ds.hacks.guide) with [Luma3DS](https://github.com/LumaTeam/Luma3DS) installed. If your 3DS is on, turn it off, then press and hold `SELECT`, then press the power button. You should be in the [Luma3DS configuration screen.](https://github.com/LumaTeam/Luma3DS/wiki/Optional-features) Press down on the `D-Pad` once, then press `A`. This will turn on `Enable game patching`, assuming it hasn't been enabled yet (You'll know if it's enabled if `(x)` is shown before `Enable game patching`.). Press `START` to save, then turn off the 3DS. Remove your SD Card from your 3DS and insert it into your computer.

2. Download the `.zip` file from the latest [pre-release](https://github.com/vilijur/acnl-translated/releases), and extract it to the root of your SD Card. If it asks to merge, select yes. Allow it to replace any files, if asked. Then, insert your SD Card back into your 3DS.

3. Start up `Animal Crossing: New Leaf - Welcome amiibo`. If the menu says `According to Ⓐ`, you're done! Enjoy the unfinished translated mess!

### How do I know if I have the Welcome amiibo release or not?
Have a look at the game's icon. If the background is **green**, you have the orginal game. If the background is **white**, you have the Welcome amiibo release. If you have the orginal game, make sure to change the Title ID in the `titles` folder found in the `zip` file to that of your game (You can find the Title ID by using [FBI](https://github.com/Steveice10/FBI). Open FBI, go into Titles and look for `Animal Crossing: New Leaf`. You'll see the Title ID on the top screen.) This also applies if you're not using a Europian/PAL copy of AC:NL.

### Isn't the warning a bit too dramatic?
Yeah. It is.

### How will you go about making this publically avalible?
At first, I'll do pre-releases, each of them containing one file that has been translated (I.E. The frst pre-relese will have `SYS_2D_UI.umsbt`, while the next may have another one). After all the text files have been poorly translated, the first offical release will be.. well, released. After that, I'll turn my attention to changing the graphics, which will take more time. After all graphics are complete, I'll consider making a `.cia` release, with a different TitleID to Animal Crossing: New Leaf - Welcome amiibo (EUR) (You'll be able to use it on any region, though). The `.cia` release may not be public for a while, however this is still up in the air. **This plan is subject to change**

### You mention a `.cia` release. Will you change the game icon and banner?
Yes! I plan to make the banner's icon (the one you see on the top screen) the same as the poorly translated title screen graphic in game. As for the game icon on the bottom screen, I'll replace it with this:

![The icon I plan to use.](https://github.com/vilijur/acnl-translated/blob/main/acnlwatr3.png)

### How long do you think it will take to finish this?
I say about a year or two minimum. Animal Crossing: New Leaf is a very text heavy game, and the `Talk` folder is scaring me with how many files there are.

### Why is some of the text not translated?
It's nowhere near complete, and some text is in other files that have not yet been translated. Though, if something's apart of one of the avalible translated files and isn't translated, open an [Issue](https://github.com/vilijur/acnl-translated/issues/new) with the `bug` tag, provide where the text isn't translated (I.E in a menu) and I'll get to it as soon as posible.

### Some text is duplicated, why is that?
The text must be too long. Please open an [Issue](https://github.com/vilijur/acnl-translated/issues/new) with the `bug` tag, include **where** in the game this issue appears and I'll look into it as soon as I can.

### Some of the text goes off screen or gets cut off.
Seems like I need to retranslate that part, make it shorter or reformat it. You can inform me of this by opening an [Issue](https://github.com/vilijur/acnl-translated/issues/new) with the `invalid` tag, give details on what part of the game this issue happens at, and I'll look into it as soon as I can.

### I have a suggestion, where should I put it?
Any and all suggestions are welcome! Just make a [new Issue](https://github.com/vilijur/acnl-translated/issues/new) with the `enhancement` tag. Don't be vauge, though.

### Why is it taking so long for something to get done?
I'm (for the most part) the only one working on this, as a hobby. It's for fun, and nothing more. Plus, basiaclly everything is self taught. Of coruse, with one person who don't know what they are doing sometimes working on changing all the text in a text heavy game like Animal Crossing: New Leaf, it's gonna take a while for things to get done. 

### How do I keep up to date on the project?
[On this here Twitter account, ran, owned and entirely made by me! No phone number required!](https://twitter.com/translatijur)

### My question isn't answered here!
If you have any questions that are not answered here, either drop me a Discord DM (vilijur#4481), Twitter DM ([@vilijur](https://twitter.com/vilijur), I do not recommend contacting me this way), or make a [new Issue](https://github.com/vilijur/acnl-translated/issues/new) with the `question` tag (You should also add `@vilijur` in your Issue so I can get to it a little bit quicker). Keep in mind that it may take a while for me to repsond, depening on how you choose to contact me. Also don't ask for my email, I am not a business.

### What's the fastest way to contact you?
I'd say Discord would be fastest, since I use that app too much (oh god someone help me)

### What folder are you working on as of now?
Right now, I'm working on [the MailN folder](https://github.com/vilijur/acnl-translated/wiki/The-Script-folder#mailn-and-mailr), or trying to at least.

### How many spelling mistakes do you make
Wayyyy too many.

### Hurry up.
That's not a question.

# Documentation
I do plan to document the prosess so that others can do not just text hacks, but also ROM hacks for Animal Crossing: New Leaf. As of right now, that documentation does exist but barely. You can check it out [here.](https://github.com/vilijur/acnl-translated/wiki)

# Credits
This is where I credit people for their work on this project, because I don't want to take all the credit. Well, assuming I end up doing all of this on my own. So far, the credits area as follows:

basically everything - [vilijur](https://github.com/vilijur)

# That's it
You can get on with your day now. **:>**
