# WHATIS

https://meshtastic.taubetele.com/

Not a pet. Not a product-grade. Just a try to educate `@kkwestt` to read this `Readme.md` and notify `@zwoelf` if it's read.
Before start it, run redis docker container.

# Config it

```bash
cat server.js
```

```js
export const useServer = () => {
  // const theOnlyOne = 'https://api.meshtasticback.taubetele.com'
  const theOnlyOne = 'http://localhost'
  return {
    theOnlyOne
  }
}
```


# WHATIS

https://meshtastic.taubetele.com/


Not a pet. Not a product-grade. Just a try to educate `@kkwestt` to read this `Readme.md` and notify `@zwoelf` if it's read.
Before start it, run redis docker container.

# Config it

```bash
cat server.js
```

```js
export const useServer = () => {
  // const theOnlyOne = 'https://api.meshtasticback.taubetele.com'
  const theOnlyOne = 'http://localhost' // poka tak v deve
  return {
    theOnlyOne
  }
}
```


### Task list

- [x] Show node's on the map
- [x] Diveces data list
    - [x] Search
    - [ ] Button > modal window > readeble table
- [x] Telegram bot forwards public messages
    - [ ] add some reciver
- [x] Show MQTT connected node's
- [x] Show points in the window only, do not draw unnecessary
    - [ ] redraw timer
- [x] Background update by timer 20s
- [ ] Telemetry charts
	- [x] collect telemetry data
	- [x] returns data on request
- [ ] GPS track by node
	- [x] collect location data
	- [x] returns data on request
- [ ] Show real connections between nodes (based on user pings)
