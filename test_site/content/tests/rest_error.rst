title: reStructuredText Test Page with Deliberate Error
category: tests
tags: [rest, sample]
---

reStructuredText Page with Deliberate Error
===========================================

For issue #144: reStructuredText rendering errors don't show
filename, just "string"

The following will trigger a rst rendering error:
    - Should be an extra newline between the
    - first bullet point and the preceeding paragraph
This is line 15 but wok will report line 11 due to four lines of
metadata above.

