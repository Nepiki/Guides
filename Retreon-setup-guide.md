# What is Retreon?
It's an app that gives you a dynamic overlay in OBS for the current game you're playing for RetroAchievements.

# Setup
1. Download Retreon from the releases page on https://github.com/spaceglace/retreon/releases

2. Extract the archive.

3. Run the app.

4. It will open a page at http://localhost:3000 in your default browser.

5. Switch to the **Profile** tab.

6. Click **Add Profile**.

7. Enter your RA user name.

8. For the **API Key**, open the **Settings** page on the RA website: https://retroachievements.org/controlpanel.php - and copy the **Web API Key** to the Retreon profile. Click **Submit** to create your profile.

9. Switch over to the **Settings** tab.

10. Add widgets to the right-hand panel. That's the area we will be displaying on the stream.

10a. My personal suggestion would be to add **'Focussed achievement'** and a **'Progress bar'**.

![Layout](https://i.imgur.com/HmR76tz.png)

11. Run any game with RetroAchievements to see how the resulting panel looks. To refresh the panel, switch over to the **Status** tab and press **'Refresh now'**. I'd recommend setting up an auto-refresh interval there.

12. Switch to the **Layout** tab inside the **Settings** tab. Adjust the panel's height and width to your liking.

13. If you're using the **'Focussed achievement'** widget, switch to the **Game** tab and drag-and-drop the achievements on the list so that the achievement you're actively working on is on top of the list. Preferably, put the next one you'll be working on 2nd on the list and so forth.

# Setting up OBS

14. Open OBS.

15. Add a **Browser** source.

16. Put in http://localhost:3000 as the URL.

17. Crop the source in OBS to only show the right-hand panel.