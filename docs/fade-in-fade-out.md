## Fade-in and fade-out

Fade-in and fade-out are gradual opacity transitions. 

### Add fade-in and fade-out

> Placeholder for video/add-fadein-fadeout.mp4

1. Select one or more strips
2. Press <kbd>f</kbd> 

### Add fade-in

> Placeholder for video/add-fadein.mp4

1. Select one or more strips
2. Press <kbd>Ctrl</kbd><kbd>f</kbd> (*shortcut for operator: `PS.Fade strips`*)

### Add fade-out

> Placeholder for video/add-fadeout.mp4

1. Select one or more strips
2. Press <kbd>Alt</kbd><kbd>f</kbd>

### General fade tips

When you apply a fade, its transition function will appear in the [Blender graph editor](https://docs.blender.org/manual/en/dev/editors/graph_editor/introduction.html). You can edit individual key frames to adjust the fade as you like.

Try to add fades at the very end of your video editing process otherwise you can encounter caveats that can create slowdowns; if you want to know more, see the documentation video ["Power Sequencer: Fade in, fade out"](https://youtu.be/7v2WLP-gqJQ?t=2m16s).

#### Add a fade with operator 
By default `PS.Fade strips` will use the *Fade-in*, but you can also use other types with these steps: 

1. Select one or more strips
2. Use the `PS.Fade strips operator` (<kbd>Ctrl</kbd><kbd>f</kbd>)
4. Press <kbd>F6</kbd> to access operator properties
5. Change `Fade Type`

### Techniques

#### Dim a strip

1. Add a color strip above on che channel above the strip you want to dim
    1. Press <kbd>Shift</kbd><kbd>a</kbd> 
    2. Select *Effect Strip -> Color*
2. Select the color strip
3. Adjust the length of the color strip
4. Set blend to alpha over
5. Set the desired max opacity (e.g. 0.5)
6. Press <kbd>f</kbd> 
