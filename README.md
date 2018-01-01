# Blender Power Sequencer docs

Source repository for [Power Sequencer](https://github.com/GDquest/Blender-power-sequencer/), the Open Source Blender add-on for video makers.

To read the documentation, head to the [ add-on's GitHub wiki ](https://github.com/GDquest/Blender-power-sequencer/wiki). We use this repository to write the documentation with other contributors and collect videos.

## Docs writing guidelines

Documenting a tool in the docs doesn't take much time and helps up tremendously! If you enjoy using Power Sequencer, it's a great way to contribute to the project.

We follow a few guidelines to make sure the content is well-structured and as clear as can be. They're the same as the Godot engine's [ docs writing guidelines ](http://docs.godotengine.org/en/latest/community/contributing/docs_writing_guidelines.html):

1. Use the direct voice instead of the passive voice
1. Use precise action verbs
1. Avoid verbs that end in -ing
1. Remove unnecessary adverbs and adjectives.
1. Ban these 8 words: obvious, simple, basic, easy, actual, just, clear, and however
1. Use explicit references
1. Use ‘s to show possession
1. Use the Oxford comma

In short, we favor simple English, a coherent structure and short sentences to make the docs more pleasant to read.

## How to write docs for a given feature

1. Use h2 `##` for the first title and h3 `###` for sub-sections
1. Start with the title, a short description, followed by a 480p screen recording and the steps to use the tool
1. Use the html `<kbd></kbd>` tag for keystrokes. Don't put spaces between keyboard tags. E.g. for <kbd>Shift</kbd><kbd>c</kbd> write `<kbd>Shift</kbd><kbd>c</kbd>`.

See [Import local footage](./docs/import-local-footage.md) and [Cut and Trim with the mouse](./docs/cut-and-trim.md) for examples.

If you need more info, a review, or help to record the video demo, count on us! You can open an issue on GitHub, or contact [ GDquest on Twitter ](https://twitter.com/NathanGDquest).

## Helpful snippets

Regex to add `kbd` tags around keyboard shortcuts:

- Emacs sed command -> `s/\( ?\(Shift\|Ctrl\|Alt\|Action Mouse\|Select Mouse\|F[0-9]\|[A-Z0-9]\) ?\)/<kbd>\2<\/kbd>/g`

## Credits

Online docs:

- [ Davide Cristini ](https://github.com/davcri)
- Nathan Lovato

Videos:

- Nathan Lovato ([ GDQuest ](https://twitter.com/NathanGDquest))
