If you get errors with reading the pickle, probably pandas and the pickle dumping version are not matching.
https://stackoverflow.com/questions/68625748/attributeerror-cant-get-attribute-new-block-on-module-pandas-core-internal


Consultas a Stev:
- What landmarks are we filtering? Can we quantify them?
R: identify them but not remove them.
- Define missing values: MediaPipe we know.

- What does the range of 0-1 in the heatmaps mean, percentage of missing values?
R: correlación de 1s

- More comments needed

- What wrist to use  (pose or hands)? Do an analysis of both, which one have more "valid" 
R: in pose it is recovered, then if a flag is turn off, we do not have any point of hands (mediapipe).  Let's check for WP and OP.

- Cut better the images


- Comparison plot separate in two