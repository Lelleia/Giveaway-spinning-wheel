# Giveaway-spinning-wheel
A simple spinning wheel for giveaways made through twitch.

How it works:
Viewers type in Twitch chat: !giveaway John, and "John" gets added to the sidebar participants list.
The wheel updates with slices representing each participant’s name.
Press the 'Spin' button to spin the wheel.
---------------------------------------------------------------------------------------------
1.
What you need to do:
-Replace 'your_channel_name' with your Twitch channel name, all lowercase.
-Open this HTML file in a browser.
-Make sure your Twitch chat is active and sending !giveaway <name> commands.
---------------------------------------------------------------------------------------------
2.
-Add Browser Source in OBS
-Open OBS.
-Click the + under Sources → choose Browser.
-In the URL field, enter your hosted URL, e.g. http://localhost:8080/ or GitHub Pages URL.
-Set width/height to match your HTML canvas (e.g., 1280x720 or 800x600).
-Make sure “Shutdown source when not visible” is unchecked (to keep chat connection alive).
Click OK.
---------------------------------------------------------------------------------------------
3.
-Make sure your Twitch channel is connected
-The spinning wheel uses tmi.js to connect to your Twitch chat.

Important:
The HTML runs in OBS browser source (Chromium-based), so it needs internet access.
Your Twitch channel name must be correct in the script.
Twitch chat will be monitored, so when viewers type !giveaway <name>, the wheel updates live in OBS!
---------------------------------------------------------------------------------------------
4.
ALTERNATE: Test It
Open your Twitch chat.

Type: !giveaway Alice

Check your OBS overlay — the name “Alice” should appear on the right and on the wheel.

Click the Spin button in the overlay or trigger spin remotely (more advanced).
