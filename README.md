<div align="center">
    <div class="header">
        <p>
            <h1 style="display:inline;text-size:24px;"> Advanced Keypad</h2>
            <span style="float:right">Using UI!</span>
        </p>
    </div>
    <!-- build status badges here thanks -->
    <hr style="width:50%" />
    <br />
    <br />
</div>

![SimpleKeypad](https://github.com/itsKatVR/vrc-simple-keypad/assets/77287432/a26c68f7-dff5-41f1-8503-ec024e4e5241)

## Introduction

Advanced Keypad is designed for UdonSharp, and a step up from [Simple Keypad](https://github.com/itsKatVR/vrc-simple-keypad/releases/latest)!

## Requirements
A project with the latest VRChat SDK3 Release- can be found below:

[UDON](https://vrchat.com/home/download) (Udon Worlds Latest Release)

[Udon Sharp](https://github.com/vrchat-community/UdonSharp/releases/tag/v0.20.3)

## Installation

1. Install VRChat SDK3, UdonSharp, and latest release of [Adv Keypad](https://github.com/itsKatVR/vrc-adv-keypad/releases/latest)!
2. Inside of the "AdvKeypad" Folder you will find the Prefab.
3. Drag KPAD (Prefab) into Scene.

## How it works
Set a passcode, enter passcode.

`Passcode: 123456`
`Master Passcode: 654321`
`Temp Passcode: 9999`

`Temp Objects, General Objects, Master Objects.`

Let's start with `General` objects, these are objects that are enabled/disabled based on correctly entered `passcode`.

`Master` objects, enabled/disabled objects based on a Master Code input. `Master Passcode` allows you to set a Temporary passcode, to be used for that instance only.
This can be given out to anyone, to give them General & Temp Object access.

You can click the dropdown for "Users" to specify usernames that will automatically have access to the toggles without the need to input the passcode each time!

How do I know I've entered the correct code? - "ACCESS" will turn Green on valid input, and Red on invalid input.

![AdvKeypad_U#_Example](https://github.com/itsKatVR/vrc-adv-keypad/assets/77287432/cee55685-3862-42f8-9cef-476052a997f2)

## Customize
Can I change the color? Yes!
Inside of the prefab, after you have unpacked it. 
You can select each Parent Object named 0_Button - Enter_Button,
There should be an "Image" UI element inside each, select all of these- and then modify the color in inspector.

## Something needs fixed?
Sprite Editor! In some projects, it may require you to install 2D Sprite through your Package Manager. If this is the case, please follow steps to install.

Also, note that the Sprite used for the Borders uses a `9, 9, 9, 9` Border setting.

![SimpleKeypad_SpriteExample](https://github.com/itsKatVR/vrc-simple-keypad/assets/77287432/5097f7fa-470b-4b86-8e34-e95b7931c2ec)

```
$ ./That one time at band camp.
```
