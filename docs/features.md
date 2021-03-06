---
title: Features
---
For complex development reasons they have been included in the [base packages](architecture.html#Base-packages) and also they are the basic features of a social platform.
The plugins installed can add more features to the platform then refer to the  [plugins](plugins.html) documentation to learn more.

### User registration and login
- signup by external social accounts
- email verification
- password changing

### Places creations
- add new place by location
- add or edit geometry of a place(point,polyline,polygon)
- import data from Openstreetmap in a new place
- import multiple places from standard geojson file

### User profile
- GPS location on mobile device
- checkin / checkout of users in the places
- online / offline user status
- user settings
- history of places visits

### Users relationships
- requests / confirmations friendship
- blocking / reporting of other users

### Searching
- users by name, date of signup
- places by name, date and proximity

### Internationalization
-  extended to others languages through the package [keplerjs:i18n](https://github.com/Keplerjs/Kepler/tree/master/packages/i18n)
-  within each plugins in ```/i18ns``` folder.

