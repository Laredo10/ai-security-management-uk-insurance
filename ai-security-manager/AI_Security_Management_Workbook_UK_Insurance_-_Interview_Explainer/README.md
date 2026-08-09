\# Interview explainer deck



This folder holds the editable slide deck used as a speaker aid

for AI Security Manager interviews at a UK insurer. The deck is

authored exclusively from the populated workbook and the

supplied summary document. No invented content.



\## What is in this folder



\- manifest.json — the deck manifest. Stores canvas size,

&#x20; metadata, and the authoritative playlist order.

\- slides/ — one self-contained HTML file per slide. Sixty-one

&#x20; slides in total.

\- assets/ — shared stylesheet and any image assets referenced

&#x20; by the slides.



\## Deck structure



The deck runs in this order, drawn from manifest.json's

playlist:



1\. Title.

2\. Architecture and synchronisation — how the populated

&#x20;  workbook, the template workbook, and the deck itself

&#x20;  interlock.

3\. Interview framing — what the candidate should expect, who

&#x20;  owns what, and how to handle pushback.

4 to 35. 32 worksheet explainers, one per populated sheet.

&#x20;  Each explainer carries title, purpose, security relevance,

&#x20;  template mapping, key sections and columns, important

&#x20;  callouts, likely interview risks, candidate talking points,

&#x20;  and a speaker-aid note.

36 to 60. 25 form-tab explainers, one per form tab. Same

&#x20;  explainer scaffold as the worksheet slides.

61\. Closing.



\## How to use this folder



Open the slides in your right-hand preview inside GenSpark, or

export the deck to PPTX for use outside the session. The slide

files are pure HTML so any editor that reads HTML will work.



\## How to export to PPTX



Use the export action at the top of the slides preview. The

deck renders natively to PowerPoint with the layout preserved.

Figure on approximately a 10 to 15 second render time for the

full 61-slide deck.



\## Caveats



The deck was authored from the supplied summary, not from a

direct read of the populated .xlsx. Cell-level references in

slide content derive from rows described in the summary. No

fabricated content.



