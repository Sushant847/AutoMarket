Project: AutoMarket

Purpose:
Interactive Australian used-car exploration prototype.
See a used car, enquire about condition, book a viewing, or list a car.
The site does not complete a purchase or take payment.

How to open:
Unzip this folder and open index.html in Chrome or Edge.

Technologies:
HTML5, CSS3, JavaScript, Chart.js (CDN)

Data:
Australian Vehicle Prices (2023). A sample is embedded in js/vehicles.js
so the site runs from a ZIP without a server.

Architecture:
Client-side / server-independent prototype.

Storage (this browser only):
- demo accounts
- recently visited vehicles
- locally created listings

Important limitations:
- Not a live marketplace
- No production authentication (passwords stay in localStorage)
- Contact and viewing forms do not email a live server
- Chart.js and Google Fonts need internet if those assets are not cached
- Asking-price check is an indicative dataset comparison, not a valuation

Ten core pages:
1 Home
2 Browse
3 Details
4 Compare
5 Price checker
6 Brands
7 Locations
8 Insights
9 Features
10 About (includes privacy and security)

Supporting pages: Sell, Contact, Log in, Sign up
