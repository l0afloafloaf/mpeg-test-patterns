## MPEG TEST PATTERNS

MPEG TEST PATTERNS is single-page website that loops and tiles a selection of video files which have all been used as source/test material for the development of video compression protocols.

View the website here: https://l0afloafloaf.github.io/mpeg-test-patterns/

Viewed best in full screen on a desktop browser and waiting a while to see what happens. 

---

This is an experiment in display and following an interest in standards, compression and image into data. Videos tile larger based on chance and videos repeat, loop and change playback speed based on exponential chance. 

Most video files have been sourced from xiph: https://media.xiph.org/video/derf/

I have particular interest in a couple of the clips, being "[flower_garden](https://github.com/l0afloafloaf/mpeg-test-patterns/blob/main/videos/flower_garden_422_ntsc.mp4)" and "[tennis](https://github.com/l0afloafloaf/mpeg-test-patterns/blob/main/videos/tt_sif.mp4)" (as well as [their](https://github.com/l0afloafloaf/mpeg-test-patterns/blob/main/videos/garden_sif.mp4) [descendents](https://github.com/l0afloafloaf/mpeg-test-patterns/blob/main/videos/tennis_sif.mp4)) as, [according to Leonardo Chiariglione](https://ride.chiariglione.org/the-first-mpeg-project/), these were some of the earliest test clips used in the development of MPEG-1 in the late 1980s. 

#### Improvements/additions

##### General

* [ ] prioritise certain clips in the pool (either algorithmically, or introducing recompressed duplicates)
  * this has been partly addressed with an offline iteration using a trimmed JS file of less clips, but could be expanded by making multiple 'versions', and publishing these versions here
  * some 'less interesting' clips have been trimmed from the 25/06 videos.js file. copyright of footage needs to be doublechecked 
* [ ] Expand the pool or look at an iteration which focuses on 'test patterns', which, despite the title of this project, don't appear here
* [ ] Spill this across multiple displays/screens
* [ ] Introduce additional chaos/probabilities over extended durations, like, after 120 layout changes:
  * [ ] increased time dilation
  * [ ] new echo behaviour(?)
  * [ ] additional footage/remuxes introduced
* [ ] Play with the 'blinking effect' apparent on web versions (where footage can take a second to load). This is desirable and could be baked in, with transition delay randomised between 0s-0.5s?
* [x] ~~Increase time dilation of clips~~ 24/06 version introduced exponential time functions 
* [x] ~~address the loop function, which doesn't seem to be behaving correctly~~

##### Interactivity

 * [ ] add a floating tooltip with links to: *full screen / exit full screen* and to other versions/variations
 * [ ] introduce info overlays for each video:
   * info inclusive of filename, year of origin, frames, resolution, source, readme, other info from XIPH, or known use in different protocols(?) if i can find this info
   * could be displayed in an overlay when mousing over a tile, or could be contained in a static page/floating display activated when 'clicking' on the tile, or clicking '(i)'
 * [ ] other click/interactivity behaviour, such as:
   * [ ] clicking on a tile causes video to 'echo' across other tiles
   * [ ] clicking forces giant (2x2 tiles) or 9cell layout, or randomly cues other chance layout/speed operations

Noting that any overlays should only appear with mouse movement, default appearance should stay as pure tiled videos

#### Related Projects 

* slideshow website/static page that cycles through the public flickr galleries of the SMPTE and ITU organisations.
* return to 2023 project 'buffering', which involved designing and animate my own loading symbol as a device to lay across videos and play with videos that, in an installation setting, give the impression of 'lag' 
