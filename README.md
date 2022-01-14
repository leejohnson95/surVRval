<img src="https://github.com/leejohnson95/surVRval/blob/main/IMG_5863.jpg" alt="survrval logo" style="width:200px;height:auto;">
<h1>surVRval a virtual reality open world survival game</h1>

Current version: 0.0.1
Build tested on: Oculus Quest 2

<h2> How to install </h2>

<a href="https://github.com/leejohnson95/surVRval/releases/download/v0.0.1/testBuild_v0.0.1.apk"> Download the APK here </a>
failover link: https://github.com/leejohnson95/surVRval/releases/tag/v0.0.1

Once you download the APK, you can install it onto your Quest 2 by following this guide.
https://headjack.io/knowledge-base/how-to-easily-sideload-a-vr-app-to-oculus-quest-2/

Once you have sideloaded the APK, the game should be available to start by going to your oculus library, and choosing the unknown sources filter (top right, click all and then change to unknown sources)

Click on SurvRval, and the game should load.

<h4> Be aware this is a early alpha release build and there will be bugs and issues </h4>

Enjoy!



<h2> Implemented features; </h2>

- VR Hands tracking and movement
  - provided by autoHands, Full realistic physics movement and hands tracking
- Player movement
  - Walking
  - Full range movement and tracking
  - climbing (go climb the white tower)
- Player vitals
* Player can consume consumables by eating and drinking in VR, bring the consumable to your mouth and your player will consume the item to gain its benefits
  - Health
    - drains over time if hunger or thirst is empty
    - will restore if player is healthy (thirst and hunger over a certain %)
  - Hunger
    - drains over time
  - Food
    - drains over time
- Player UI
* Can shown/hide by pressing the oculus menu button (left controller)
  - Player vitals
  - resources (inventory)
- inventory
* For resource gathering only, picked up resource items can be stored in the inventory by putting them in the inventory (over players right shoulder)
  - Wood
  - Metal
  - Stone
- Backpack
* Physical backpack can be picked up and items can be stored
  - Can store consumables, weapons and other items
- Holsters
* Player has two holsters which can be used to store ANY items by the users side for quick access
- weapons
* Weapons can be used to apply damage and gather resources from certain trees or ore nodes(stone, metal)
* Each weapon has a hit buffer which controls how fast you can deal damage or gather resources, stopping spam resource and damage hitting
  - axe
    - One Handed
    - can harvest wood from trees
  - pickaxe
    - Two handed
    - can harvest stone from stone Ore
  - Club
    - One handed
  - Large Stick
    - Two handed
- Consumables
  - Thirst
    - Water
  - Hunger
    - Chicken drumstick
  - Health
    - Mushroom
- Resources
* these are single use resources that can be collected and stored in the players inventory
  - Wood Stick
  - small rock
