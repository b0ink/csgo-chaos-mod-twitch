# CS:GO Chaos Mod Twitch Overlay

Please keep in mind before using: THIS APP IS NOT PERFECT (yet). IT IS BUGGY. IT WILL BREAK.

(Will be open sourced once the app is cleaned up and refined)

## Download
- Download the latest release: https://github.com/b0ink/csgo-chaos-mod-twitch/releases

## Installation
- Download the latest release and extract the zip file, and run the .exe setup wizard.

## Integration
- Enter your twitch username and twitch channel (often same as your username), and generate an OAuth password from https://twitchapps.com/tmi/ using your twitch account to authorize.
- Enter in your CS:GO server's IP, Port, and RCON passowrd, and press 'Connect'
- 2 Green ticks will be displayed if the connections were successful, and an 'Open Voting' button will appear. Click that button to open the voting panel.

<p align="center">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Setup_1.PNG" 	width="250" title="Setup">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Setup_2.PNG" 	width="250" title="Setup">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Setup_3.PNG" 	width="250" title="Setup">
</p>

#### If an error occurs, ensure you have the correct Rcon details and that it is enabled on the CS:GO server
<p align="center">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Setup_4.PNG" 	width="250" title="Setup">
</p>

### Voting
If the ConVar `sm_chaos_twitch_enabled` is set to 0 (disabled), the voting panel will prompt you to enable it VIA Rcon. Once enabled, a row of effects should be displayed. The first set of effects will be run on round start

<p align="center">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Voting_1.PNG" 	width="250" title="Setup">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Voting_2.PNG" 	width="250" title="Setup">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/Voting_3.PNG" 	width="250" title="Setup">
</p>

### OBS
Below is a setup on keying out the green from the voting panel, apply a Colour Key filter to the window capture of the voting panel.

<p align="center">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/OBS_1.PNG" 	width="550" title="Setup">
	<img src="https://csgochaosmod.com/gallery/twitch-overlay/OBS_2.PNG" 	width="550" title="Setup">
</p>


If you experience any weird bugs or errors hit Ctrl+R to reload the app and reconnect to the server.

Only known issue is an error box popping up when the server goes down and breaks the RCON connection.
