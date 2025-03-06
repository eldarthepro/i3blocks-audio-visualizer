# i3blocks-audio-visualizer

Audio visualizer is a way to have visual feedback that music is playing now in i3blocks. Visualization is fake as it is randomly generated. 

Please install playerctl and alsa-utils for it to work.

Due to i3blocks is intended for static text it is not fluid.

Add to your i3blocks config:
```
[visualizer]
command=$SCRIPT_DIR/visualizer
interval=1
```
