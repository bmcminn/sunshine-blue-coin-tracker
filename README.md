
# SM Sunshine Blue Coin Tracker

> [Go to app!](https://bmcminn.github.io/sunshine-blue-coin-tracker)

Blue coin hunting guide by [Reb Valentine](https://www.imore.com/author/Reb%20Valentine), found at [Super Mario 3D All-Stars: Blue Coin hunting guide for Super Mario Sunshine](https://www.imore.com/super-mario-3d-all-stars-blue-coin-hunting-guide-super-mario-sunshine)

I merely turned his guide into an app to help track my progress.



## Disclaimer(s):

**Please note:** I am well aware of the fact there are 240 blue coins in the game. I'm still parsing Reb's list identifying and updating each individual coin description as I play through the game myself.

Also, this list is not written in an optimized order. I merely turned Reb's list into an app to help track my progress while updating some of the coin location descriptions for accuracy and how to easily get them.

Speed run order may be a future improvement to this list but it's not a priority for me.



## How to use this app:

1. Click/tap any of the level names listed below to open its blue coin checklist
1. Click/tap a given blue coin location description to toggle if you have collected it or not
1. Repeat as necessary

Each time you check or uncheck a coin, the page URL is updated with a hash your progress, so feel free to bookmark this page to save your progress and share your progress with your friends!



## Changelog

- `10/19/2020` **BREAKING CHANGE:** Update blue coin descriptions for multiple levels. Generally improving location accuracy and how to collect them, also breaking up entries describing more than one coin into their own checklist entries. *This requires you to redo your list. Sorry!*
- `10/19/2020` Update `serialize()` and `deserialize()` to use [`lz-string`](https://github.com/pieroxy/lz-string) compression library for progress hashes in URL
- `10/19/2020` Add `package.json` and include script for running local dev server via `php` for testing
- `10/18/2020` Fix `serialize()` method overwiting window URL `path` value instead of appending the querystring
- `10/18/2020` Add `README.md` document
- `10/18/2020` Add `LICENSE` file
- `10/18/2020` Fix missing link to original blue coin guide
- `10/18/2020` Initial application deployment