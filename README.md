This builds on https://github.com/axmandm/sgdk-game-over-sound to add background music.

Add to sound.res the VGM file to play

`XGM music "music.vgm"`

Note we have added a while(TRUE) loop, essentially encasing all of our other code within this main loop.

Add to int main()

`XGM_startPlay(music);`

When we want to stop it (at game over)

`XGM_stopPlay();`
