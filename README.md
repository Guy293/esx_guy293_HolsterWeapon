# guy293_HolsterWeapon
Fivem ESX & Non ESX Script for weapon holster

This script will allow an animation to play when drawing your weapon. The Draw is time based and can be configured.

Features:
* (ESX) Different Animations with Police and Civillians
* Prevent FailRP’s
* Set cooldown for drawing weapon

# UseESX
To apply different Holster animations see below:
```lua
Config.UseESX = True
```
Police Pull from Side Holster and Civillians will Pull from back

ESX Dependencies;
* esx_policejob
* es_extended

If you do not have ESX simply apply the following in the config:
```lua
Config.UseESX = false
```
Move Contents into resources folder and add the following to Server.cfg
```
start guy293_holsterweapon
```
Please Do Not Change the name of the Resource. Thank You.
