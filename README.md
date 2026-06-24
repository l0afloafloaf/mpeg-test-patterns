## MPEG TEST PATTERNS

MPEG TEST PATTERNS is single-page website that loops and tiles a selection of video files which have all been used as source/test material for the development of video compression protocols.

View the website here: https://l0afloafloaf.github.io/mpeg-test-patterns/

Viewed best in full screen on a desktop browser and waiting a while to see what happens. 

---

This is an experiment in display and following an interest in standards, compression and image into data. It is entirely vibe coded. Videos tile larger based on chance and videos repeat and loop based on incremental chance. 

Most video files have been sourced from xiph: https://media.xiph.org/video/derf/

I am particularly interested in a couple of the clips such as "flower_garden" and "tennis" (and their descendents) as, according to Leonardo Chiariglione's history on the subject, they were the initial two test clips chosen for the development of MPEG-1 in the late 1980s: https://ride.chiariglione.org/the-first-mpeg-project/

Improvements for future iterations:
* [ ] prioritise certain clips in the pool (either algorithmically, or introducing recompressed duplicates)
  * this has been partly addressed with an offline iteration using a 'shortlist.js' file
  * still need to edit out less relevant clips and ensure any copyright requirements are being followed
* [ ] Expand the pool or look at an iteration which focuses on 'test patterns', which, despite the title of this project, don't appear here
* [ ] Spill this across multiple displays/screens 
* [x] ~~Increase time dilation of clips~~ 24/06 version introduced exponential time functions 
* [x] ~~address the loop function, which doesn't seem to be behaving correctly~~ loop works as intended, though clips could be trimmed to make the loop cleaner

Other related projects include 
* slideshow website/static page that cycles through the public flickr galleries of the SMPTE and ITU organisations.
* return to 2023 project 'buffering', designing and animate my own loading symbol to place across content 
