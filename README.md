# 2027 MSBA Sports Data Analytics Competition

Public website for the inaugural MSBA Sports Data Analytics Competition, hosted by the USC Marshall School of Business.

**Live site:** https://usc-student-outcomes-and-trajectories.github.io/sports-data-analytics-competition/

## Editing the site

The whole site is one file, `index.html`. Images live in `assets/`. GitHub Pages republishes automatically about a minute after each change to `main`.

Near the bottom of `index.html` is a block marked **Edit these values to update the site**:

- **`interestFormUrl`:** the expression-of-interest form link. While it's empty, the buttons scroll to the contact section.
- **`livestreamUrl`:** the YouTube finals link. After registration closes, the main button switches to "Watch the live finals" once this is set.
- **`MILESTONES`:** every date on the page. The key-date strip, the full timeline, the "Up next" highlight and the countdown are all built from this list. Times are in UTC (Pacific Time in January and February is UTC−8).

Eligibility, judging and FAQ text is plain HTML higher up in the same file.

Internal planning documents are kept in a separate private repository and are not part of this site.
