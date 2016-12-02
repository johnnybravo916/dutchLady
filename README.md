# dutchLady
Dutch Lady Advertisement

Expansion size and direction
300x250 creatives should have maximum expansion of 500x250 left and right.
Close button required on the expanding panel
All expanding creatives types should include a way to collapse the creative.
Hit area/hot spot size for expansion should no more than 25-33% of the unexpanded area of the creative.
Close button shouldn't overlap the expansion hit area.
This best practice prevents the creative from immediately re-expanding after a user clicks the close button.
Expand/collapse methods should match
If an ad is click-to-expand, then it should be click-to-collapse. If an ad is rollover-to-expand, then it should be roll-off to collapse.
Pre-expand (automatically expanding) creatives must auto-collapse after 15 seconds
This follows the same 15-second animation guidelines.
If a user interacts with the ad, the ad may remain open.
If pre-expand creatives don't trigger the rich media expansion timer:
Remember: The rich media expansion timer can only be called on an expansion triggered by a user interaction.
Use the startExpanded() call to pre-expand your creative. See the Expanding build guide for more information.
The div layer of a webpage must collapse on your creative's collapse


Non-expanded size: 300 x 250px (h) - 200kb excluding video
Expanded size: 500 x 250px (h) - 2.2 MB
Expansion direction: LEFT
Border: A 1px #333 border is required for all banners (top-most layer)


Non-expanded banner will need to have a Rollover to expand button (GWD has a control that can trigger this)
Expanded banner will need to have a Close button (in GWD too)
Call To Action button (Find out more) will need to have a clickTag overlay (in GWD)

There is also a slight change with the first frame:
1. Display city and weather condition for tomorrow only–no more temperature
2. Weather condition can be categorised this way:
     - If cloudy or thunderstorm -> Thunderstorm
     - If sunny or partially cloudy -> Sunny
     Let me know what the API parameters are and we can tweak accordingly.
3. There's also an additional line below 'Tomorrow's forecast' that says 'Stuck at home?', 'Nowhere to go?', 'Wondering where to go?' and 'Wondering what to do?'. Each of this line should be loaded depending on the randomisation result for each weather and activity. i.e. they should match according to the PSD.