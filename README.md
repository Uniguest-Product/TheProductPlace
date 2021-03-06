## SA10 V3.1
*	### Platform
    *	Fully Configurable in Salesforce!! - A first in Uniguest History!  ![Jonah Hill Screaming](JonahHillScreaming.gif)
        *	  Manage Assets remotely from the platform you all know and love.
        *	  Update fleets in bulk with respect to Flag, Brand, and Location.
        *	  Make minute changes to individual assets.
        *   Reference assets in cases to make reporting and tracking escalations easier
        *	  GBC is completely gone, now less mysterious broken assets! 
        ![Blink Blink](BlinkBlink.gif)
   *	Completely New Backend.  
         *   More secure and robust against threats near and far.
   *	All endpoints require a subscription key to accept a request from the client! Not just anyone can send requests to the backend now, you’ve got to be on the list!  
   * Completely scalable cloud architecture! (Shiny!) 
        *	The more instances of SA10 that are added, the more the system automatically scales and allocates processing power on the servers.
   *	New Registration experience for the new SA10!
   *	TOU now has text for dedicated BPS kiosks – Relates SE-1316
   *	Bolded cost and time values in rate card details for TOU so it’s more obvious how much time, service, or other benefits/services are being charged for.
         
         ![Duh](Duh!.gif)
   *	Transaction Lookup Tool now has a new UI with an improved experience! 
   * Session Details are now organized by date/time rather than First In last out order  



*	### Windows Client
    *	Added Serial Number to the help window.
    *	Override for Printer Name, if it’s just a B&W printer, we won’t charge for color prints!


*	### Mac Client
    *	Support for Deepfreeze included in 10.14.

### Support Escalations Adddressed by the 3.1 Release
![Stonks](Stonks.png)
* SE-1316, Session header for TOU on BPS Kiosks
* SE-1505 & 1558, Mac Screensave on system idle
* SE-1044, Suppress updates on session start for Mac


### 3.1.1 Patch
A small patch is being deployed to the fleet currently (As of 12/9). This includes a Client Update as well as a Server Side Update (already done as of 12/5).


#### Backend
* SE-1626 - Services Not Availabe
* * Note: The backend deployment should reduce the amount of issues related to TOU not starting, and having incomplete UI

#### Client
* SE-1604 - Loss of Registration Issues due to file permissions 


### 3.1.2
The 3.1.2 server side update will resolve the issues with Bill-To-Room and is currently behind the 3.1.1 client deployment. This relates to a smattering of support escalations. This list will be updated as more SEs are found that relate to the issues. 
* SE-1621 - Bill to Room does not work on 3.1 Client


### 3.2

* Uniguest Cloud Print - Print files from the internet using a SA10 public use kiosk!
* Browser Compatibility Updates for Unibrowse
* Flexible UI System that supports IHG UI and others!
* SE-1555, Whitescreen issue for low connectivity systems
* SE-1537, Default Weather to Lat/Long instead of HTML5 Geolocation
* News Regionalization and suport for new, news vendors!
* Browser Compatibility Updates for Unibrowse!

