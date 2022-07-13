## Bitmojis and Friendmojis GEnerator
## Generating and searching friendmojis

In order to use the [friendmoji generator](https://anxkhn.github.io/bitmoji/friendmoji.html?firstid=f48e5674-30b2-4f60-aa65-9a0354a1684a&secondid=b84252ec-d02e-4a50-8682-0445ff64379c) you require two IDs which go here in the URL -
https://anxkhn.github.io/bitmoji/friendmoji.html?firstid=IDHERE&secondid=IDHERE.

There is two process of extracting the IDs
 - Using [Chrome Extension](https://chrome.google.com/webstore/detail/bitmoji/bfgdeiadkckfbkeigkoncpdieiiefpig)
 - Using ROOT permission on Android and extracting from /data/data/com.snapchat.android/database/main.db
 
 Two acceptable formats of IDs are 
 - 410601612_13-s5 (older accounts)
 - f48e5674-30b2-4f60-aa65-9a0354a1684a (newer accounts.)


## List of bitmoji images:

Access the bitmoji list in json format [here](https://api.bitmoji.com/content/templates).

Use the entries in "imoji" for solo comics, and the entries in "friends" for friendmojis.

## Making sense of the data

You can modify the following attributes according to your need.
  * `transparent=1` to set the bg to true (enabled by default on all supported bitmojis).
  * `width=XXX` scale image width to XXX pixels (set to 500- highest possible to generate at the moment).
