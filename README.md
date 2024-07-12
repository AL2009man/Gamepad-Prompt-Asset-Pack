# Gamepad Prompt Asset Pack by AL2009man

![Gamepad Prompt Asset Pack promo alternative](https://github.com/AL2009man/Gamepad-Prompt-Asset-Pack/assets/67606569/aa1b6e48-1bf1-4c03-be96-5c5def124516)

This collection of Controller Prompt icons is intended for modularity while having the look and feel of Steam Input API button icons. 

Download: [CLICK ME](https://github.com/AL2009man/Gamepad-Prompt-Asset-Pack/releases/latest/download/Gamepad.Prompt.Asset.Pack.zip)


---

# Asset List:

**Controller Prompts**: 
* Shared/Generic
  * Universal Face Button, Apple MFi
* Xbox
  * Xbox Wireless Controller, Xbox Elite Controllers, Xbox 360 Controller
* DirectInput
  * Up to 32 button prompts
* PlayStation
   * DualSense, DualSense Edge, DualShock 4, DualShock 3
* Nintendo
   * Nintendo Switch Controllers, Wii Controllers, GameCube Controller
* Steam
   * Steam Deck, Steam Controller

---


# FAQ

For FAQ: most of the answers will reside within the Gamepad Asset Pack, however: there will be questions specific to this pack.

### Question 1: What's the purpose of this Asset Pack?

A: This version is intentionally designed to be similar to Steam Input API's built-in button prompts but with the same modularity principles as Gamepad Asset Pack. This is originally inspired by icculus's [ControllerImage](https://github.com/icculus/ControllerImage) and SteamInput prompts 

### Question 2: Why is this pack separated from [Gamepad Asset Pack]?

This pack is intentionally designed to allow game developers/modders to utilize this pack, even in commercially sold games. In order to achieve this: 98% of the assets was recreated by scratch, while taking notes/inspiration from Steam Input's button prompts. However, only 2% of it is reused from Gamepad Asset Pack, inorder to speed-up creation time. It might still be using licensed stuff taken from it- but it'll be replaced in future versions.


### Question 3: What does pack this include?

A. The vast majority of Xbox, PlayStation, Nintendo and Steam's family of input devices prompts are available, but all of them will be shared within one "Shared" file that will cover the standard gamepad prompts (More on that on Question 4!), more Input Types are coming soon.

For specific prompts like the Face buttons: we have alternative versions of each button prompt, so if you want the colored version of the A button or the defaulted transparent A Button...or you just want the "South" Button; you can use those prompts that suit your specific needs...or can't be bothered to support every Controller Types.

![buttonpromptvariants twitter fix](https://github.com/AL2009man/Gamepad-Prompt-Asset-Pack/assets/67606569/7219446d-61e7-4ad5-bb48-29639adb86a9)


Every prompt image will come with three variants: the "Transparent" style, the "Black" style and the "White" style. Depending on what kind of prompt you wanna show in a specific UI color language: these will be sutied well.

![buttonpromptvariants1 twitter fix](https://github.com/AL2009man/Gamepad-Prompt-Asset-Pack/assets/67606569/49d4c977-a27e-4e4b-a77b-d11c9db5a56b)

These variants will be included within a single image file's group/layer, using with the same principles set in the Gamepad Asset Pack.

![Button Prompt style switch](https://github.com/AL2009man/Gamepad-Prompt-Asset-Pack/assets/67606569/8b0bd9eb-4f3f-447e-b38d-ece9860de70b)


As of this writing: versions of the Trackpad/Touchpad, platform-specific Home/Alt buttons and Paddle buttons is not in this collection; but will come in a future update.


### Question 4: What's up with "Shared" file?

Inspired by Steam Input API's `shared` prompts and [ControllerImage](https://github.com/icculus/ControllerImage), I decided to have one "master" file that covers all Controller Types. For example: most of the "XInput-centric" button prompts will be in the Shared file, while Xbox-specific prompts will be on it's own dedicated "`Xbox`" file. Similar case with Nintendo prompts and tiny portions of PlayStation prompts. Hence; you'll see a "shared" name (or other gamepad type's names) on the title of each file.

**If you wanna use those button prompt images**: you can take one of the images and placed them in your game/mod project's button prompt file/directory and customize to your wishes.

**If you're planning to have a dynamic button prompt detection system based on Controller Type**: make sure you set a system where it can grab closer equivalent prompts.


### Question 5: Which Image Editor, File Format, and Fonts were used for this asset pack?

This asset pack was created using [Inkscape](https://inkscape.org/). 

All images formats are Inkscape SVG. For Image Editing: I recommend Inkscape for the best experience.

[Open Sans](https://fonts.google.com/specimen/Open+Sans) font family (by Steve Matteson) is used to display the lettered Symbols.


---

# Guideline

### Question 1: Can I use this Asset Pack for my personal or community-driven projects? (i.e Gamepad overlay, custom image, mods, reverse-engineered project, fan project)

As long as you credit this project (as per [MIT License](https://github.com/AL2009man/Gamepad-Overlay-Asset-Pack/blob/main/LICENSE)), sure.

### Question 2: Can I use this Asset Pack for my commercially released game/planned to be released commercially? (i.e.: releasing on Steam, GOG, Epic Games Store, Microsoft/Xbox Store, PlayStation Store, etc.) 

99% of the assets can freely be used, with a sole exception for platform-based Guide buttons.

### Question 3:  Console Certification has failed due to mismatched button prompts. 

Please report this issue directly to [this issue report page](https://github.com/AL2009man/Gamepad-Prompt-Asset-Pack/issues/6) and I'll try to address them as best as I can. I can't fully guarantee you that a specific fix will give them an A-OK from the Console Manufacture.
