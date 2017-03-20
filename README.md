
### TweetMap

- Get tweets from twitter and store it in DB (you can store only the ones that have the geo-location data to save time filtering the data later)
- Use Google Maps API to render these tweets in the map in whatever manner you want. You can visualize them as <dots>ther color maps,etc.
- You should provide a drop down with keywords of your choice to display only those tweets which contain the keyword.
- You need to display the tweets on the map in real-time.


### Stack
- RethinkDB (storage)
- Node.js (server)
- React (frontend)

### Prod

##### Stream
```
$ npm run stream
```

##### Start server
```
$ npm start
```

### Dev

##### Start server
```
$ npm run dev
```

##### Build frontend
```
$ npm run watch
```

