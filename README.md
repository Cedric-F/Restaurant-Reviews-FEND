# Front End Web Developer Certification Course

---

## Restaurant Reviews static application

Stage 1 of the Restaurant Reviews progressive app for the Udacity MWS course.

### Getting started

#### Installation

*Cloning the repository*

```
git clone https://github.com/Cedric-F/Restaurant-Reviews-FEND.git
```

#### Kickstart the server

Different options depending on your preferences:

- Execute the `server.bat` script that will run the npm http server and open the project.
- In your terminal, run `http-server ./` and open your favorite browser at the address: `localhost:8080`.
- Use your favorite local server.
Might not work with `python` as it seems to override the files' MIME types and cause issues with the service worker.

### Using the application

#### Testing Accessibility

Install the Chrome Vox extension (or any screen reader) and navigate through the page using tab.

#### Testing Offline mode

- Press F12 and in the `Application` tab, check the `Offline` box.

***or***

- Stop the server.

Now, only the cached files and visited pages should work.

#### Testing responsiveness

Use the Chrome Device emulator to simulate different smartphones and tablets.

### License

None

### Dependencies

* [Google Normalize.css](https://code.google.com/archive/p/normalize-css/)
* [Google Maps' API](https://developers.google.com/maps/documentation/)

### Compatibility

Tested on:

* Chrome
* Chrome Canary
* FireFox
* FireFox Dev edition