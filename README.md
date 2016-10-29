# simpsons-image-training-dataset
##Description
Collection of 30,693 frames from 65 Simspsons episodes from seasons 3, 4, and 5. Each image is 160x120 pixels.

One collection (faces-clean-color) contains isolated frames of Homer (n=1,041), Marge (n=444), Lisa (n=358), and Bart (n=645) totalling (n=2,488). These files are labled as {instance_number}_{character_name}.jpg. 

The second collection (unsorted-color) contains 28,205 unsorted frames which can contain backgrounds, characters, text, etc. The two sets are mutually exclusive. This has been broken up into several archives for upload.

##Source
Downloaded from https://www.frinkiac.com/ using Chrome on Oct. 28th-29th, 2016. Original post at http://www.jbencina.com/blog/2016/10/29/simpsons-character-image-training-set/

##Categorization Methodology
Each frame was manually inspected to see whether it contained one of the four main characters. Images were selected such that the subject was:
- Facing the camera at an angle of less than 90 degrees (no side profiles)
- Generally vertical, not sideways/upside down
- The only face in the image (distinctive features too eg. Marge's face, but back of Lisa's head)
- At least the eyes & mouth were visible
- Not overly small (subjective)
- Not wearing head costume, prop, hat, etc.
- Not part of flashback/flashforward to different age
- Not covered by text or prop
- Not covered with a heavy/artistic shadow
- Not distorted by some strange animation effect (subjective)

I inspected the files a couple of times and am confident in the labled faces set. I may have missed some qualifying photos in the unsorted set. Frankly, I began going cross eyed.
