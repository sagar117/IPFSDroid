[![Build Status](https://snap-ci.com/ligi/IPFSDroid/branch/master/build_image)](https://snap-ci.com/ligi/IPFSDroid/branch/master)

[![Android app on Google Play](http://ligi.de/img/play_badge.png)](https://play.google.com/store/apps/details?id=org.ligi.ipfsdroid)
[![Android app on FDroid](http://ligi.de/img/fdroid_badge.png)](https://f-droid.org/repository/browse/?fdid=org.ligi.ipfsdroid)

### Android App for the The InterPlanetary File System(IPFS)

This App does not represent a full IPFS node yet! It is currently mainly for developers who want to experiment with IPFS on Android. Think of it as a dependency injection for IPFS on Android. Currently we use the centralized service ipfs.io so you can use ipfs on android - later this will be exchanged for a full-node for decentralisation but all things that use this app don't have to change/care.

### Features:

Handles fs:/ipfs and fs:/ipns links via intent-filters ( also the unrecommended ones work: ipfs:// | ipns:// | fs://ipfs | fs://ipns )
Ability to share content with IPFS. This is possible from within the app and with the share-intent.

### Developer Remarks:

This app uses the [IPFS Kotlin API](https://github.com/ligi/ipfs-api-kotlin)

### Future features:

* Content Provider
* Document Provider

![](https://raw.githubusercontent.com/ligi/IPFSDroid/master/assets/screenshots/browser.png)

![](https://raw.githubusercontent.com/ligi/IPFSDroid/master/assets/screenshots/browse_ipns.png)


### Test links

[http://ligi.de/ipfs/example_links.html](http://ligi.de/ipfs/example_links.html)
