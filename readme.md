goal: have a stream layout that helps people join and get their bearings

see stream-view.png for high-level layout
	- should make code the focus (when in terminal)
	- include chat
	- include music
	- include keystrokes
		- widget that shows "how" I'm typing
		- answers questions like "what movement command was that in vim?"
		- persists long enough for seqs to be grokked
	- stream metadata
	- speed runner 'splits'

note:
	- can start a debug copy of the keystrokes widget in chrome by opening file://wsl$/Ubuntu/path/to/keystrokes/input-history-windows.html

todo:
- bouncing 'j/k' should just flash the existing 'j' and 'k' elements
- 'shift+5' should be '%'
- bug: spam >> wait for clear >> input-is-ignored >> spam >> input-is-recognized
- since combo strokes are wider than singles, a seq of many combos followed by
  singles shifts the 'cursor' left as typing happens ;;; jarring
		- fix: make everything fixedwidth
		- fix: align list items to the right
- 'j + space' ==> ' + space' ... O_o
- when repeating, we're erasing the key for the repeat counter O_O !! _if_ font size is increased ...
