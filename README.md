# dutchLady
<h2>Dutch Lady Advertisement</h2>

Expansion size and direction<br/>
300x250 creatives should have maximum expansion of 500x250 left and right.<br/>
Close button required on the expanding panel<br/>
All expanding creatives types should include a way to collapse the creative.<br/>
Hit area/hot spot size for expansion should no more than 25-33% of the unexpanded area of the creative.<br/>
Close button shouldn't overlap the expansion hit area.<br/>
This best practice prevents the creative from immediately re-expanding after a user clicks the close button.<br/>
Expand/collapse methods should match<br/>
If an ad is click-to-expand, then it should be click-to-collapse. If an ad is rollover-to-expand, then it should be roll-off to collapse.<br/>
Pre-expand (automatically expanding) creatives must auto-collapse after 15 seconds<br/>
This follows the same 15-second animation guidelines.<br/>
If a user interacts with the ad, the ad may remain open.
If pre-expand creatives don't trigger the rich media expansion timer:<br/>
Remember: The rich media expansion timer can only be called on an expansion triggered by a user interaction.<br/>
Use the startExpanded() call to pre-expand your creative. See the Expanding build guide for more information.<br/>
The div layer of a webpage must collapse on your creative's collapse<br/>
<br/>
<br/>
<ul>
  <li>Non-expanded size: 300 x 250px (h) - 200kb excluding video</li>
  <li>Expanded size: 500 x 250px (h) - 2.2 MB</li>
  <li>Expansion direction: LEFT</li>
  <li>Border: A 1px #333 border is required for all banners (top-most layer)</li>
</ul>
<br/>
<br/>
Non-expanded banner will need to have a Rollover to expand button (GWD has a control that can trigger this)<br/>
Expanded banner will need to have a Close button (in GWD too)<br/>
Call To Action button (Find out more) will need to have a clickTag overlay (in GWD)<br/>
<br/>
<strong>There is also a slight change with the first frame:<strong><br/>
<ol>
  <li>Display city and weather condition for tomorrow only–no more temperature</li>
  <li>Weather condition can be categorised this way:<br/>
     - If cloudy or thunderstorm -> Thunderstorm<br/>
     - If sunny or partially cloudy -> Sunny<br/></li>
  <li>here's also an additional line below 'Tomorrow's forecast' that says 'Stuck at home?', 'Nowhere to go?', 'Wondering where to go?' and 'Wondering what to do?'. Each of this line should be loaded depending on the randomisation result for each weather and activity. i.e. they should match according to the PSD.</li>
</ol>