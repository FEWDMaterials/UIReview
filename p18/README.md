## [Create a Weather Tracker](https://github.com/FEWDMaterials/UIReview/tree/master/p18)

Create a simple weather tracker.

#### [API Docs](https://openweathermap.org/api)

#### Requirements

1. Input field should handle `Enter` key press to initiate search
2. Submit button should also initiate search
3. Both search initiations should clear the input field
4. User should input city name and country name (your call if you want to do two input fields or one) to see five day forecast for the week


#### Stretch Goals
1. Look into the [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation/Using_geolocation) to see if you can get the city from user's browser
2. Allow the user to click a button to add multiple cities - for each city selected, display 5 day forcast for that city (labeled properly, ofc)
3. Pull in [Google Maps](https://developers.google.com/maps/documentation/javascript/tutorial). Figure out how to detect when user pans the map - on user pan, grab the center of the map as lat and long and push that into your 5 day weather forecaster.