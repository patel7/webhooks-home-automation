In order to run this app:

- Install [node.js](https://nodejs.org/en/).
- Clone the repository.
- Install dependencies using `npm install`.
- Get your key from the Maker channel on IFTTT
- Add your key to the 'key' variable in the script

- Run like this:

 ```
 node index.js
 ```

- Add the webhook to https://app.plex.tv/web/app#!/account/webhooks
- In this case the webhook would be:
```
http://localhost:12000
```

- Used in conjunction with the follow IFTTT recipe: https://ifttt.com/applets/49465061d-log-everything-plex-plays
