# Brochure Display

## Program

KidSpirit Brochure code is available on the GitHub repo at [https://github.com/OSUKidSpirit/Programs-Section](https://github.com/OSUKidSpirit/Programs-Section)

Changes pushed to GitHub will be notified on Slack at **#04code** public channel

## Location

The KidSpirit Brochure is located at the following location:

- [KidSpirit Program Page](https://kidspirit.oregonstate.edu/programs)
- [Archery Program Guide](https://kidspirit.oregonstate.edu/archery-program-guide)
- [Gymnastics Program Guide](https://kidspirit.oregonstate.edu/gymnastics-program-guide)
- [Cooking Academy Program Guide](https://kidspirit.oregonstate.edu/cooking-academy-program-guide)
- [BASE Camp Program Guide](https://kidspirit.oregonstate.edu/base-camp-program-guide)

## Updating Code

## Brochure Changes

Changing the brochure, unless the URL remains the same, require changing the code for **ALL** these pages.

To change the brochure, replace the URL located in `src=""` with the new URL of the file like so:

```html
<iframe class="anthonian-brochure" src="{{ URL }}" width="100%" height="500px"></iframe>
```

The JavaScript should be placed at the very bottom of the page. Use a new section if needed.
