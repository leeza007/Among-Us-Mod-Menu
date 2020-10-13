# Among Us Mod Menu
Mod menu for Among Us For Android

You cannot be the Imposter unless you are the host of the match.

Hacks Provides :-

Self
- Fake Impostor
- No Kill Cooldown
- Show Impostors
- No Emergency Cooldown
- Color Cycler (Constantly Cycle through different player colors)

Player Options
- Teleport to Player
- Teleport to Me
- Freeze Position
- Attach to Player
- Attach Player to me
- Spoof Message ( talk on chat as any other player)
- Kick Player (Kick anyone except for the host)
- Cast Vote
- Report Dead
- Blame Murder Player (Make an impostor other than yourself kill the selected player)
- Murder Player as me (Kill a selected player if you are the impostor)
- Complete Player Tasks

Lobby
- Force Impostor (Host only)
- Attach Lobby Behind
- Teleport All to me
- Teleport All to player
- Freeze All Players positions
- Blame Murder Crew (Make an impostor other than yourself kill the entire crew)
- Me Murder Crew (Make yourself kill the crew if you are the impostor)
- Murder Impostors (Make the impostors kill themselves)

Ship
- Lock All Doors
- Sabotage Loop (Constantly tries to sabotage chosen system and sabotages when 'sabotage' is available in game)
- Sabotage All (Sabotages reactor, comms, lights and o2 all at once)
- Repair (Automatically repair O2, comms and reactor)
- Play Shield Animation (Play the ship task animations to pretend to not be the impostor)
- Play weapons Animation
- Play Trash Animation
- Advertise Menu


Passive features included by default:
- Unlock All Hats
- Unlock All Skins
- Unlock All Pets
- Always Enable Chat
- 10 min Antiban
- See Ghosts
- No Ads

## Injecting Menu
- Compile the a source code and make the apk. Else download the latest prebuild apk.
- Download the real apk and decompile the dex of both the real and this mod apk.
- Copy all smali folders from this mod apk and paste in the real smali folders.
- Navigate to the main activity - com.unity3d.player.UnityPlayerActivity
- Edit "UnityPlayerActivity" and search for requestFocus()
- On the very next line paste this code - "Lheaven/on/fire/MenuMain;->initModMenu(Landroid/content/Context;)V" and then save it.
- Edit AndroidManifest.xml and add this code in the uses permission section - uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW"
- Scroll down and at last paste this line just before the end tags of the xml file (i.e, </application></manifest>) 
- PASTE THIS - service android:name="heaven.on.fire.MenuService" android:enabled="true" android:exported="false"

Note - Give the opening and closing tags of the permission and service section


## Running the menu
- Install the apk
- Accept draw over app permission
- If all goes well, you should see the menu now.

## Credits
- Devilx86
- Rprop And64InlineHook
- Cydia Substrate

FOR RELEASED APK PING ME ON TELEGRAM - @Ascarre and join my channel - @ashopetech
