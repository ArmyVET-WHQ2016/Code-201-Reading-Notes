# Read: 13 - Local Storage

Reading

1. Why would a developer use local storage for a web application?
- Normally, this is done server-side, and you would check the user name to know which state to revert to. But what if you don’t want to force people to sign up? This is where local storage comes in. You would keep a key on the user’s computer and read it out when the user returns.

2. What information should not be stored in local storage?
- do not store sensitive user information in localStorage.
It is not a substitute for a server based database as information is only stored on the browser.
localStorage is limited to 5MB across all major browsers.

3. Local storage can store what type of data? How would you convert it to that type before storing? localStorage. is a property that allows JavaScript sites and apps to save key-value pairs in a web browser with no expiration date. This means the data stored in the browser will persist even after the browser window is closed.
