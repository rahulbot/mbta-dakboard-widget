MBTA DAKBoard Widget
====================

A simple webpage that fetches and shows upcoming bus and train times for the MBTA boston transit. This is built to use their open API, and designed to show up on the side of a [DAKBoard screen](https://dakboard.com/site). You could fork and change the `pointsOfInterest` variable to the ones you care about.

Setup
-----

You need to first [request a V3 API key from the MBTA](https://www.mbta.com/developers/v3-api), for free. Then just pass that on the URL to the app. For example:

    http://localhost/index.html?apiKey=12345askldfak134
