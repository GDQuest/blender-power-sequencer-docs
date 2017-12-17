## Crossfades

Crossfades or dissolves are smooth transitions from one video or image strip to another. To achieve a crossfade in Blender you add a cross or gamma cross effect strip that stacks on top of two video or image strips.

### Add a crossfade

> Placeholder for video: add-crossfade.mp4

1. Select one strip to fade from
1. Press <kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>c</kbd> (*shortcut for `PS.Add Crossfade` operator*)

*Power Sequencer finds the closest strip to fade to for you. It looks from strips that start after the active selected strip end frame. If the strip already overlaps with your selection Power Sequencer will ignore it and move to the next one in the editor. It will also first look for strips in the same channel or neighboring channels.*

### Slide a crossfade

> Placeholder for video: edit-crossfade.mp4

1. Select the Gamma Cross effect strip
1. Press <kbd>Alt</kbd><kbd>c</kbd> (*shortcut for `PS.Edit crossfade` operator*)

*This tool finds and selects the handles of the effect's input strips. Then it fires the grab mode. It's a shortcut to move a gamma cross effect faster.*
