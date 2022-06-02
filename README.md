<img src="https://github.com/mhluska/blackjack-discard-tray-photos/raw/master/preview.gif" alt="Preview" />

# Discard Tray Photos

A collection of sequential photos of playing cards in a discard tray (one photo
per card). The main use case for this is deck estimation practice in Blackjack
card counting.

Future versions might offer higher resolutions, different angles and green
screen backgrounds.

## Develop

To be able to run build scripts in this project, you'll need a few dependencies:

```sh
brew install imageoptim imagemagick parallel
```

## FAQ

- Why are there 365 photos?

One photo of the empty tray plus 364 card photos (7 decks). I used a 6 deck
discard tray but managed to fit 7 decks in there. You really only need the first
313 photos.
