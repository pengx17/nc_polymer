# nc_polymer

A simple mock application of [slack](https://slack.com).

TODO:

- [x] Narrow layout support
- [x] Refactor firebase structure
- [x] Auto select the first channel after loaded
- [ ] Write something when channel is empty
- [x] Split chats based on dates
- [ ] Make sure no channel name collides
- [x] Loading spinner
- [ ] Supports chat edit and delete
- [ ] Supports channel edit and delete
- [ ] Supports login via Google account
- [ ] LocalStorage to persist user login status
- [ ] Performance tunes
- [ ] Direct messages
- [ ] Desktop notifications
- [x] Electron package

## Tech stack
- Google Polymer 1.0
- Firebase
- MVVM pattern. Databinding enabled with polymer's view and firebase.
- Electron

## Run locally with your favourite http server
The following shows how to run with `http-server` utility:
```
bower install
npm install -g http-server
http-server
```
## Run with electron
```
electron .
```
