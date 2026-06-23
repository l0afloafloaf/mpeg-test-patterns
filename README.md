## MPEG TEST PATTERNS

This is a single-page website that loops and tiles a selection of video files, all known for their use as source/test material for the development of video compression protocols. This is an experiment in display and following an interest in standards, compression and image into data. 

This is entirely vibe coded. Videos tile larger based on chance and videos repeat and loop based on incremental chance. 

Most video files have been sourced from xiph: https://media.xiph.org/video/derf/

I believe I have excluded any with outstanding copyright restrictions. 

I am particularly interested in a couple of the clips such as "flower_garden" and "tennis" (and their descendents) as, according to Leonardo Chiariglione's history on the subject, they were the initial two test clips chosen for the development of MPEG-1 in the late 1980s: https://ride.chiariglione.org/the-first-mpeg-project/

Improvements for future iterations:
* Increase the chance of certain clips appearing more often - like flower_garden or tennis, whether through modifying the chance function, or by introducing recompressed duplicates of these clips to the video pool
* Expand the pool or look at an iteration which focuses on 'test patterns', which, despite the title of this project, don't appear here
* Spill this across multiple displays/screens 
* Increase time dilation of clips - it gets really slow when it gets very big, this could happen at chance to other clips, or more often generally
* address the loop function, which doesn't seem to be behaving correctly - it should be looping videos less than 5s long 2-3 times

Other related projects could include a slideshow website that would cycle through the public flickr galleries of the SMPTE and ITU organisations, cos... idk it'd be funny and there's *something* there 