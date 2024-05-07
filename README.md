# Itinerary on the Go - Documentation

## Purpose

This mobile app displays trips and their itineraries. It is a view only app.

The app can load itineraries from static yaml files. A database or cloud account are not required; however, the yaml files must be accessible via the internet.

## Quick Start

1. Launch the app
2. Add itinerary Url (via copy & paste or scanning a QR Code)
3. View itinerary

## Example Itineraries

This is a sample QR Code and URL for an itinerary:

| Example | QR Code |
|---|---|
| [Example 1](https://raw.githubusercontent.com/l5/curly-memory/main/trips/example-1/itinerary.yml) (monolingual)| <img src="assets/images/qr-code-url-example-1.svg" width=100 alt="QR Code for loading itinerary example 1" /> |
| [Example 2](https://raw.githubusercontent.com/l5/curly-memory/main/trips/example-2/itinerary.yml) (multilingual)| <img src="assets/images/qr-code-url-example-2.svg" width=100 alt="QR Code for loading itinerary example 2" /> |

## Example Use Cases
* Tour group members can view an itinerary on their mobile devices
* Walking tour guide: The tour guide has prepared the yaml file and carries its Url in printed form as a QR Code. When customers join the walking tour, they can download the app and scann the QR code, in order to see the scope of the tour and follow it.

## Features
* The user can maintain a list of trips via their URLs inside the app
* The app can render and display information about trips and their itineraries
* No user registration necessary
* No user data stored on servers
* Tour operators can maintain the itinerary via simple yaml files

## Non-Features
* There is no map inside the app
* Itineraries are not cached; it is necessary to be online
* Settings cannot be stored

## Known Issues
not yet :)
 
## Support

Feel free to create an [Issue](https://github.com/l5/itinerary-app-doc/issues) in the GitHub documentation repository for support or send an email to info@siriusplans.com . Please be aware that support is limited.

## Further Information

* [Privacy Policy](mobile-app-privacy-policy.md)
