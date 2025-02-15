# Akamai-3.0
I made a script for generating the Akamai sensor_data + 'akamai-bm-telemetry', used in retrieving the '_abck' cookie. Language: NodeJS.

Contact: 
- Telegram: @taurinedev

About the script:
It only generates the sensor_data and the 'akamai-bm-telemetry' header, thus I sell it for rather cheap compared to other coders.

Depending on your site of choice, additional challenges may be imposed by Akamai, so for most sites this won't be enough.
Akamai's latest 3.0 version antibot utilizes an algorithm which encrypts the sensor, it's implemented here as well as everything else.

Due to the unique nature of canvas FP and mouse movements, you need to add them yourself.
I did include my mouse-move algorithm which you can use or adjust (not perfect)

Usage:
(url is your url. from the intial GET request you can get the two cookies)
get_sensor(_abck, _bm_sz, url)
You need a custom HTTP client that mimics the JA3 & HTTP2 fingeprints of a real browser for making requests to all protected endpoints. A lot are available on Github for free.
[more info on HTTP Fingerprinting](https://tls.peet.ws)

Example output from the function:
3;0;1;0;3553328;jI......IK

Pricing:
Your offer.

If you are interested or have any other requests, feel free to PM me.


 

