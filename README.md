# OpenFin Platform as Single Page App

This is a basic barebones app where we have configured the snapshot to have one url and hide the tab header. This makes it look like a single window even though you still have the power of the Platform API and the ability to customise the platform provider or the style of the header etc.

The codesandbox can be found here: https://codesandbox.io/s/openfin-platform-as-single-window-app-798g9

Some things you will need to update if you fork the github or codesandbox repo:

In config/app.platform.fin.json update:

- uuid : make the uuid unique
- visit https://www.openfin.co and request a trial/developer license
- update the url field to reflect your codesandbox url
- update the application icon to reflect your own icon
- update the name and description to reflect your application

More information about OpenFin:

- https://openfin.co/ -> main site
- https://developers.openfin.co/docs/getting-started => getting started guide
- https://github.com/openfin -> OpenFin Github repo
