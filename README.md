# Clip Player
Based on Random Clip Player: https://github.com/ShaderWave/RandomClipPlayer by ShaderWave

This edited version of Random Clip Player I made for me and some friends. The file picks a random user from the USERS array and takes 100 clips from the user's channel. Then it randomly picks one of those clips to play. After a clip it plays, it picks a new user and picks one of the new user's clips. The script has a form of duplicate user protection, so you won't get a clip from the same person twice.

# Setup
You are required to create a Twitch developer application in order for this to function. If you have already created one and have the Client ID and Client Secret, skip to Step 7.

Visit https://dev.twitch.tv/ and Login.
1. Press "Your Console" in the top right.
2. Under "Applications" press "Register Your Application"
3. Give it any name, it doesn't matter. Select the most appropriate category, or just "Other."
4. As an "OAuth redirect URL" is required, enter a link to any website - preferably one you own, or just enter a link to google (https://google.com/). The app doesn't use this so it's not important.
5. Press "Create"
6. Once created, press "Manage" and scroll to the bottom of the page. Take note of the "Client ID" and "Client Secret" (press new secret if there isn't one there)
7. Now, download the viewer.html file from here. Save this file somewhere accessible.
8. Open the viewer.html file in a text editor of your choice.
9. In CLIENT_ID and CLIENT_SECRET enter the Client ID and Client Secret respectively, between the quotes.
10. Add the different channels you want to have clips played of in the USER array.
11. Adjust any of the other settings as you wish.
12. Once this is complete, save and close the file.
13. In OBS/other streaming software, simply add this file as a Browser Source. You may need to tick "local file" in order for this to be possible.
14. In OBS, adjust the width and height of the Browser Source in the "Properties" panel rather than scaling it, this ensures that the clips play at the highest possible quality without becoming blurry when scaled.
15. Optionally, you may also want to consider enabling "Shutdown source when not visible" and "Refresh browser when scene becomes active" for the most flexibility.
