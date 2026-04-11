Bissett Consulting Organization Website Assignment 2
Rizwan Mirza & Enzo Farshori - 201749288
201720559
Comp 2511

Rizwan: responsive CSS, media queries, normalize.css, accessibility fixes
Enzo: HTML structure updates, cross-device testing, WAVE analysis

Manual Analysis:

Perceivable:
Issue: Low contrast on figcaption text 
Fix: Changed color from grey to black to meet WCAG contrast requirements

Understandable:
Issue: Radio buttons and checkboxes had no associated labels
Fix: Added id attributes to each input and matching for attributes on labels

Robust:
Issue: Group labels for radio/checkbox sets werent linked to inputs
Fix: Wrapped groups in fieldset with legend elements

Automated Analysis (WAVE):
- index.html: 10/10
- about.html: 10/10
- sponsors.html: 10/10
- team.html: 10/10
- contact.html: 9.9/10 

General changes made: 

The main type of issues we faced were form accessibility problems. The inputs lacked proper label associations, which effects screen reader users. 
Fixed by making sure all inputs have linked labels and by making sure group inputs use fieldset/legend.

NOTE: used claudecode for 2 push to github, we expeirienced troubled early on 








