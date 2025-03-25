 About

This is a fully functional e-commerce website created using HTML, Sass, JS, Node and MongoDB. It is fast, has good SEO and is fully responsive across all screens. It uses Google Maps api to calculate delivery fee and give accurate directions for efficient deliveries. The payment system is powered by daraja api which enables m-pesa, Kenya's most popular payment system. Lastly, It's integrated with Google Analytics and Facebook Pixel to boost sales.
Pre requisites for running repo

    Node JS
    MongoDB
    Redis

NB: These are a MUST and the project won't be able to run without them. Please make sure that they are all correctly installed.
Enabling APIs
1. Google Maps

To enable Google Maps, create a Google Maps api key from Google Developers Console and enable the apis named below:

    Directions API
    Maps JavaScript API
    Places API
    Geocoding API

Copy and paste your api key in the .env file created above.

KEY=YOUR_API_KEY
