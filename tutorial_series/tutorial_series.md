Blender VSE Tutorial Series
===========================
Thoughts on Style
-----------------
(This isn't one of the tutorials, just some ideas about what makes a
good tutorial)

* Brevity is the soul of wit
* Avoid long introductions of yourself, your brand, etc.
* No background music.
* Humour is a good way to recapture attention
* Start videos with an explanation of what will be accomplished
* If you want to be awesome, finish the video with a quick summary of
  what was learned
* Ideally a tutorial should be 10-20 minutes or less (see
  [wikipedia](https://en.wikipedia.org/wiki/Attention_span))
* Use a quality microphone. Try using Audacity's noise removal method.
* Let's all agree on a frame rate and resolution
* Use a software that demonstrates what keys you're pushing. I like
  [key-mon](https://pypi.python.org/pypi/key-mon)

Intro to the series
-------------------
* What people will learn
* How to make the most out of it

Intro to Blender for Video Editing: Strengths and Limitations
-------------------------------------------------------------
* Blender is free and always will be.

  - What is FOSS?
  - No user account required
  - No annoying advertisements or awkward emails
  - No frustrating customer service
  - Working together with other people is easier because the software is
    free. (Good luck convincing your friends to buy After Effects so
    they can help you edit.)

* Blender is open source, it's code is read and edited by people from
  all over the world.

  - Not collecting personal data
  - Not filled with viruses or other malware

* Blender works on Windows, MacOS, Linux
* Vibrant community filled with Blender users who want to give back

  - Blender stack exchange
  - Blenderartists
  - Blendswap
  - Blender subreddit
  - Hundreds of user-made addons

* Blender is a "gateway drug" that helps you explore other art forms

  - 3D modeling
  - Animation
  - Game design
  - Computer programming

* Hotkeys; Custom Hotkeys for anything! (Makes Blender hard at first,
  but way faster in the long run)

Whatever else from GDQuest's
[presentation](https://github.com/GDquest/blender-sequencer-presentation)
(I don't read French)

VSE Interface
-------------
Project goal: load 2 videos into the vse, trim one of them, line them
up, render the video out as .mp4. I vote we leave out any add-ons and
just keep this to Blender's defaults for this video

* Changing from the default Blender view to the Video Editing view
* Add a video to the timeline by dragging it in (One that is NOT
  1920x1080 so we can demonstrate the need to correct the resolution)

  - The clip will start wherever the cursor is located

* Audio strips vs video strips (light green vs blue)
* Dragging the cursor to shuttle through video

  - Enable audio scrubbing
  - Enable AV-Sync
  - Enable Frame-Dropping

* Playing/Pausing the video with Alt+A key combo
* Selecting strips

  - Right clicking
  - Shift + Right Clicking
  - Using the A key to toggle selection of all strips
  - Using B to box select
  - Using B + Middle Mouse Button to Unselect

* Showing the Audio Waveform

  - Demonstrate that the right side menu can be toggled using the N key

* Fixing the resolution & Frame rate

  - Change the "Graph Editor" screen to "Properties." Explain that all
    screens in Blender can be switched to any other.
  - Set the resolution manually to match the video

    + Explain that all videos are just pixels; the resolution is the
      number of pixels horizontally and vertically
    + Video resolution can be double-checked using the program
      [Mediainfo](https://mediaarea.net/en/MediaInfo)

  - Blender will automatically set the frame rate when a file is loaded
    into the timeline, but the resolution needs to be set later.
  - You can automatically set the resolution by selecting the video
    strip, then going to Strip > Set Render Size

* Load in the next video using Shift+A method

  - Explain that the mouse must be in the correct screen for shortcuts
    to work

* Make a Cut using K button

  - Notice how whichever side the mouse was on is the strip that remains
    selected after cutting.
  - Delete the garbage segment

* Explain grabbing of video using the G key

  - Line up the two remaining strips
  - Use the middle mouse wheel to zoom in and out of the timeline
  - Use the middle mouse button to pan left and right in the timeline

* Set the Start and End Points, describe the current frame property too
* Set the render properties

  - Change the file format to FFMPEG
  - Use the h264 in MP4 encoding preset
  - Set the audio codec to AAC
  - Set the output filepath

* Render the video and watch it play in VLC

Streamlining Your Workflow: Tricks to Edit Quickly
--------------------------------------------------
Do the same work as the last video, but show off proxies and some common
tools in Power Sequencer including: concatenate strips, mouse cut,
ripple delete, toggle waveforms, preview to selection, fade

* Set up the Blender user interface with Custom settings and save the
  startup file

  - Change the Graph screen to properties
  - Set the resolution
  - Set the output render format (ffmpeg, h264 in MP4, audio as AAC)
  - Enable audio scrubbing
  - Enable AV-Sync
  - Enable Frame-Dropping
  - Close and re-open blender to show that it works
  - Setup a custom hotkey for the set render size function

* Load in a high-resolution video clip.
* Add another high resolution clip, spaced out from the first (so we can
  show off concatenating them later)
* Demonstrate that shuttling through the clips is laggy
* Explain what a proxy video file is and why it fixes the lagginess.
  Final rendering will use the original source file, not the proxy file.
* Generate 25% proxies for all the clips and set the proxy render size
  accordingly.
* Demonstrate how the proxy has sped up shuttling
* Install Power Sequencer

  - Briefly describe the readme page and how users can find more
    information
  - Installing and saving user settings
  - Briefly cover the automatic updater

* Demonstrate changing playback speed with 1, 2, 3, 4 and brackett keys.
* Concatenate the strips
* Toggle all the waveforms, (explain that you can toggle the waveform of
  just selected strips too which may be nice if you have some long audio
  strips in the project)
* Use mouse cut (using ctrl+LMB) to edit out a spot in the first clip
* Use ripple delete to remove the garbage
* Change the start and end points using the preview to selection
  function
* Add a fade-in and fade out to both the video and the audio.
  Demonstrate clearing the fades
* Check that everything is lined up. Zoom in using Shift+B, zoom back
  out using the home key. Mention that using the period key will zoom
  out to just the selected strip while the home key will zoom out to the
  entire project.
* Instead of rendering out to a .mp4, save the project as a .blend file

  - Mention that the source files are not included in the .blend file
  - Moving source files around will mess stuff up
  - It's best to keep projects organized in a separate folder where
    relative paths will stay the same even if the folder is moved.

More Strip Manipulations
------------------------
Project idea: Say you were filming someone giving a talk as they
described how to use Blender stack exchange. The person you're recording
is speaking into a microphone, so you want to use the audio from that
but the video from your phone. You also want to add in an image that
shows what the speaker is describing; complete with little arrows that
highlight different spots on the webpage.

* Add the video clip of the person talking and the audio from the
  microphone
* Add the nice audio
* Synchronize the 2 audios
* Add an image of Blender Stack Exchange's website by dragging it into
  the timeline

  - Mention that blender stack exchange is a great place to get answers
    to specific questions about how to use Blender.

* Add/Edit crossfade into the image showing Blender Stack Exchange
* How to install VSE_Transform_Tools
* Adding text using images created in GIMP

  - Mention that you *can* use the text strip modifier, but you can't
    change the font. This is planned to be fixed in future versions of
    Blender.
  - Mention that you *can* use a font object from the 3D view, but this
    is beyond the scope of the tutorial and it's not really the best way
    to do it anyway.
  - Use Alt+S to set scale of images to default
  - Demonstrate how you can select different videos with the Right mouse
    button
  - Scale and position the text images

* Using VSE_Transform_Tools to add, scale, rotate, and animate little
  arrows.

  - Use the duplicate method to make more of them.

Making Animated GIFs
--------------------
Project Idea: Making an animated GIF to share on Reddit, Blender Stack
exchange, text to friends, etc. This will demonstrate cropping, the
speed modifier, and Bligify.

* Add in a video clip
* Edit the start and end points and do preview to selection
* Crop the video
* Autocrop (adjusts the resolution to match the video)
* Use Add-Speed method to make it 2x's as fast
* Install Bligify
* Explain how to open blender from a terminal (or how to open the
  console if you're on Windows)

  - Mention that using Bligify on Mac requires you to open Blender from
    a console

* Use the FPS adjust to set the frame rate to 10
* Render the animated GIF

  - Mention that different render settings will influence the quality
    and filesize

Subtitling
----------
Project idea: Adding subtitles to a tutorial video (2 birds, 1 stone right?)

* Install subsimport
* Disable Power Sequencer (conflict with F keyboard shortcut)
* Load a .txt file
* Delete the video, add wave forms to audio
* Use keyboard shortcuts to line up subtitles with audio
* Consider slowing audio with audacity
* Demonstrate editing a .srt file
* Demonstrate automatic subtitling using Aeneas like a boss.
