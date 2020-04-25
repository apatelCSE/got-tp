<h1>Got TP?</h1>

<h2>The Main Idea</h2>
<p>The vision for my web app is a platform that helps shoppers find the 
    essential items they need during the COVID-19 crisis. Minimizing social 
    contact is essential during these unprecedented times, which is especially 
    difficult when families must visit multiple stores to find the household/
    cleaning essentials they need. Got TP? is a data-driven solution that 
    allows shoppers to input in-stock items from their latest shopping trip, 
    which helps other users searching for the items they need to plan their 
    shopping trips safely and effectively.
</p>

<h2>The Implementation</h2>
<p>My app has two user functions: to search for items in the nearby area or to
    input available items at the store they've recently visited. The app uses 
    the Radar API to detect when a user has entered a store (geofence). The app 
    then alerts the user when they have left the geofence and asks them if they 
    would like to input items from their last visit. The store information and 
    available items are stored in a database, which are pulled when another user
    searches for the items they are looking for. The app then lists the stores
    (geofences) nearby that have the item(s) available in stock.
</p>

<h2>Further Development</h2>
<p>The current solution is limited by my programming experience. As a web app, 
    Got TP? could be better implemented using React to improve the app's 
    structure. Further development into an IOS/Android app would use the Radar
    SDK to create push notifications that alert users when they have left an
    indexed store or alert users when they are near a store that has an item on
    their wishlist.
</p>
