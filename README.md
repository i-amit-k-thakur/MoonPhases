# MoonPhases

The application will display the lunar details for the next 7 days.

### API DETAILS
The application uses [stormglass.io ](https://stormglass.io/) to fetch the astronomy data.
```
GET https://api.stormglass.io/v2/astronomy/point
PARAMS: lat & lng
```
***The API call requires an API Key, which can be generated from the above link. This should be passed as the ```Authorization``` header***

### DEPENDANCIES
Dependancies will be managed using ```Cocoapods```

List of dependancies used:
- Nimble
