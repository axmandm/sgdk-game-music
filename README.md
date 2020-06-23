This builds on 4_gameoversound to add background music.

Add to sound.res the VGM file to play
XGM music "music.vgm"

Note we have added a while(TRUE) loop, essentially encasing all of our other code within this main loop.

Add to int main()
XGM_startPlay(music);

When we want to stop it (at game over)
XGM_stopPlay();

Lengthen int timer to 30s to hear more of this great track :)
