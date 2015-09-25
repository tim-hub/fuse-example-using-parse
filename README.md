# Using Parse with Fuse Example
Example project to accompany the "Using Parse with Fuse" Fuse tutorial video. This is a super simple app using [Parse](https://www.parse.com) as a backend service, where anyone can simply post text, and anyone else can see that text. All relevant code is in the `MainView.ux` file.

## Setup
_NOTE: this is covered in the tutorial video._

You'll need to use your own Parse app backend with this example. Insert your app's Application ID and Javascript Key into the `api-keys.js` file:
```js
module.exports = {
	appId: "YOUR APP ID HERE",
	jsKey: "YOUR JS KEY HERE"
};
```

Once that's done, you're ready to roll!

## Fuse version
This example was produced with Fuse (beta) v0.5.7001 (September 22, 2015).

## Branches
The "finished product" is on the `master` branch, and the template I started with in the video is on the `starting-template` branch.

## License
This code is licensed under the BSD2 license (see LICENSE).
