
# PGPush Star Track

A PhoneGap example app using [Framework7 HTML Framework](http://framework7.io/) and the [Spotify API](https://developer.spotify.com/web-api/).
It is forked from https://github.com/phonegap/phonegap-app-star-track

### Requirements

- PhoneGap CLI: `npm install -g phonegap`

### Clone

```
git clone https://github.com/tuanquynet/pgpush-star-track
cd pgpush-star-track
phonegap serve
```

##Development guideline
- Checkout sample code: `git clone <github>`
- Install dependencies: `npm install`
- Add android platform: `cordova platform add android`
- Run application: `cordova run android --device` 
- Add ios platform: `cordova platform add ios`
- Run application: `cordova run ios --device` 

## Setup plugin
- phonegap plugin add phonegap-plugin-push --variable SENDER_ID=1078410550987

## Others information
Google Cloud Messaging (Firebase Cloud Messaging), project on GCM: https://console.firebase.google.com/project/incutech-drevalet-test/settings/cloudmessaging
- senderID: 1078410550987

## References
- This application is accomplished by following this workshop http://macdonst.github.io/push-workshop-eu/module1.html
