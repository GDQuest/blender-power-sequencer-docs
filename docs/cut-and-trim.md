## Cut and Trim with the Mouse

You can cut and trim strips with mouse clicks using the add-on.

The cut and trim tool has two main modes:

1. The **smart** mode is the default. If you click on a strip, it will only cut this strip. If you click on a gap between two blocks of strips, it will remove the gap. And if you click above the strips, it will cut every strip in the sequencer on that frame.
2. The **time cursor** mode always cuts or trims all strips under the time cursor or on a given frame.

### Cut strips

#### Cut a single strip at a time

![Cut strip GIF](./img/mouse-cut-single-strip.gif)

1. Place the mouse cursor over the strip to cut
2. Press <kbd>Ctrl</kbd><kbd>Action Mouse</kbd>

*By default <kbd>Action Mouse</kbd> is <kbd>Left Click</kbd> and <kbd>Select Mouse</kbd> corresponds to <kbd>Right Click</kbd>*

#### Cut all strips under the time cursor

![Cut all strips GIF](./img/mouse-cut-all.gif)

1. Place the mouse cursor on the sequencer, without hovering any strips
2. Press <kbd>Ctrl</kbd><kbd>Action Mouse</kbd>

To always cut in **time cursor** mode, press <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>Action Mouse</kbd> instead.

You can also use this operator to cut gaps between strips. Hover a gap and press <kbd>Ctrl</kbd><kbd>Action Mouse</kbd> to remove it.

### Trim strips

#### Trim a single strip at a time

![Trim strip GIF](./img/mouse-trim-single-strip.gif)

1. Place the mouse cursor over the strip that you want to cut
2. Press <kbd>Ctrl</kbd><kbd>Select Mouse</kbd>

#### Trim all strips

![Trim all strips GIF](./img/mouse-trim-all-strips.gif)

1. Place the mouse cursor on the sequencer, without hovering on any strips
2. Press <kbd>Ctrl</kbd><kbd>Select Mouse</kbd>

To always trim in **time cursor** mode, press <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>Action Mouse</kbd> instead.

---

Keyobard shortcuts are the quickest way to activate these operations, but they also can be accessed by the [operator search pop-up menu](https://docs.blender.org/manual/en/dev/interface/controls/templates/operator_search.html).


## Toggle Mute strips

Press <kbd>Alt</kbd><kbd>Action Mouse</kbd> on a strip to toggle it muted with the mouse.

This leaves the strip in the channel so when you trim audio or footage around it, the muted strip will block the rest of the edits.

It's useful when you're editing audio separately from the video which is common with tutorials and other screencasts.

*It also works during playback and leaves the time cursor running.*


### Techniques

You can resize mute strips to add space between 2 other strips. Grab the mute sequence's handle, and keep the alt key down to ripple the edit.

Want to shorten it instead? Mouse trim it with Ctrl Right Click, and let Power Sequencer remove the gap.

#### Add a muted sound strip to leave some space in your edits

Select and drag the left handle of the sequence to the right of a cut to extend it while you keep the <kbd>Alt</kbd> key down. This will ripple the edit, or push the sequence to the right.

<kbd>Ctrl</kbd><kbd>Action Mouse</kbd> to cut the extra audio or footage, and <kbd>Alt</kbd><kbd>Action Mouse</kbd> the new small sound sequence. You now have a block that will leave some time between the 2 sequences, even when you remove all gaps!

#### Quickly cut and mute bad sounds with the mouse

It's common to have pops, or little coughs in the audio. Often the speaker is so fast you don't want to trim them. Instead, you'd rather keep the strip around as a spacer but you may want to mute them.

1. <kbd>Ctrl</kbd><kbd>Action Mouse</kbd> before and after the incriminated sound on the waveform to cut a new strip.
2. <kbd>Alt</kbd><kbd>Action Mouse</kbd> on the new sound strip to mute it.
