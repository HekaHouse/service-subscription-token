# service-subscription-token

`<service-subscription-token>` A polymer element to retrieve a subscription key from Firebase.

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/service-subscription-token)

[Source](http://github.com/hekahouse/service-subscription-token/)


## Install

    bower install --save HekaHouse/service-subscription-token

## Example

    <service-subscription-token
      subscription-key-path="https://YOUR-FIREBASE.firebaseio.com/SUBSCRIPTIONS/"
      subscription-id="SUBSCRIPTION-ID"
      subscription-key="{{subscriptionKey}}">
    </service-subscription-token>

In the above example replace YOUR-FIREBASE SUBSCRIPTIONS and SUBSCRIPTION-ID with appropriate values from your Firebase.

## Note

Upon successful retrieval subscriptionKey is populated with relevant key

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

service-subscription-token depends only on firebase-element from Google

## Related
