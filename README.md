# Calex
A browser extension that shows events' descriptions in Google Calendar.

Descriptions of the events are displayed in the agenda and search view.

## Installation
Install from [Chrome Web Store](https://chrome.google.com/webstore/detail/calex-for-google-calendar/ccoehijdbponhcemihobmdpaeenmgchg).
![Calex in Google Calendar](docs/screenshot.png)

## Features

- shows descriptions in:
    - the agenda view
    - the search results
- supports markdown format thanks to [showdownjs/showdown](https://github.com/showdownjs/showdown)

### Browsers
Tested in:

- [Chrome](https://www.google.com/chrome/)
- [Opera](https://www.opera.com/) (you can use Chrome extensions trough [Download Chrome Extensions](https://addons.opera.com/en/extensions/details/download-chrome-extension-9/) addon)
- [Vivaldi](https://vivaldi.com/)

## Development
- clone this repository
- checkout a new branch
- load directory as an unpacked extension (be sure you have enabled **developer mode**)
- you have to reload extension on every change you made

### Todo
- [ ] simple cache to avoid unnecessary requests
- [ ] show description in event popup
