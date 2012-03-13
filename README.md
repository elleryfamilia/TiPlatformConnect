# TiPlatformConnect (forked twitter-titanium)
* Replaced jsOAuth-1.3.1.js to jsOAuth-1.3.3.js, and customize for Titanium Mobile(Content-Type, Ti.Network.createHTTPClient())
* twitter.js using jsOAuth.getAccessTokenKey() and jsOAuth.getAccessTokenSecret(), and update_with_media support!
* Added tumblr.js using OAuth(not XAuth). Photo upload yet...
* Added mixi.js
* Added foursquare.js
* Added flickr.js. In development...
* Rewrite the app.js
* Extend platform.request(path, params, headers, httpVerb, callback); path is replaced url possible. Added headers.

## How to use

See Resouces/app.js

## twitter.js

update_with_media support!

## tumblr.js

Required default callback URL in Tumblr application setting page. No need to in the library properties.

## mixi.js

Required callback url in the library properties. Required access token refresh(only mixi.js), how to Resouces/app.js.

## foursquare.js

Required callback url in Foursquare application setting page. Need to in the library properties.

## flickr.js

Required callback url in the library properties.

## Thanks
* Original twitter-titanium by @ebryn
* jsOAuth by @bytespider
