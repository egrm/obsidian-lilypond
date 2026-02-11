# Obsidian Lilypond Plugin

Render [LilyPond](https://lilypond.org/) notation directly in Obsidian.

Originally created by Egor Gromyko. Special thanks to [dot-asterisk-nl](https://github.com/dot-asterisk-nl) for maintaining the project.

## Setup

Ensure you have [LilyPond installed](https://lilypond.org/). In the plugin settings, set "Lilypond Path" to the `lilypond` executable:

- **Linux**: `/usr/bin/lilypond`
- **Windows**: `C:\Program Files (x86)\LilyPond\usr\bin\lilypond-windows.exe`

## Usage

Write a code block with the `lily` language identifier:

	```lily
		\score{
			\relative c' {a}
			\layout {}
		}
	```

Any valid LilyPond code is supported.
