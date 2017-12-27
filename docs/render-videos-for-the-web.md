## Render videos for the web

Applies a rendering preset (specified in the preferences) and,
optionally, starts the rendering.

### TODO - Using the operator

### Change rendering preferences

1. Press <kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>U</kbd> to access *User Preferences*
2. Select the *Input tab*
3. Search for `PS.Render video for the web`

![Rendering videos preferences](img/rendering-videos-preferences-highlight.png)

#### Preset option

The preset contains rendering options such as resolution, container, and codecs.

At the moment there are only two presets available.

| Preset      | Resolution | Container | Video codec | Audio codec |
| -           | -          | -         | -           | -           |
| **youtube** | 1080p      | mp4       | h264        | AAC         |
| **twitter** | 720p       | mp4       | h264        | AAC         |


#### Filename option

Filename of the rendered video. It can be one of:
- Blender file
- Current scene
- Folder (it's the name of the folder containing the main .blend file) 

#### Auto render option

If the *Auto render* option is enabled, `PS.Render video for the web` will
automatically start the rendering.
