# Student ACM Chapter Website

### 2020 - 2022 School Year(s)

Website maintainer: Nicholas O'Kelley

## Motivation

Allow our ACM Chapter to be represented with an nice online website showcasing
what our chapter is offering other students/peers.

## Credit:

- Based on HTML5Up's dopetrope template, with modifications made by Wesley Rogers.
- This is a fork of Wesley's repo and has since been further modified and customized by Nicholas with feedback from club members.

## Contributions

Feel free to open an issue and we will get to resolving it as soon as possible. Alternatively
you can fork this repo and create a new pull request and we will provide feedback.

## Future Goals

- A form for being added to the email list
- Make this page open source
- Add more content to resources

## Project Layout

### Project Focus

The main files you will need to update periodically are:

- `./index.shtml`
- `./about-us.shtml`
- `./events.shtml`
- `./resources.shtml`

### References

The pdfs are located in the `./src/` directory. The goal was to put all the html
in the source too but configuring it so the appropriate stuff was shown on the server
prevented it due to other security measures.

NOTE: We keep the previous pages as inspiration for what has come before.

Our goal was to cut down on the amount of pages needed to just the four mentioned
above, but did not want to limit future students.

```
src/
├── pdfs
│   ├── bylaws.pdf
│   └── constitution.pdf
└── previous_pages
    ├── board.shtml
    ├── conferences.shtml
    ├── events.shtml
    ├── hunt.shtml
    ├── orgs.shtml
    ├── projects.shtml
    └── reu.shtml
```

## Development notes:

- Anything regarding styling is in the `assets/`. Good luck manipulating the templates current themes
- Images are (shockingly) in the `./images/` directory
- Updating content is more important than the colors as we have them on a pretty neutral point now.
