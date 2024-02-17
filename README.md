# **__Java Local Multiplayer__**

# Requirement
- Any computer (Window, Mac or Linux)
- One Microsoft account with Minecraft Java
- [Prism Launcher](https://prismlauncher.org/download/)

# Setup Tutorial:

### 1. Create Multiple Accounts:
- Open Prism Launcher and go to the account management (click on the arrow in the corner).
- Add offline accounts for each player you want to have. (This can also be online accounts if you have multiple Microsoft accounts that have bought Minecraft).

### 2. Add Modpacks:
- Click on "Add Instance" (top left corner).
- Choose "Import" and paste the URL.
- Repeat this action for the number of players you want in alphabetical order: [A](https://github.com/CoconutsXXS/Minecraft-Java-Splitscreen/releases/download/Modpacks/Local.Multplayer.A.zip), [B](https://github.com/CoconutsXXS/Minecraft-Java-Splitscreen/releases/download/Modpacks/Local.Multplayer.B.zip), [C](https://github.com/CoconutsXXS/Minecraft-Java-Splitscreen/releases/download/Modpacks/Local.Multplayer.C.zip) and [D](https://github.com/CoconutsXXS/Minecraft-Java-Splitscreen/releases/download/Modpacks/Local.Multplayer.D.zip).

### 3. Assign Accounts with Instances:
- Select each instance and click on "Edit".
- Go to "Settings" > "Miscellaneous".
- Toggle "Override Default Account" and choose the account which will use this instance. (Can be an online or offline account)
- Double click on each instance to launch them.

### 4. In-Game Configuration:
- Press F11 in each game to change their disposition.
- (You can change the account in-game by clicking on the square button next to the mod button. This is optional.)
- To play with your controllers, go to "Options..." > "Controls..." > [The squared controller button], set mode on "Controller", enable "Virtual Mouse" (if it is not already done). Go to "Controller Options" and switch the current controller to your desired controller.

### 5. LAN or WEB Server:
LAN: Quickest but Resource-Intensive Alternative.
- On one of the instances, create a new world or open the "Test World". Once it is opened/generated, go to the options (escape key) and click on "Open to LAN". Disable the "Online Mode", customize your parameters, and click on "Start LAN World".
- Optional: Few seconds after starting the LAN world, the web address of the server should appear in green in the chat. (This is a # followed by random words) Click on it to copy it; you can share it with any non-local player to allow them to join your LAN server.
- In each other game, go to "Multiplayer" and join the LAN server. (It automatically appears in the servers list)

WEB: Longest but Optimized Alternative
- Create an Aternos.org account and create a new server.
- On the principal server menu, below "Software", click on "Change" and select "Fabric" with the version 1.20.1 (0.15.6).
- In the "Mods" menu, search and add the "Fabric Tailor" mod in version 2.1.2.
- In the "Options" menu, enable "Cracked". (Don't worry, this just allows offline accounts to join it.)
- Launch the server and copy its address.
- In each game, go to "Multiplayer" and join the server via the copied address. (The free server will automatically stop if there is no player in it.)



## Important Key Binds:

- Change split-screen disposition: F12
- Open skin changer menu: M (Works only in servers or local worlds which have the "Fabric Tailor" mod)



## Problem Solving:

"Invalid Session," "Invalid Token," or "Failed to Verify Username":
- The server you are trying to join does not accept offline accounts. If you are the owner, go to the parameters and disable the "Online Mode."

"Username Already Taken":
- Another player in the server has the same name as you. Offline accounts can have any name contrary to Microsoft accounts, which may cause conflicts. Verify if your opened instances are not logged in the same account (top left corner in the main menu). Add another offline account in Prism Launcher (with a more unique name) and log into it by clicking on the square button next to the mod button (In the main menu).

I can't press F12 on a Mac Keyboard:
- Press the fn key + F12. If you don't have the fn key, go to System Preferences, in "Keyboard", toggle "Use F1, F2, etc., as standard function keys" and retry.

How to hide Dock and Sidebar on Mac:
- Go to system preferences, in "Dock and Menubar," and toggle "Hide/Show automatically Menubar on the desktop" and "Hide/Show automatically the Dock."
