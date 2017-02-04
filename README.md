# Better Buy Orders
Improves Steam market buy orders (hot-swap view different currencies and extended listings)

<img src="http://fat.gfycat.com/LiquidRelievedBarebirdbat.gif"></img>
# What is it?

BBO is a little script this extends the functionality of the "Buy Orders" system on the Steam Community Market. This script uses available data to extend the amount of buy and sell orders seen beyond the standard 5 rows. It also allows for you to quickly change the currency in which you view the buy order system in order to see the distribution of quantity more easily.

As of v1.3, BBO also allows all of these features on item pages and implements the ability to put buy orders on pages that have no items (very rare items etc...)

# How to Install
<a href="https://chrome.google.com/webstore/detail/better-buy-orders/fdohejjlbpikihghncmaejajdbpoiebj">If you have Google Chrome, you can install the up-to-date extension here</a>
 
Better Buy Orders (script v1.4) can be installed on Firefox using <a href="https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/">Greasemonkey</a> on Mozilla Firefox. After you install Greasemonkey extension, just click <a href="https://github.com/Step7750/BetterBuyOrders/raw/master/master.user.js">here</a> and follow the install instructions

# Features
As of v1.5
* Extend the amount of buy and sell orders seen
* Works on commodity, items, and pages with nothing listed
* Allows "hot swapping" of currencies for the tables
* Place buy orders on items without any listings
* Price history graphs now appear on pages with no listings
* Auto-complete market search bar

#Changelog

v1.0.
* Initial Public Release

v1.1 
* Added HTTPS support

v1.2 
* Better Localization Support
* Fixed a bug in the handling of the Polish network response
* Improved the handling of the animation so that it only executes after the request is fully complete

v1.2.5
* Fixes crucial bug for Mac systems (at least on Chrome) that don't properly run the script

v1.3
* Implemented showing more/less buy orders on item pages
* Added currency selector for item pages
* Added the ability to place a buy order on a page with no item listings <a href="http://steamcommunity.com/market/listings/730/AWP%20%7C%20Dragon%20Lore%20%28Factory%20New%29">Example</a>
* Added more/less buy orders on item pages with no items
* Added currency selector on item pages with no items

v1.3.1
* Changes injection timings in order to prevent waiting for the item id on pages with no items

v1.3.2
* The "Activity Feed" on commodity items now reflects the currency selected

v1.4
* Price history graphs now display on items with no listings
* Added the functionality to place a buy order on items that don't have any current buy orders and have no listings
* **NOTE**: Items that have never been sold on the market do not appear to have the ability to have buy orders placed on them (ex. ★ StatTrak Shadow Daggers | Night (Factory New))

v1.4.1
* Implemented prompt for Chrome users to upgrade to the extension version (that is maintained)
* **End of support for the Userscript**

v1.5
* Auto-complete market search bar that works on items that are and aren't listed on the market

v1.5.1
* Fixed HTTPS issue on the front market page for the search bar

v1.5.2
* Fixed bug that would sometimes prevent proper loading of the autocomplete search bar on pages with no listings

v1.5.3
* Updated the item list to include the new "Wildfire" case for the autocomplete search bar

v1.5.4
* Fixed version control issue

v1.5.5
* Fixed a bug that would only allow you to place a buy order on CSGO items without any listings

v1.5.6
* Fixes needless `Market_LoadOrderSpread` calls after Valve's update

#Suggestions/Bugs

Are you encountering a bug or have a suggestion? Please use the available Github panel or contact me on <a href="http://steamcommunity.com/id/Step7750/">Steam</a>


