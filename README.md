## MPEG TEST PATTERNS

MPEG TEST PATTERNS is single-page website that loops and tiles a selection of video files which have all been used as source/test material for the development of video compression protocols.

View the website here: https://l0afloafloaf.github.io/mpeg-test-patterns/

Viewed best in full screen on a desktop browser and waiting a while to see what happens. 

---

This is an experiment in display and following an interest in standards, compression and image into data. It is entirely vibe coded. Videos tile larger based on chance and videos repeat and loop based on incremental chance. 

Most video files have been sourced from xiph: https://media.xiph.org/video/derf/

I am particularly interested in a couple of the clips such as "flower_garden" and "tennis" (and their descendents) as, according to Leonardo Chiariglione's history on the subject, they were the initial two test clips chosen for the development of MPEG-1 in the late 1980s: https://ride.chiariglione.org/the-first-mpeg-project/

#### Improvements/additions

##### General

* [ ] prioritise certain clips in the pool (either algorithmically, or introducing recompressed duplicates)
  * this has been partly addressed with an offline iteration using a 'shortlist.js' file, but could be expanded by making multiple 'versions', and publishing here
  * still need to edit out less relevant clips from here and from shortlist and ensure any copyright requirements are being followed
* [ ] Expand the pool or look at an iteration which focuses on 'test patterns', which, despite the title of this project, don't appear here
* [ ] Spill this across multiple displays/screens
* [x] ~~Increase time dilation of clips~~ 24/06 version introduced exponential time functions 
* [x] ~~address the loop function, which doesn't seem to be behaving correctly~~

##### Interactivity

 * [ ] add a floating tooltip with links to: *full screen / exit full screen* and to other versions/variations
 * [ ] introduce info overlays for each video:
   * info inclusive of filename, year of origin, frames, resolution, source, readme, other info from XIPH, or known use in different protocols(?) if i can find this info
   * could be displayed in an overlay when mousing over a tile, or could be contained in a static page/floating display activated when 'clicking' on the tile, or clicking '(i)'
 * [ ] other click/interactivity behaviour, such as:
   * [ ] clicking on a tile will causes video to 'echo' and spread across other tiles
   * [ ] clicking forces giant (2x2 tiles) or 9cell layout, or randomly cues other chance layout/speed operations

Noting that any overlays should only appear with mouse movement, default appearance should be simply tiled videos

#### Related Projects 

* slideshow website/static page that cycles through the public flickr galleries of the SMPTE and ITU organisations.
* return to 2023 project 'buffering', designing and animate my own loading symbol to place across content 
