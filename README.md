# vimeoplayer
Embedded Vimeo player with seek forward disabled and button hidden until playing completes

We have a need for a player to play educational content as part of a learning management system which we don't want to be skipped over. Without disabling seek functionality entirely, we allow users to go back over what they have already watched in real time. Also, we don't want them progressing to the next slide until the video has played in it's entirety, so we hide the "Next" button. All done client side with no server side checks, so not cheat proof, but adequate for our purposes. We only need to make it inconvenient enough to encourage people to watch a two minute clip.
