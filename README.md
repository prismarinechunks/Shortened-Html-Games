# Standalone HTML Game Collection

A collection of HTML games that have been manually converted from projects requiring multiple external assets into single standalone HTML files.

Each game is prepared individually by taking its original HTML, JavaScript, CSS, images, audio, and other required local assets and combining them into one `.html` file.

## What This Project Is

The goal is to make HTML games easier to:

* Run offline
* Archive
* Back up
* Move between computers
* Use without the original folder structure

A typical game might originally look like:

```text
game/
├── index.html
├── game.js
├── style.css
├── img/
├── audio/
└── other assets/
```

After being converted, it becomes:

```text
game.html
```

with the required local assets contained inside the HTML.

## Multiple Games

This project contains multiple standalone HTML games.

Each game is converted and tested separately because different games handle their external assets differently.

The collection can include older games, lightweight games, experimental projects, and other HTML-based games that are suitable for standalone packaging.

## Low-End Friendly

The collection is intended to work well on lower-end hardware, including older laptops and Chromebooks.

The goal is not to add unnecessary frameworks or heavy systems. The games are kept as close as reasonably possible to their original versions while packaging their required local assets.

## Offline Support

A successfully converted game should be able to run without its original asset folders.

However, games that depend on servers, online APIs, accounts, or other external services may still require an internet connection.

## Credits and Licensing

All original code, graphics, audio, and other assets remain credited to their respective creators.

Each game must be checked against its original license or creator's terms before being distributed.

Original attribution and copyright notices should be preserved.

This project does not claim ownership of the games or their original assets.

## Project Status

This is an ongoing collection.

More HTML games can be manually converted into standalone files and added over time.

