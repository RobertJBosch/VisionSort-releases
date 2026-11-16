# VisionSort

Scan your Magic: The Gathering cards with a webcam, keep your collection, sort it into piles and
build Commander decks from what you own.

## Download

**[Get the latest version](https://github.com/RobertJBosch/VisionSort-releases/releases/latest)** - under
*Assets*, download `VisionSort-<version>-setup.exe` and run it.

- It installs just for you (no administrator password) and adds VisionSort to the Start menu.
- Windows may say "Windows protected your PC" the first time, because the app isn't signed by a
  publisher: click **More info**, then **Run anyway**.
- Prefer not to install? Download the `.zip` instead, unzip it somewhere that stays put and run
  `VisionSort.exe` in it.

Needs Windows 10 or 11 (64-bit) and a webcam for scanning (the Inventory and Decks work without one).

## Your data

The first start asks where to keep things; the suggested folders are fine:

- **Your collection** - `Documents\VisionSort`: your cards, decks, settings and daily backups. Back
  this folder up or sync it. Installing, updating and uninstalling never touch it.
- **Card data** - `%LOCALAPPDATA%\VisionSort\Card data`: the card index and card images. VisionSort
  keeps it up to date by itself and can always download it again.

## Updating and removing

- **Update**: run the newer setup.exe; it replaces the old version.
- **Remove**: Settings > Apps > VisionSort > Uninstall (it offers to delete the card data too; your
  collection is kept).

## Something wrong?

The log is at `%LOCALAPPDATA%\VisionSort\Card data\logs\visionsort.log` - send it along with what
you were doing.

---

VisionSort is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed
by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the
Coast LLC. Card data and images: [Scryfall](https://scryfall.com). Deck data:
[EDHREC](https://edhrec.com) and [Commander Spellbook](https://commanderspellbook.com).

This repository only holds the downloads.
