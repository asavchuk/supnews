# supnews

A simple Flutter app for displaying stories retrieved from Hacker News. Uses the [provider](https://github.com/rrousselGit/provider) package along with [MobX](https://mobx.pub) to managing the architecture

The app demonstrates

* Using MobX for managing UI state where stores function as view models that may talk to other services
* `provider` is used to organise stores and inject them into the appropriate widgets. Services are injected into the stores via `provider` as well
* How to load more items into a `ListView` based on scroll position by invoking an action in MobX
* Opening stories using the [url_launcher](https://github.com/flutter/plugins/tree/master/packages/url_launcher) package with the ability to load them in the browser instead of doing so "in-app"
* Toggling between dark and light mode
* Using custom fonts
* Using a Cupertino widgets within a material app
