# Project: Neighborhood

A **Neighborhood Map API Project**, a single-page Neighborhood Map application using **Google Maps API**, **Knockoutjs**, and **Foursquare API** to retrieve 3rdparty data on each marked place on the map. The user has to ability to manipulate the list by filtering them through text matching, click on a marker and view the place address, Foursquare likes and a direct link to their website.

## Get it started.

* You may run the application here: https://russeladrianlopez.github.io/neighborhood-mapping/
* However, Foursquare API has [rate limits](https://developer.foursquare.com/overview/ratelimits), it may result for the application to fail if the request exceeds the limit.
* Alternatively, to make it work just follow the instructions below.

### Downloading a copy
* **Fork** the [repository](https://github.com/russeladrianlopez/neighborhood-mapping). _(You may fork or not totally up to you)_

* Once you have your own repository. **You may click Clone or download**, then use _HTTPs section_ and copy the clone URL.

* Open Terminal and type in `git clone` and paste the URL you copied.
Ex.
```
git clone https://github.com/russeladrianlopez/neighborhood-mapping.git
```

### Setting up Foursquare API
To get the Foursquare API working there are a few additional steps:

* Go to [Foursquare for developers](https://developer.foursquare.com/)
* Create New App
* Sign up or Login if prompted
* Fill in the details
* Create App with or without Verification.
* Copy the CLIENT_ID and CLIENT_SECRET
* Go to js/app.js paste it into the foursquare global variable `fs_client_id` and `fs_client_id` respectively.
* Save the file and run index.html

### Usage
* The user can filter the list of using the search box.
* The user may proceed to the place's website if the user clicks on the name or the picture inside the marker's Infobox.

### Sources

* [Foursquare API](https://developer.foursquare.com/)
* [Google Maps API](https://developers.google.com/maps/)
* [Knockoutjs](http://knockoutjs.com/)
* [JQuery](http://api.jquery.com/)
* [w3cshools](http://www.w3schools.com/)

Nanodegree Course courtesy of [Udacity](https://www.udacity.com/).
