# Clip Player
Based on Random Clip Player: https://github.com/ShaderWave/RandomClipPlayer

# Setup
You are required to create a Twitch developer application in order for this to function. If you have already created one and have the Client ID and Client Secret, skip to Step 8.

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
